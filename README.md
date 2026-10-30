# St. Gallen: law history in git

The law of the canton of St. Gallen (Kanton St.Gallen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-sg/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

344 acts with 1092 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 225 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-1-kv/` | Verfassung des Kantons St.Gallen (sGS 111.1) | 1 | one version (the oldest available), 17 May 2009 |
| `117-1-adg/` | Gesetz über die Amtsdauer (sGS 117.1) | 1 | as enacted, 10 June 2008 |
| `121-1-brg/` | Gesetz über das St.Galler Bürgerrecht (sGS 121.1) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `125-1-rig/` | Gesetz über Referendum und Initiative (sGS 125.1) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `125-3-wag/` | Gesetz über Wahlen und Abstimmungen (sGS 125.3) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `140-1-stvg/` | Staatsverwaltungsgesetz (sGS 140.1) | 9 | as enacted, then each consolidated version: 1 June 2012 to 1 July 2022 |
| `140-2-oeffg/` | Öffentlichkeitsgesetz (sGS 140.2) | 2 | as enacted, then each consolidated version: 18 November 2014 to 1 July 2023 |
| `140-3-pubg/` | Publikationsgesetz (sGS 140.3) | 1 | as enacted, 1 June 2019 |
| `142-1-dsg/` | Datenschutzgesetz (sGS 142.1) | 3 | as enacted, then each consolidated version: 16 November 2010 to 25 June 2019 |
| `142-3-e-govg/` | Gesetz über E-Government (sGS 142.3) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 January 2026 |
| `143-1-persg/` | Personalgesetz (sGS 143.1) | 7 | as enacted, then each consolidated version: 31 January 2012 to 1 March 2026 |
| `146-1/` | Statistikgesetz (sGS 146.1) | 1 | as enacted, 1 July 2012 |
| `147-1-gaa/` | Gesetz über Aktenführung und Archivierung (sGS 147.1) | 3 | as enacted, then each consolidated version: 1 July 2011 to 1 January 2019 |
| `151-2-gg/` | Gemeindegesetz (sGS 151.2) | 11 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `151-3-gvg/` | Gemeindevereinigungsgesetz (sGS 151.3) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `153-1-ggu/` | Gesetz über gemeinschaftliche Unternehmen (sGS 153.1) | 1 | one version (the oldest available), 1 January 2010 |
| `161-1-vg/` | Gesetz über die Haftung der öffentlich-rechtlichen Körperschaften und Anstalten und die Verantwortlichkeit der Behörden und öffentlichen Angestellten (Verantwortlichkeitsgesetz) (sGS 161.1) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `161-3-dg/` | Gesetz über die disziplinarische Verantwortlichkeit der Behördemitglieder, Beamten und öffentlichen Angestellten (Disziplinargesetz) (sGS 161.3) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `171-0-rgg/` | Gesetz über die öffentlich-rechtlich anerkannten Religionsgemeinschaften (sGS 171.0) | 1 | one version (the oldest available), 1 January 2019 |
| `211-5-stipg/` | Gesetz über die staatlichen Stipendien und Studiendarlehen (Stipendiengesetz) (sGS 211.5) | 2 | as enacted, then each consolidated version: 10 January 2002 to 1 August 2015 |
| `213-1-vsg/` | Volksschulgesetz (sGS 213.1) | 17 | oldest version available, then each consolidated version: 27 November 2012 to 1 September 2024 |
| `213-51-llg/` | Gesetz über den Lohn der Volksschul-Lehrpersonen (sGS 213.51) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2020 |
| `215-1-msg/` | Mittelschulgesetz (sGS 215.1) | 8 | as enacted, then each consolidated version: 7 August 2012 to 1 October 2026 |
| `216-0-gphsg/` | Gesetz über die Pädagogische Hochschule St.Gallen (sGS 216.0) | 3 | as enacted, then each consolidated version: 24 April 2012 to 1 June 2016 |
| `217-1-ug/` | Universitätsgesetz (sGS 217.1) | 1 | as enacted, 1 January 2024 |
| `219-1-ght/` | Gesetz über die privaten Hochschulen und den Titelschutz (sGS 219.1) | 1 | as enacted, 1 January 2024 |
| `221-1-kibg/` | Gesetz über Beiträge für familien- und schulergänzende Kinderbetreuung (sGS 221.1) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2024 |
| `231-1-eg-bb/` | Einführungsgesetz zur Bundesgesetzgebung über die Berufsbildung (sGS 231.1) | 7 | as enacted, then each consolidated version: 31 January 2012 to 1 September 2024 |
| `251-1/` | Einführungsgesetz zur Bundesgesetzgebung über die Förderung von Turnen und Sport (sGS 251.1) | 1 | as enacted, 9 June 1985 |
| `273-1/` | Gesetz über Beiträge an die Genossenschaft Konzert und Theater St.Gallen (sGS 273.1) | 1 | as enacted, 1 January 2010 |
| `275-1-kfg/` | Kulturförderungsgesetz (sGS 275.1) | 2 | as enacted, then each consolidated version: 1 July 1996 to 1 January 2018 |
| `276-1/` | Bibliotheksgesetz (sGS 276.1) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2018 |
| `277-1-keg/` | Kulturerbegesetz (sGS 277.1) | 1 | as enacted, 1 January 2018 |
| `311-1-gesg/` | Gesundheitsgesetz (sGS 311.1) | 7 | oldest version available, then each consolidated version: 1 January 2013 to 1 March 2026 |
| `311-2-sug/` | Suchtgesetz (sGS 311.2) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2015 |
| `312-2-eg-bfap/` | Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (sGS 312.2) | 1 | as enacted, 1 July 2024 |
| `315-1-eg-lmg/` | Einführungsgesetz zur eidgenössischen Lebensmittelgesetzgebung (sGS 315.1) | 1 | as enacted, 28 July 2009 |
| `320-1-spfg/` | Gesetz über die Spitalplanung und -finanzierung (sGS 320.1) | 4 | as enacted, then each consolidated version: 1 January 2012 to 1 July 2024 |
| `320-2-gsv/` | Gesetz über den Spitalverbund (sGS 320.2) | 6 | as enacted, then each consolidated version: 31 January 2012 to 1 January 2025 |
| `320-5-gpv/` | Gesetz über den Psychiatrieverbund (sGS 320.5) | 4 | as enacted, then each consolidated version: 31 January 2012 to 1 January 2025 |
| `320-22-gzl/` | Gesetz über das Zentrum für Labormedizin (sGS 320.22) | 4 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `331-2-pfg/` | Gesetz über die Pflegefinanzierung (sGS 331.2) | 5 | as enacted, then each consolidated version: 1 January 2011 to 1 April 2021 |
| `331-11-eg-kvg/` | Einführungsgesetz zur Bundesgesetzgebung über die Krankenversicherung (sGS 331.11) | 7 | oldest version available, then each consolidated version: 1 January 2012 to 1 January 2026 |
| `350-1-eg-ahv/` | Einführungsgesetz zur Bundesgesetzgebung über die Alters-, Hinterlassenen- und Invalidenversicherung (sGS 350.1) | 2 | as enacted, then each consolidated version: 26 June 2012 to 1 January 2024 |
| `351-5-elg/` | Ergänzungsleistungsgesetz (sGS 351.5) | 6 | as enacted, then each consolidated version: 27 September 2009 to 1 January 2024 |
| `361-0-alvg/` | Gesetz über Arbeitslosenversicherung und Arbeitsvermittlung (sGS 361.0) | 1 | as enacted, 22 January 2008 |
| `371-1/` | Einführungsgesetz zur Bundesgesetzgebung über die Familienzulagen (sGS 371.1) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `372-1-geb/` | Gesetz über Elternschaftsbeiträge (sGS 372.1) | 3 | as enacted, then each consolidated version: 23 January 2007 to 1 January 2026 |
| `381-1-shg/` | Sozialhilfegesetz (sGS 381.1) | 11 | oldest version available, then each consolidated version: 1 January 2013 to 1 March 2026 |
| `381-4-behg/` | Gesetz über die soziale Sicherung und Integration von Menschen mit Behinderung (sGS 381.4) | 4 | as enacted, then each consolidated version: 1 January 2013 to 1 October 2026 |
| `383-1/` | Gesetz über die Aufhebung der Kantonshilfskasse für nichtversicherbare Schäden bei Elementarereignissen (sGS 383.1) | 2 | as enacted, then each consolidated version: 17 May 2009 to 1 January 2023 |
| `411-1/` | Gesetz über das Militärwesen (sGS 411.1) | 1 | as enacted, 1 June 2000 |
| `413-1/` | Einführungsgesetz zur Bundesgesetzgebung über den Zivilschutz (sGS 413.1) | 2 | as enacted, then each consolidated version: 29 June 2004 to 1 January 2019 |
| `421-1-bevsg/` | Bevölkerungsschutzgesetz (sGS 421.1) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 September 2024 |
| `431-1/` | Gesetz über den Vollzug der wirtschaftlichen Landesversorgung (sGS 431.1) | 1 | as enacted, 1 January 2011 |
| `451-1-pg/` | Polizeigesetz (sGS 451.1) | 6 | as enacted, then each consolidated version: 24 April 2012 to 1 January 2025 |
| `453-1-nag/` | Gesetz über Niederlassung und Aufenthalt (sGS 453.1) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `455-1-eg-bgs/` | Einführungsgesetz zur Bundesgesetzgebung über Geldspiele (sGS 455.1) | 2 | as enacted, then each consolidated version: 9 November 1995 to 1 November 2020 |
| `456-1-hug/` | Hundegesetz (sGS 456.1) | 2 | as enacted, then each consolidated version: 9 January 2003 to 1 January 2020 |
| `458-1/` | Gesetz über die Friedhöfe und die Bestattungen (sGS 458.1) | 1 | one version (the oldest available), 1 January 2013 |
| `511-1/` | Einführungsgesetz zum eidgenössischen Arbeitsgesetz (sGS 511.1) | 1 | as enacted, 29 June 2004 |
| `515-1/` | Gesetz betreffend das kantonale Einigungsamt (sGS 515.1) | 1 | as enacted, 21 November 2006 |
| `552-1-rlg/` | Gesetz über Ruhetag und Ladenöffnung (sGS 552.1) | 1 | as enacted, 22 January 2008 |
| `552-5/` | Gesetz über den Abbau technischer Handelshemmnisse (sGS 552.5) | 1 | as enacted, 1 January 2001 |
| `553-1-gwg/` | Gastwirtschaftsgesetz (sGS 553.1) | 3 | as enacted, then each consolidated version: 22 January 2008 to 1 July 2024 |
| `554-1/` | Kinogesetz (sGS 554.1) | 1 | as enacted, 1 March 2008 |
| `555-1/` | Gesetz über das Pfandleihgewerbe (sGS 555.1) | 1 | as enacted, 1 June 2000 |
| `571-1/` | Gesetz über die Gewährung von ergänzenden Krediten und Solidarbürgschaften infolge des Coronavirus (sGS 571.1) | 1 | as enacted, 21 May 2020 |
| `571-3/` | Gesetz über die wirtschaftliche Unterstützung von Unternehmen sowie von durch die öffentliche Hand geführten Institutionen der familienergänzenden Kinderbetreuung in Zusammenhang mit der Covid-19-Epidemie (sGS 571.3) | 5 | as enacted, then each consolidated version: 18 February 2021 to 16 June 2022 |
| `573-0/` | Standortförderungsgesetz (sGS 573.0) | 2 | as enacted, then each consolidated version: 16 November 2010 to 1 January 2015 |
| `575-1/` | Tourismusgesetz (sGS 575.1) | 3 | as enacted, then each consolidated version: 1 April 1996 to 1 February 2023 |
| `610-1-lag/` | Landwirtschaftsgesetz (sGS 610.1) | 4 | as enacted, then each consolidated version: 21 November 2006 to 1 March 2025 |
| `633-1-melg/` | Meliorationsgesetz (sGS 633.1) | 2 | as enacted, then each consolidated version: 23 January 2007 to 1 October 2017 |
| `633-3/` | Gesetz über die Melioration der Rheinebene und die Errichtung eines Arbeitsbeschaffungskontos (sGS 633.3) | 2 | as enacted, then each consolidated version: 31 January 2012 to 1 June 2016 |
| `643-1-vetg/` | Veterinärgesetz (sGS 643.1) | 2 | as enacted, then each consolidated version: 28 July 2009 to 1 January 2016 |
| `651-1/` | Einführungsgesetz zur eidgenössischen Waldgesetzgebung (sGS 651.1) | 4 | as enacted, then each consolidated version: 23 September 2007 to 1 July 2023 |
| `671-7-gaol/` | Gesetz über die Abgeltung ökologischer Leistungen (sGS 671.7) | 2 | as enacted, then each consolidated version: 21 June 2002 to 1 January 2015 |
| `672-1-eg-usg/` | Einführungsgesetz zur eidgenössischen Umweltschutzgesetzgebung (sGS 672.1) | 2 | as enacted, then each consolidated version: 1 January 2012 to 1 October 2017 |
| `672-5/` | Einführungsgesetz zur eidgenössischen Chemikaliengesetzgebung (sGS 672.5) | 1 | as enacted, 1 January 2008 |
| `710-5-gov/` | Gesetz über den öffentlichen Verkehr (sGS 710.5) | 3 | as enacted, then each consolidated version: 3 August 2010 to 1 January 2016 |
| `711-70-svag/` | Gesetz über die Strassenverkehrsabgaben (sGS 711.70) | 4 | as enacted, then each consolidated version: 29 November 2011 to 1 October 2026 |
| `714-1/` | Gesetz über die Schiffahrt auf den öffentlichen Gewässern (sGS 714.1) | 1 | as enacted, 1 July 1965 |
| `714-2/` | Gesetz über die Wasserfahrzeugsteuer (sGS 714.2) | 1 | one version (the oldest available), 21 November 2006 |
| `731-1-pbg/` | Planungs- und Baugesetz (sGS 731.1) | 10 | as enacted, then each consolidated version: 19 April 2011 to 1 June 2026 |
| `732-1-strg/` | Strassengesetz (sGS 732.1) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `734-1-wbg/` | Wasserbaugesetz (sGS 734.1) | 5 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2023 |
| `734-21-rhg/` | Rheingesetz (sGS 734.21) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 September 2025 |
| `734-22-rhesig/` | Gesetz über die Verfahren zur Verbesserung des Hochwasserschutzes am Rhein von der Illmündung bis zum Bodensee (sGS 734.22) | 1 | as enacted, 1 September 2025 |
| `734-31/` | Linthgesetz (sGS 734.31) | 1 | as enacted, 17 May 2009 |
| `735-1-entg/` | Enteignungsgesetz (sGS 735.1) | 1 | as enacted, 23 January 2007 |
| `737-1-gwe/` | Gesetz über Wohnbau- und Eigentumsförderung (sGS 737.1) | 1 | as enacted, 25 January 2005 |
| `737-7/` | Einführungsgesetz zum Bundesgesetz über die Verbesserung der Wohnverhältnisse in Berggebieten (sGS 737.7) | 1 | as enacted, 23 September 2007 |
| `741-1-eng/` | Energiegesetz (sGS 741.1) | 4 | oldest version available, then each consolidated version: 1 November 2012 to 1 July 2021 |
| `741-2/` | Einführungsgesetz zur eidgenössischen Stromversorgungsgesetzgebung (sGS 741.2) | 1 | as enacted, 1 January 2011 |
| `751-1-gng/` | Gesetz über die Gewässernutzung (sGS 751.1) | 2 | oldest version available, then each consolidated version: 17 May 2009 to 1 July 2021 |
| `752-2-gschvg/` | Vollzugsgesetz zur eidgenössischen Gewässerschutzgesetzgebung (sGS 752.2) | 2 | oldest version available, then each consolidated version: 19 April 2011 to 1 October 2017 |
| `760-1-geoig-sg/` | Geoinformationsgesetz (sGS 760.1) | 1 | as enacted, 1 June 2019 |
| `811-1-stg/` | Steuergesetz (sGS 811.1) | 15 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2027 |
| `813-1-fag/` | Finanzausgleichsgesetz (sGS 813.1) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `814-1-ggs/` | Gesetz über die Durchführung der Grundstückschätzung (sGS 814.1) | 1 | as enacted, 1 January 2001 |
| `816-1/` | Gesetz über die Kursaalabgabe (sGS 816.1) | 2 | as enacted, then each consolidated version: 1 December 2002 to 1 February 2023 |
| `851-1/` | Gesetz über das Salzregal (sGS 851.1) | 1 | as enacted, 1 October 1975 |
| `852-1/` | Gesetz über den Bergbau (sGS 852.1) | 1 | as enacted, 23 January 2007 |
| `853-1-jg/` | Gesetz über die Jagd, den Schutz der wildlebenden Säugetiere und Vögel sowie deren Lebensräume (Jagdgesetz) (sGS 853.1) | 6 | as enacted, then each consolidated version: 16 November 2010 to 1 April 2024 |
| `854-1/` | Gesetz über die Fischerei sowie den Schutz der im Wasser lebenden Tiere und deren Lebensgrundlagen (Fischereigesetz) (sGS 854.1) | 2 | as enacted, then each consolidated version: 16 November 2010 to 1 October 2017 |
| `861-2-kbg/` | Kantonalbankgesetz (sGS 861.2) | 1 | one version (the oldest available), 1 January 2004 |
| `864-1-pkg/` | Gesetz über die St.Galler Pensionskasse (sGS 864.1) | 3 | as enacted, then each consolidated version: 1 July 2013 to 1 January 2014 |
| `871-1-fsg/` | Gesetz über den Feuerschutz (sGS 871.1) | 3 | as enacted, then each consolidated version: 23 January 2007 to 1 January 2021 |
| `872-1/` | Gesetz über Beitragsleistung von Feuerversicherungsgesellschaften zu Feuerlöschzwecken (sGS 872.1) | 1 | as enacted, 20 December 1954 |
| `873-1-gvg/` | Gesetz über die Gebäudeversicherung (sGS 873.1) | 7 | oldest version available, then each consolidated version: 17 May 2009 to 1 January 2023 |
| `911-1-eg-zgb/` | Einführungsgesetz zum Schweizerischen Zivilgesetzbuch (sGS 911.1) | 7 | oldest version available, then each consolidated version: 1 January 2013 to 1 April 2019 |
| `911-51-givu/` | Gesetz über Inkassohilfe und Vorschüsse für Unterhaltsbeiträge (sGS 911.51) | 5 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `912-5-eg-kes/` | Einführungsgesetz zur Bundesgesetzgebung über das Kindes- und Erwachsenenschutzrecht (sGS 912.5) | 5 | as enacted, then each consolidated version: 1 January 2013 to 1 February 2024 |
| `914-1/` | Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (sGS 914.1) | 1 | as enacted, 15 June 2010 |
| `921-1-uestg/` | Übertretungsstrafgesetz (sGS 921.1) | 2 | as enacted, then each consolidated version: 28 July 2009 to 1 January 2019 |
| `941-1-gerg/` | Gerichtsgesetz (sGS 941.1) | 5 | oldest version available, then each consolidated version: 25 January 2011 to 1 June 2027 |
| `951-1-vrp/` | Gesetz über die Verwaltungsrechtspflege (sGS 951.1) | 12 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `963-70-anwg/` | Anwaltsgesetz (sGS 963.70) | 1 | as enacted, 1 January 2011 |
| `971-1/` | Einführungsgesetz zum Bundesgesetz über Schuldbetreibung und Konkurs (sGS 971.1) | 1 | as enacted, 25 January 2011 |
| `113-1/` | Wappenverordnung (sGS 113.1) | 1 | as enacted, 1 January 1982 |
| `121-11-brv/` | Verordnung über das St.Galler Bürgerrecht (sGS 121.11) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2020 |
| `125-11/` | Verordnung über die gemischte Unterschriftensammlung (sGS 125.11) | 1 | as enacted, 1 January 2026 |
| `125-31/` | Verordnung über das stehende Stimmregister (sGS 125.31) | 5 | oldest version available, then each consolidated version: 11 January 2011 to 1 January 2026 |
| `131-11-geschkr/` | Geschäftsreglement des Kantonsrates (sGS 131.11) | 11 | as enacted, then each consolidated version: 28 September 2011 to 1 January 2026 |
| `141-3-geschr/` | Geschäftsreglement der Regierung und der Staatskanzlei (sGS 141.3) | 16 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `141-41-delv/` | Delegationsverordnung (sGS 141.41) | 6 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `141-81/` | Verordnung über die Raumnutzung im Regierungsgebäude (sGS 141.81) | 4 | as enacted, then each consolidated version: 1 January 2012 to 1 April 2026 |
| `142-21/` | Verordnung über die Informatiksicherheit (sGS 142.21) | 1 | as enacted, 1 March 2004 |
| `142-22/` | Verordnung über die digitale Postbearbeitung in der Staatsverwaltung (sGS 142.22) | 1 | as enacted, 1 February 2022 |
| `142-31/` | Verordnung über das E-Login (sGS 142.31) | 1 | as enacted, 1 January 2026 |
| `143-4-eva-ms/` | Ergänzende Verordnung über das Arbeitsverhältnis der Mittelschul-Lehrpersonen (sGS 143.4) | 8 | oldest version available, then each consolidated version: 1 August 2013 to 1 August 2024 |
| `143-7-vvk/` | Verordnung über die Versicherungskasse für das Staatspersonal (sGS 143.7) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `143-11-persv/` | Personalverordnung (sGS 143.11) | 21 | as enacted, then each consolidated version: 1 January 2013 to 1 December 2028 |
| `143-23/` | Verordnung über die Bemessung des Lohns des Staatspersonals im Jahr 2026 (sGS 143.23) | 14 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `143-24/` | Verordnung zur Durchführung der Überprüfung der Lohngleichheitsanalysen (sGS 143.24) | 1 | as enacted, 1 January 2021 |
| `143-28-ausfv/` | Verordnung über die Beteiligung der Versicherten an der Ausfinanzierung der St.Galler Pensionskasse (sGS 143.28) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2018 |
| `143-70/` | Reglement über die Teilliquidation der Versicherungskasse für das Staatspersonal (sGS 143.70) | 1 | as enacted, 1 July 2012 |
| `143-71/` | Verordnung über die Teuerungszulagen an Rentenbezüger der Versicherungskasse für das Staatspersonal (sGS 143.71) | 1 | as enacted, 1 January 1994 |
| `143-210-besvmp/` | Besoldungsverordnung für Magistratspersonen (sGS 143.210) | 1 | one version (the oldest available), 1 January 2014 |
| `143-211-lfvmp/` | Verordnung über die Lohnfortzahlung für Magistratspersonen (sGS 143.211) | 1 | as enacted, 1 January 2014 |
| `145-1/` | Verordnung über die Vergütungen an Mitglieder von Kommissionen sowie Expertinnen und Experten der kantonalen Verwaltung (Vergütungsverordnung KomEx) (sGS 145.1) | 4 | oldest version available, then each consolidated version: 1 September 2012 to 1 June 2020 |
| `145-2/` | Verordnung über die Höhe, Ausrichtung und Ablieferung von Vergütungen im Zusammenhang mit der Einsitznahme in Organe von Organisationen mit kantonaler Beteiligung (Vergütungsverordnung) (sGS 145.2) | 3 | as enacted, then each consolidated version: 1 June 2016 to 1 June 2024 |
| `146-11/` | Statistikverordnung (sGS 146.11) | 3 | as enacted, then each consolidated version: 1 July 2012 to 1 January 2026 |
| `147-11-vaa/` | Verordnung über Aktenführung und Archivierung (sGS 147.11) | 1 | as enacted, 1 June 2019 |
| `151-51/` | Verordnung über die öffentliche Beurkundung und die Beglaubigung (sGS 151.51) | 3 | as enacted, then each consolidated version: 1 January 2006 to 1 October 2024 |
| `151-53-fhgv/` | Verordnung über den Finanzhaushalt der Gemeinden (sGS 151.53) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `161-5/` | Vereidigungsverordnung (sGS 161.5) | 1 | as enacted, 1 January 1985 |
| `161-11/` | Verordnung über die Sicherheitsleistung von Behördemitgliedern und Angestellten (sGS 161.11) | 2 | as enacted, then each consolidated version: 19 November 1996 to 1 June 2025 |
| `211-21-vsad/` | Verordnung über den Schulärztlichen Dienst (sGS 211.21) | 2 | as enacted, then each consolidated version: 1 August 2005 to 1 January 2020 |
| `211-51-stipv/` | Stipendienverordnung (sGS 211.51) | 8 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2025 |
| `211-54/` | Reglement über den Ausbildungsfonds für den Kanton St.Gallen (sGS 211.54) | 2 | as enacted, then each consolidated version: 1 January 2025 to 1 January 2026 |
| `211-731/` | Verordnung über die Umsetzung der IT-Bildungsoffensive (sGS 211.731) | 1 | as enacted, 1 April 2019 |
| `212-12/` | Verordnung über die Vergütungen an Volksschulträger für rückwirkende Entschädigungen an Lehrpersonen für Pausenaufsichten im Kindergarten (sGS 212.12) | 1 | as enacted, 7 December 2022 |
| `213-12-vvu/` | Verordnung über den Volksschulunterricht (sGS 213.12) | 7 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2022 |
| `213-13-szpv/` | Schulzahnpflegeverordnung (sGS 213.13) | 1 | as enacted, 30 October 2007 |
| `213-14-vpvl/` | Verordnung zum Personalrecht der Volksschul-Lehrpersonen (sGS 213.14) | 4 | as enacted, then each consolidated version: 13 December 2011 to 1 August 2023 |
| `213-550-vlvk/` | Verordnung über die kantonale Lehrerversicherungskasse (sGS 213.550) | 1 | one version (the oldest available), 1 January 2013 |
| `213-551/` | Verordnung über die Teuerungszulagen an die Rentenbezüger der kantonalen Lehrerversicherungskasse (sGS 213.551) | 1 | as enacted, 20 December 1994 |
| `213-552/` | Reglement über die Teilliquidation der kantonalen Lehrerversicherungskasse (sGS 213.552) | 1 | as enacted, 1 July 2012 |
| `213-951/` | Verordnung über die Anerkennung und Finanzierung von privaten Sonderschulen (Sonderschulverordnung) (sGS 213.951) | 6 | as enacted, then each consolidated version: 11 December 2007 to 1 October 2025 |
| `215-11-msv/` | Mittelschulverordnung (sGS 215.11) | 4 | as enacted, then each consolidated version: 27 March 2012 to 1 August 2026 |
| `215-110/` | Aufnahmereglement der Mittelschule (sGS 215.110) | 7 | as enacted, then each consolidated version: 15 February 2012 to 1 August 2026 |
| `215-111/` | Aufnahmereglement des Untergymnasiums (sGS 215.111) | 2 | as enacted, then each consolidated version: 1 October 1998 to 1 August 2019 |
| `216-10/` | Verordnung über Berichterstattung, Rechnung und Eigenkapital der Pädagogischen Hochschule St.Gallen (sGS 216.10) | 4 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `216-11/` | Personalverordnung der Pädagogischen Hochschule St.Gallen (sGS 216.11) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 September 2023 |
| `216-12/` | Verordnung über die Zulassung von Bewerberinnen und Bewerbern ohne eine gymnasiale Maturität zum Studium an der Pädagogischen Hochschule St.Gallen (sGS 216.12) | 3 | as enacted, then each consolidated version: 1 September 2009 to 1 August 2024 |
| `217-14/` | Verordnung über Berichterstattung, Rechnung und Eigenkapital der Universität St.Gallen (sGS 217.14) | 4 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `217-18/` | Reglement über die Beschränkung der Studierendenzahl auf der Master-Stufe der Universität St.Gallen (sGS 217.18) | 1 | as enacted, 1 August 2026 |
| `217-32/` | Personalreglement der Universität St.Gallen (HSG) (sGS 217.32) | 5 | oldest version available, then each consolidated version: 1 January 2019 to 1 January 2027 |
| `218-312/` | Personalreglement (sGS 218.312) | 1 | as enacted, 1 January 2022 |
| `218-313/` | Verordnung über Berichterstattung, Rechnung und Eigenkapital der Ost – Ostschweizer Fachhochschule (sGS 218.313) | 2 | as enacted, then each consolidated version: 31 December 2021 to 1 January 2026 |
| `219-11-vh/` | Verordnung über die privaten Hochschulen (sGS 219.11) | 1 | as enacted, 1 January 2024 |
| `230-311-mar/` | Reglement der EDK über die Anerkennung von gymnasialen Maturitätszeugnissen (Maturitätsanerkennungsreglement) (sGS 230.311) | 2 | oldest version available, then each consolidated version: 1 August 2007 to 1 August 2024 |
| `230-312/` | Reglement über die Anerkennung der Abschlüsse von Fachmittelschulen (sGS 230.312) | 2 | as enacted, then each consolidated version: 26 October 2007 to 1 August 2019 |
| `230-313/` | Reglement über die Ergänzungsprüfung für die Zulassung von Inhaberinnen und Inhabern eines eidgenössischen Berufsmaturitätszeugnisses oder eines gesamtschweizerisch anerkannten Fachmaturitätszeugnisses zu den universitären Hochschulen (sGS 230.313) | 3 | as enacted, then each consolidated version: 1 April 2004 to 1 January 2017 |
| `230-320/` | Reglement über die Anerkennung von Lehrdiplomen für den Unterricht auf der Primarstufe, der Sekundarstufe I und an Maturitätsschulen (sGS 230.320) | 1 | as enacted, 1 January 2020 |
| `231-11/` | Berufsbildungsverordnung (sGS 231.11) | 5 | oldest version available, then each consolidated version: 1 December 2012 to 1 May 2024 |
| `231-14-bmv/` | Berufsmaturitätsverordnung (sGS 231.14) | 3 | as enacted, then each consolidated version: 1 August 2015 to 1 August 2017 |
| `231-31-eva-bs/` | Ergänzende Verordnung über das Arbeitsverhältnis der Lehrpersonen an Berufs- und Weiterbildungszentren (sGS 231.31) | 5 | as enacted, then each consolidated version: 19 June 2012 to 1 August 2025 |
| `271-52/` | Verordnung über das Strahlen (sGS 271.52) | 2 | as enacted, then each consolidated version: 5 December 2000 to 1 October 2017 |
| `271-53/` | Verordnung über die Sicherung und Überlieferung von Naturkörpern (sGS 271.53) | 1 | as enacted, 1 June 2025 |
| `275-11-kfv/` | Kulturförderungsverordnung (sGS 275.11) | 2 | as enacted, then each consolidated version: 1 July 1996 to 1 August 2019 |
| `276-11-biblv/` | Bibliotheksverordnung (sGS 276.11) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 June 2019 |
| `277-11-vukg/` | Verordnung über Kantonsbeiträge an unbewegliche Kulturgüter (sGS 277.11) | 2 | as enacted, then each consolidated version: 1 July 2018 to 1 August 2019 |
| `277-12-kev/` | Kulturerbeverordnung (sGS 277.12) | 1 | as enacted, 1 August 2019 |
| `311-5-venae/` | Verordnung über die Entschädigung der Ärzte für amtliche Verrichtungen (sGS 311.5) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `311-12-vsp/` | Verordnung über den Schutz vor Passivrauchen (sGS 311.12) | 3 | as enacted, then each consolidated version: 1 July 2010 to 1 January 2025 |
| `312-0-vmb/` | Verordnung über die Ausübung der medizinischen Berufe (sGS 312.0) | 4 | as enacted, then each consolidated version: 1 September 2011 to 1 November 2025 |
| `312-1-vbg/` | Verordnung über die Ausübung von Berufen der Gesundheitspflege (sGS 312.1) | 5 | as enacted, then each consolidated version: 1 September 2011 to 1 November 2025 |
| `312-21/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (sGS 312.21) | 2 | as enacted, then each consolidated version: 1 July 2024 to 1 January 2026 |
| `312-32/` | Verordnung zum Register über die Gesundheitsfachpersonen NAREG (sGS 312.32) | 3 | as enacted, then each consolidated version: 1 January 2017 to 1 February 2022 |
| `312-311/` | Reglement der Schweizerischen Konferenz der kantonalen Gesundheitsdirektorinnen und -direktoren (GDK) über die Gebühren für die interkantonale Prüfung der Osteopathinnen und Osteopathen (sGS 312.311) | 1 | one version (the oldest available), 10 April 2014 |
| `313-1-vepg/` | Vollzugsverordnung zur eidgenössischen Gesetzgebung über übertragbare Krankheiten (sGS 313.1) | 1 | as enacted, 6 December 2005 |
| `313-2/` | Vollzugsverordnung zur eidgenössischen Covid-19-Verordnung internationaler Personenverkehr (sGS 313.2) | 22 | as enacted, then each consolidated version: 19 March 2020 to 17 February 2022 |
| `313-5-vss/` | Vollzugsverordnung zur eidgenössischen Verordnung über den Strahlenschutz (sGS 313.5) | 1 | as enacted, 15 January 1996 |
| `313-51-ev-nissg/` | Einführungsverordnung zur Bundesgesetzgebung über den Schutz vor Gefährdungen durch nichtionisierende Strahlung und Schall (sGS 313.51) | 1 | as enacted, 1 April 2021 |
| `313-75/` | Naturbäderverordnung (sGS 313.75) | 2 | as enacted, then each consolidated version: 21 June 2011 to 1 April 2021 |
| `314-3/` | Heilmittelverordnung (sGS 314.3) | 7 | as enacted, then each consolidated version: 24 January 2012 to 1 January 2025 |
| `314-5-vbetmg/` | Vollzugsverordnung zur Bundesgesetzgebung über die Betäubungsmittel (sGS 314.5) | 1 | as enacted, 15 January 1996 |
| `314-52/` | Verordnung über die Meldepflicht bei Anbau von Hanf (sGS 314.52) | 1 | as enacted, 21 June 2011 |
| `315-11-vlk/` | Verordnung über die Lebensmittelkontrolle (sGS 315.11) | 2 | as enacted, then each consolidated version: 21 June 2011 to 1 April 2021 |
| `321-12-patv/` | Verordnung über die Rechtsstellung der Patientinnen und Patienten (sGS 321.12) | 2 | as enacted, then each consolidated version: 1 June 2017 to 1 January 2025 |
| `325-11-veg/` | Verordnung über den Betrieb privater Einrichtungen der Gesundheitspflege (sGS 325.11) | 1 | one version (the oldest available), 1 January 2013 |
| `325-51/` | Vollzugsverordnung zur Bundesgesetzgebung über die Schwangerschaftsberatungsstellen (sGS 325.51) | 1 | as enacted, 18 November 2003 |
| `331-21/` | Verordnung über die Pflegefinanzierung (sGS 331.21) | 13 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2027 |
| `331-111/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über die Krankenversicherung (sGS 331.111) | 19 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2028 |
| `331-112/` | Verordnung über die Einschränkung der Kostenübernahme des Kantons bei bestimmten elektiven Eingriffen (sGS 331.112) | 2 | as enacted, then each consolidated version: 1 April 2022 to 1 January 2027 |
| `331-539/` | Verordnung über die Kostenübernahme bei ausserkantonalem Spitalaufenthalt (sGS 331.539) | 1 | as enacted, 17 February 1997 |
| `351-52/` | Verordnung über die nach Ergänzungsleistungsgesetz anrechenbare Tagespauschale (sGS 351.52) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2027 |
| `351-53-vkb/` | Verordnung über die Vergütung von Krankheits- und Behinderungskosten bei den Ergänzungsleistungen (sGS 351.53) | 6 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2026 |
| `361-11/` | Verordnung über Arbeitslosenversicherung und Arbeitsvermittlung (sGS 361.11) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2023 |
| `371-11/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über die Familienzulagen (sGS 371.11) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `372-11/` | Vollzugsverordnung zum Gesetz über Elternschaftsbeiträge (sGS 372.11) | 2 | as enacted, then each consolidated version: 7 March 1995 to 1 May 2018 |
| `381-11-vge/` | Verordnung über gemischte Einrichtungen (sGS 381.11) | 1 | as enacted, 1 January 2013 |
| `381-12/` | Asylverordnung (sGS 381.12) | 4 | as enacted, then each consolidated version: 11 January 2011 to 1 June 2020 |
| `381-18/` | Verordnung über private Betagten- und Pflegeheime (sGS 381.18) | 3 | as enacted, then each consolidated version: 1 April 2004 to 1 January 2025 |
| `381-19-pqv/` | Verordnung über die qualitativen Mindestanforderungen an Pflege und Betreuung in stationären Einrichtungen für Betagte (sGS 381.19) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2025 |
| `381-21/` | Verordnung über die anrechenbaren Kosten bei Unterbringung Minderjähriger (sGS 381.21) | 1 | as enacted, 1 January 2020 |
| `381-41-behv/` | Verordnung über die soziale Sicherung und Integration von Menschen mit Behinderung (sGS 381.41) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `387-21/` | Verordnung zur Interkantonalen Vereinbarung für soziale Einrichtungen IVSE (sGS 387.21) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `411-5/` | Verordnung zur Bundesgesetzgebung über die Wehrpflichtersatzabgabe (sGS 411.5) | 2 | as enacted, then each consolidated version: 8 April 2008 to 1 March 2014 |
| `411-15/` | Verordnung über die Sektionschefs (sGS 411.15) | 1 | as enacted, 30 October 2007 |
| `413-11/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über den Zivilschutz (sGS 413.11) | 6 | as enacted, then each consolidated version: 6 March 2012 to 1 January 2023 |
| `431-11/` | Verordnung zum Gesetz über den Vollzug der wirtschaftlichen Landesversorgung (sGS 431.11) | 2 | as enacted, then each consolidated version: 1 January 2011 to 1 October 2021 |
| `451-11-pv/` | Polizeiverordnung (sGS 451.11) | 7 | as enacted, then each consolidated version: 13 December 2011 to 1 August 2021 |
| `451-12/` | Verordnung über die polizeilichen Datenverarbeitungssysteme (sGS 451.12) | 2 | as enacted, then each consolidated version: 1 July 2006 to 1 January 2025 |
| `451-13/` | Privatdetektivverordnung (sGS 451.13) | 1 | as enacted, 30 October 2007 |
| `451-14/` | Verordnung über die Ausübung von Bewachungs-, Ordnungs- und Sicherheitsaufgaben (sGS 451.14) | 1 | as enacted, 1 January 2005 |
| `451-22/` | Vollzugsverordnung zur interkantonalen Vereinbarung über die polizeiliche Zusammenarbeit (sGS 451.22) | 1 | as enacted, 30 October 2007 |
| `452-4/` | Vollzugsverordnung zur eidgenössischen Sprengstoffgesetzgebung (sGS 452.4) | 1 | as enacted, 30 October 2007 |
| `452-15/` | Verordnung zur eidgenössischen Waffengesetzgebung (sGS 452.15) | 2 | as enacted, then each consolidated version: 13 June 2000 to 1 August 2024 |
| `453-7/` | Verordnung über die Gebühren zur Bundesgesetzgebung über die Ausländerinnen und Ausländer (sGS 453.7) | 2 | as enacted, then each consolidated version: 16 August 2011 to 1 March 2022 |
| `453-11/` | Verordnung über die kantonale Einwohnerdatenplattform (sGS 453.11) | 5 | as enacted, then each consolidated version: 1 November 2013 to 1 January 2020 |
| `453-31/` | Verordnung zur Bundesgesetzgebung über die Ausweise für Schweizer Staatsangehörige (sGS 453.31) | 3 | as enacted, then each consolidated version: 16 August 2011 to 1 November 2026 |
| `453-51/` | Verordnung zur Bundesgesetzgebung über die Ausländerinnen und Ausländer (sGS 453.51) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 October 2015 |
| `455-11/` | Verordnung zum Einführungsgesetz zur Bundesgesetzgebung über Geldspiele (sGS 455.11) | 3 | as enacted, then each consolidated version: 5 December 2000 to 1 November 2020 |
| `455-315/` | Verordnung über den Sportfonds (sGS 455.315) | 8 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2022 |
| `456-11-huv/` | Hundeverordnung (sGS 456.11) | 1 | as enacted, 1 January 2020 |
| `458-11/` | Vollzugsverordnung zum Gesetz über die Friedhöfe und die Bestattungen (sGS 458.11) | 2 | as enacted, then each consolidated version: 30 October 2007 to 1 October 2013 |
| `511-11/` | Vollzugsverordnung zur Gesetzgebung über die Arbeit in Industrie, Gewerbe und Handel (sGS 511.11) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2018 |
| `511-31/` | Vollzugsverordnung zur Bundesgesetzgebung über die Heimarbeit (sGS 511.31) | 1 | one version (the oldest available), 1 January 2013 |
| `512-11/` | Verordnung zur eidgenössischen Entsendegesetzgebung (sGS 512.11) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2020 |
| `514-1/` | Vollzugsverordnung zum Bundesgesetz über die Allgemeinverbindlicherklärung von Gesamtarbeitsverträgen (sGS 514.1) | 1 | one version (the oldest available), 1 January 2013 |
| `517-11/` | Verordnung zur Bundesgesetzgebung über Massnahmen zur Bekämpfung der Schwarzarbeit (sGS 517.11) | 1 | one version (the oldest available), 1 January 2013 |
| `551-1/` | Verordnung über das Messwesen (sGS 551.1) | 2 | as enacted, then each consolidated version: 1 July 2000 to 1 January 2022 |
| `552-11/` | Verordnung zum Gesetz über Ruhetag und Ladenöffnung (sGS 552.11) | 1 | as enacted, 1 October 2004 |
| `552-21/` | Verordnung zur Bundesgesetzgebung über das Gewerbe der Reisenden (sGS 552.21) | 1 | one version (the oldest available), 1 January 2013 |
| `553-12/` | Verordnung über Kurse und Prüfungen in Lebensmittelhygiene und Suchtprävention (sGS 553.12) | 1 | as enacted, 1 January 2021 |
| `556-11/` | Verordnung zur Bundesgesetzgebung über den Konsumkredit (sGS 556.11) | 1 | one version (the oldest available), 1 January 2013 |
| `559-11/` | Verordnung zur Bundesgesetzgebung über Risikoaktivitäten (sGS 559.11) | 1 | as enacted, 1 January 2014 |
| `561-71/` | Vollzugsverordnung zur Bundesgesetzgebung über die Bekanntgabe von Preisen (sGS 561.71) | 1 | one version (the oldest available), 1 January 2013 |
| `575-11/` | Tourismusverordnung (sGS 575.11) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `577-311/` | Geschäftsreglement «RhySearch» (sGS 577.311) | 2 | as enacted, then each consolidated version: 22 March 2016 to 22 May 2023 |
| `610-11-lav/` | Landwirtschaftsverordnung (sGS 610.11) | 6 | as enacted, then each consolidated version: 21 June 2011 to 1 August 2024 |
| `633-11/` | Vollzugsverordnung zum Meliorationsgesetz (sGS 633.11) | 2 | as enacted, then each consolidated version: 17 September 2002 to 1 October 2017 |
| `633-31/` | Reglement über Organisation und Geschäftsordnung der Melioration der Rheinebene (sGS 633.31) | 1 | as enacted, 1 September 1962 |
| `643-12-vtg/` | Verordnung über die Tiergesundheit (sGS 643.12) | 2 | as enacted, then each consolidated version: 21 June 2011 to 1 January 2020 |
| `643-71/` | Verordnung über den Tarif des Instituts für klinische Mikrobiologie und Immunologie für veterinär-medizinische Untersuchungen (sGS 643.71) | 1 | as enacted, 1 March 1993 |
| `643-72/` | Verordnung über Entschädigungen und Gebühren im Veterinärwesen (sGS 643.72) | 2 | as enacted, then each consolidated version: 21 June 2011 to 1 January 2023 |
| `645-1-vts/` | Vollzugsverordnung zur Bundesgesetzgebung über den Tierschutz (sGS 645.1) | 1 | as enacted, 21 June 2011 |
| `651-7/` | Reglement über die Bewirtschaftung der Staatswaldungen (sGS 651.7) | 1 | as enacted, 24 December 1955 |
| `651-11/` | Verordnung zum Einführungsgesetz zur eidgenössischen Waldgesetzgebung (sGS 651.11) | 7 | oldest version available, then each consolidated version: 10 November 2009 to 1 January 2024 |
| `671-1-nsv/` | Verordnung über den Schutz wildwachsender Pflanzen und freilebender Tiere (Naturschutzverordnung) (sGS 671.1) | 2 | as enacted, then each consolidated version: 30 October 2007 to 1 October 2017 |
| `671-71/` | Verordnung zum Gesetz über die Abgeltung ökologischer Leistungen (sGS 671.71) | 3 | as enacted, then each consolidated version: 18 March 2008 to 1 January 2016 |
| `672-11/` | Verordnung zum Einführungsgesetz zur eidgenössischen Umweltschutzgesetzgebung (sGS 672.11) | 8 | as enacted, then each consolidated version: 1 January 2012 to 1 September 2025 |
| `672-51/` | Verordnung zum Einführungsgesetz zur eidgenössischen Chemikaliengesetzgebung (sGS 672.51) | 2 | as enacted, then each consolidated version: 21 June 2011 to 1 July 2017 |
| `710-51-vov/` | Verordnung über den öffentlichen Verkehr (sGS 710.51) | 5 | as enacted, then each consolidated version: 1 January 2016 to 1 January 2026 |
| `711-1/` | Einführungsverordnung zum eidgenössischen Strassenverkehrsgesetz (sGS 711.1) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 December 2025 |
| `711-3/` | Verordnung über den Verkehr mit Raupenfahrzeugen (sGS 711.3) | 1 | as enacted, 1 September 1977 |
| `711-73-svav/` | Verordnung über die Strassenverkehrsabgaben (sGS 711.73) | 3 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2026 |
| `712-11/` | Reglement über Bau und Betrieb der nicht eidgenössisch konzessionierten Seilbahnen und Skilifte (Reglement IKSS) (sGS 712.11) | 2 | as enacted, then each consolidated version: 2 November 2006 to 2 June 2022 |
| `714-11/` | Schifffahrtsverordnung (sGS 714.11) | 3 | as enacted, then each consolidated version: 30 October 2007 to 1 April 2025 |
| `714-21/` | Vollzugsverordnung zum Gesetz über die Wasserfahrzeugsteuer (sGS 714.21) | 1 | as enacted, 30 October 2007 |
| `715-1/` | Vollzugsverordnung zu den eidgenössischen Vorschriften über die Luftfahrt (sGS 715.1) | 1 | as enacted, 30 October 2007 |
| `716-1/` | Verordnung zum eidgenössischen Rohrleitungsgesetz (sGS 716.1) | 3 | as enacted, then each consolidated version: 30 October 2007 to 1 October 2021 |
| `731-11-pbv/` | Verordnung zum Planungs- und Baugesetz (sGS 731.11) | 8 | as enacted, then each consolidated version: 30 October 2007 to 1 March 2025 |
| `731-12/` | Verordnung zum Bundesgesetz über Zweitwohnungen (sGS 731.12) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 June 2020 |
| `732-11-strv/` | Strassenverordnung (sGS 732.11) | 4 | as enacted, then each consolidated version: 30 October 2007 to 1 January 2026 |
| `732-12-kpv/` | Verordnung über den Klosterplatz in St.Gallen (sGS 732.12) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 October 2021 |
| `733-1-immov/` | Immobilienverordnung (sGS 733.1) | 2 | as enacted, then each consolidated version: 1 February 2016 to 1 October 2021 |
| `734-11-wbv/` | Wasserbauverordnung (sGS 734.11) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 October 2021 |
| `734-211/` | Verordnung über die Wasserwehr am Alpenrhein und Linthkanal (sGS 734.211) | 2 | as enacted, then each consolidated version: 1 January 1994 to 1 January 2022 |
| `735-5/` | Verordnung über die Zuständigkeit zur Beurteilung von Schadenersatzansprüchen nach Art. 15 des eidgenössischen Enteignungsgesetzes (sGS 735.5) | 1 | as enacted, 2 November 2005 |
| `737-11-vgwe/` | Verordnung zum Gesetz über Wohnbau- und Eigentumsförderung (sGS 737.11) | 2 | as enacted, then each consolidated version: 1 March 1993 to 1 October 2021 |
| `737-51/` | Vollzugsverordnung zum Grossratsbeschluss über Massnahmen zur Förderung des Wohnungsbaues (sGS 737.51) | 2 | as enacted, then each consolidated version: 30 January 1973 to 1 October 2021 |
| `738-3/` | Vollzugsverordnung zur Bundesgesetzgebung über Investitionshilfe für Berggebiete (sGS 738.3) | 2 | as enacted, then each consolidated version: 1 July 1998 to 1 October 2017 |
| `741-11-env/` | Energieverordnung (sGS 741.11) | 4 | oldest version available, then each consolidated version: 1 November 2012 to 1 July 2021 |
| `741-12-enfov/` | Verordnung über Förderungsbeiträge nach dem Energiegesetz (sGS 741.12) | 3 | as enacted, then each consolidated version: 1 November 2012 to 1 July 2017 |
| `751-11/` | Vollzugsverordnung zum Gesetz über die Gewässernutzung (sGS 751.11) | 3 | as enacted, then each consolidated version: 30 October 2007 to 1 October 2021 |
| `751-12/` | Verordnung über Nutzungsentschädigungen und Gebühren für Bewilligungen nach dem Gesetz über die Gewässernutzung (sGS 751.12) | 3 | as enacted, then each consolidated version: 1 January 2002 to 1 September 2023 |
| `751-13/` | Verordnung über den Materialbezug aus öffentlichen Gewässern (sGS 751.13) | 3 | as enacted, then each consolidated version: 15 January 1996 to 1 October 2021 |
| `752-21-gschvv/` | Verordnung zum Vollzugsgesetz zur eidgenössischen Gewässerschutzgesetzgebung (sGS 752.21) | 4 | oldest version available, then each consolidated version: 21 June 2011 to 1 October 2021 |
| `760-11/` | Geoinformationsverordnung (sGS 760.11) | 1 | as enacted, 1 September 2019 |
| `760-12/` | Vermessungsverordnung (sGS 760.12) | 3 | as enacted, then each consolidated version: 1 June 2019 to 1 June 2025 |
| `811-11-stv/` | Steuerverordnung (sGS 811.11) | 10 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2024 |
| `811-12/` | Verordnung über den Ausgleich der Folgen der kalten Progression (sGS 811.12) | 4 | as enacted, then each consolidated version: 1 January 2024 to 1 January 2027 |
| `813-11/` | Vollzugsverordnung zum Finanzausgleichsgesetz (sGS 813.11) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `813-52/` | Reglement über den Finanzausgleich (sGS 813.52) | 1 | as enacted, 24 June 2013 |
| `814-11-vgs/` | Verordnung über die Durchführung der Grundstückschätzung (sGS 814.11) | 4 | as enacted, then each consolidated version: 1 January 2001 to 1 January 2027 |
| `815-1/` | Verordnung zum Bundesgesetz über die direkte Bundessteuer (sGS 815.1) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2016 |
| `815-5/` | Verordnung zum Bundesgesetz über die Verrechnungssteuer (sGS 815.5) | 2 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2025 |
| `815-6/` | Verordnung über die pauschale Steueranrechnung (sGS 815.6) | 1 | as enacted, 1 January 1999 |
| `816-11/` | Verordnung über Veranlagung und Bezug der Kursaalabgabe (sGS 816.11) | 1 | as enacted, 1 December 2002 |
| `821-1-vgv/` | Verordnung über Kosten und Entschädigungen im Verwaltungsverfahren (Verwaltungsgebührenverordnung) (sGS 821.1) | 2 | as enacted, then each consolidated version: 14 May 1991 to 1 January 2020 |
| `831-1-fhv/` | Finanzhaushaltsverordnung (sGS 831.1) | 8 | as enacted, then each consolidated version: 30 October 2007 to 1 January 2026 |
| `841-11-vob/` | Verordnung über das öffentliche Beschaffungswesen (sGS 841.11) | 3 | as enacted, then each consolidated version: 23 March 2010 to 1 June 2023 |
| `853-11-jv/` | Jagdverordnung (sGS 853.11) | 8 | as enacted, then each consolidated version: 30 October 2007 to 1 April 2024 |
| `853-15-vjp/` | Verordnung über die Jagdprüfung (sGS 853.15) | 3 | as enacted, then each consolidated version: 30 October 2007 to 1 March 2022 |
| `853-111/` | Verordnung über die Jagdvorschriften (sGS 853.111) | 3 | as enacted, then each consolidated version: 1 April 2016 to 1 June 2024 |
| `854-11-fv/` | Fischereiverordnung (sGS 854.11) | 3 | as enacted, then each consolidated version: 20 December 2011 to 1 April 2026 |
| `854-312/` | Verordnung über die Fischerei im Bodensee-Obersee (sGS 854.312) | 2 | as enacted, then each consolidated version: 21 December 2010 to 1 January 2018 |
| `871-3-vgte/` | Verordnung über Gebühren, Tarife und Entschädigungen zum Feuerschutz (sGS 871.3) | 1 | as enacted, 1 January 2021 |
| `871-5/` | Vollzugsverordnung zum eidgenössischen Elektrizitätsgesetz (sGS 871.5) | 1 | as enacted, 27 March 2001 |
| `871-11-fsv/` | Feuerschutzverordnung (sGS 871.11) | 5 | as enacted, then each consolidated version: 21 December 2010 to 1 January 2021 |
| `873-11/` | Verordnung zum Gesetz über die Gebäudeversicherung (sGS 873.11) | 7 | as enacted, then each consolidated version: 23 November 2010 to 1 January 2023 |
| `873-12/` | Verordnung über Beiträge zur Verhütung von Elementarschäden (sGS 873.12) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2021 |
| `873-14/` | Geschäftsreglement der Gebäudeversicherung St.Gallen (sGS 873.14) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2024 |
| `911-11/` | Einführungsverordnung zum Schweizerischen Zivilgesetzbuch (sGS 911.11) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2022 |
| `911-21/` | Verordnung über die Amtsnotariate (sGS 911.21) | 1 | as enacted, 2 July 2002 |
| `911-511/` | Vollzugsverordnung zum Gesetz über Inkassohilfe und Vorschüsse für Unterhaltsbeiträge (sGS 911.511) | 2 | as enacted, then each consolidated version: 22 May 2001 to 1 January 2022 |
| `912-1-zstv/` | Zivilstandsverordnung (sGS 912.1) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2020 |
| `912-3-pkv/` | Verordnung über die Aufnahme von Pflege- und Tagespflegekindern (sGS 912.3) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `912-4-kjv/` | Verordnung über Kinder- und Jugendheime (sGS 912.4) | 3 | oldest version available, then each consolidated version: 1 January 2013 to 1 January 2020 |
| `912-51/` | Verordnung über die Entschädigung und den Spesenersatz bei Beistandschaften (sGS 912.51) | 1 | as enacted, 1 January 2013 |
| `914-11/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (sGS 914.11) | 3 | as enacted, then each consolidated version: 20 December 2005 to 1 July 2022 |
| `914-13-vgb/` | Verordnung über das Grundbuch (sGS 914.13) | 5 | as enacted, then each consolidated version: 1 March 2014 to 1 April 2024 |
| `914-31-gbbv/` | Grundbuchbereinigungsverordnung (sGS 914.31) | 3 | as enacted, then each consolidated version: 30 October 2007 to 1 June 2020 |
| `914-41-vsaa/` | Verordnung über die selbständigen Anteilrechte und das Alpbuch (sGS 914.41) | 4 | as enacted, then each consolidated version: 30 October 2007 to 1 January 2023 |
| `914-45/` | Verordnung über die Prüfung und den Fähigkeitsausweis der Grundbuchverwalterinnen und Grundbuchverwalter (sGS 914.45) | 4 | as enacted, then each consolidated version: 23 November 2010 to 1 July 2024 |
| `941-13/` | Verordnung über die Entschädigung der Richterinnen und Richter ohne feste Anstellung sowie der Mitglieder der Schlichtungsbehörden (Entschädigungsverordnung) (sGS 941.13) | 3 | as enacted, then each consolidated version: 1 June 2009 to 1 January 2024 |
| `941-22/` | Reglement über die Organisation und den Geschäftsgang des Verwaltungsgerichtes (sGS 941.22) | 2 | as enacted, then each consolidated version: 27 April 1988 to 1 June 2017 |
| `941-30/` | Reglement der Konferenz der Gerichte (sGS 941.30) | 1 | as enacted, 1 June 2017 |
| `941-112/` | Verordnung über die Schlichtungsbehörden (sGS 941.112) | 1 | as enacted, 1 June 2009 |
| `941-113/` | Verordnung über die Organisation der Verwaltungsrekurskommission (sGS 941.113) | 5 | oldest version available, then each consolidated version: 1 January 2013 to 1 June 2022 |
| `941-114/` | Reglement über Organisation und Geschäftsgang des Versicherungsgerichtes (sGS 941.114) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 June 2026 |
| `941-223/` | Reglement über den Geschäftsgang der Verwaltungsrekurskommission (sGS 941.223) | 3 | as enacted, then each consolidated version: 2 December 2010 to 1 June 2022 |
| `951-11-rekv/` | Verordnung über die Bearbeitung von Rekursverfahren vor den Departementen (sGS 951.11) | 1 | one version (the oldest available), 1 January 2019 |
| `951-12/` | Verordnung über den elektronischen Verkehr in Verfahren vor dem Migrationsamt (sGS 951.12) | 1 | as enacted, 1 October 2023 |
| `962-11-stpv/` | Strafprozessverordnung (sGS 962.11) | 10 | oldest version available, then each consolidated version: 1 January 2013 to 1 May 2026 |
| `962-12/` | Verordnung über die elektronische Überwachung (sGS 962.12) | 1 | as enacted, 1 May 2026 |
| `962-13/` | Verordnung über das Zwangsmassnahmengericht (sGS 962.13) | 1 | as enacted, 1 January 2011 |
| `962-14/` | Verordnung über die Gefängnisse und Vollzugsanstalten (sGS 962.14) | 4 | oldest version available, then each consolidated version: 1 January 2013 to 1 August 2026 |
| `962-17/` | Verordnung über die Bewährungshilfe (sGS 962.17) | 4 | as enacted, then each consolidated version: 30 October 2007 to 1 May 2026 |
| `963-74/` | Reglement über das Register der Notarinnen und Notare (sGS 963.74) | 1 | as enacted, 1 January 2011 |

## Source

The sGS (systematic collection) of the canton, published by the canton at <https://www.gesetzessammlung.sg.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (nGS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (nGS), with an e-mail address that cannot exist (`<act key>@www.gesetzessammlung.sg.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
