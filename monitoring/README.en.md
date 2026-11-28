<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for St Gallen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 09:11 UTC, St Gallen: systematic collection (www.gesetzessammlung.sg.ch): 293 addresses read; 0 added, 0 changed, 0 removed; no change; 6 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [St Gallen: systematic collection (www.gesetzessammlung.sg.ch)](https://www.gesetzessammlung.sg.ch/) | `<act>/` | daily | 2026-11-28 09:11 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 09:06](checks/2026-11.md#ch-lexwork-st-gallen-20261128t090605z) | lexwork-st-gallen | 293 | 0 | 0 | 0 | 6 (0) | no change `verify-differ` | — |
| [2026-11-28 08:09](checks/2026-11.md#ch-lexwork-st-gallen-20261128t080940z) | lexwork-st-gallen | 129 | 0 | 0 | 0 | 5 (0) | the check failed | — |
| [2026-11-28 07:06](checks/2026-11.md#ch-lexwork-st-gallen-20261128t070647z) | lexwork-st-gallen | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:37](checks/2026-11.md#ch-lexwork-st-gallen-20261128t063729z) | lexwork-st-gallen | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 06:45](checks/2026-11.md#ch-lexwork-st-gallen-20261127t064506z) | lexwork-st-gallen | 234 | 0 | 1 | 0 | 4 (0) | changes found `verify-differ` | — |
| [2026-11-26 06:43](checks/2026-11.md#ch-lexwork-st-gallen-20261126t064345z) | lexwork-st-gallen | 411 | 0 | 0 | 0 | 5 (0) | no change `verify-differ` | — |
| [2026-11-25 07:51](checks/2026-11.md#ch-lexwork-st-gallen-20261125t075152z) | lexwork-st-gallen | 275 | 0 | 0 | 0 | 2 (0) | no change `verify-differ` | — |
| [2026-11-24 12:23](checks/2026-11.md#ch-lexwork-st-gallen-20261124t122352z) | lexwork-st-gallen | 405 | 0 | 3 | 0 | 4 (0) | changes found `verify-differ` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
