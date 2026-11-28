<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für St Gallen: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 09:11 UTC, St Gallen: Systematische Sammlung (www.gesetzessammlung.sg.ch): 293 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 6 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [St Gallen: Systematische Sammlung (www.gesetzessammlung.sg.ch)](https://www.gesetzessammlung.sg.ch/) | `<act>/` | täglich | 2026-11-28 09:11 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 09:06](checks/2026-11.md#ch-lexwork-st-gallen-20261128t090605z) | lexwork-st-gallen | 293 | 0 | 0 | 0 | 6 (0) | keine Änderung `verify-differ` | — |
| [2026-11-28 08:09](checks/2026-11.md#ch-lexwork-st-gallen-20261128t080940z) | lexwork-st-gallen | 129 | 0 | 0 | 0 | 5 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-28 07:06](checks/2026-11.md#ch-lexwork-st-gallen-20261128t070647z) | lexwork-st-gallen | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-28 06:37](checks/2026-11.md#ch-lexwork-st-gallen-20261128t063729z) | lexwork-st-gallen | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-27 06:45](checks/2026-11.md#ch-lexwork-st-gallen-20261127t064506z) | lexwork-st-gallen | 234 | 0 | 1 | 0 | 4 (0) | Änderungen gefunden `verify-differ` | — |
| [2026-11-26 06:43](checks/2026-11.md#ch-lexwork-st-gallen-20261126t064345z) | lexwork-st-gallen | 411 | 0 | 0 | 0 | 5 (0) | keine Änderung `verify-differ` | — |
| [2026-11-25 07:51](checks/2026-11.md#ch-lexwork-st-gallen-20261125t075152z) | lexwork-st-gallen | 275 | 0 | 0 | 0 | 2 (0) | keine Änderung `verify-differ` | — |
| [2026-11-24 12:23](checks/2026-11.md#ch-lexwork-st-gallen-20261124t122352z) | lexwork-st-gallen | 405 | 0 | 3 | 0 | 4 (0) | Änderungen gefunden `verify-differ` | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
