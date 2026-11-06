# Kloten (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Kloten, Zurich, Switzerland, which global-law reads at `switzerland/zurich/kloten/acts/`.

The municipal law of the city of Kloten (Stadt Kloten, canton of Zurich, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zurich is in [lexifina/switzerland-zurich-law](https://github.com/lexifina/switzerland-zurich-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

92 acts with 143 versions so far: the Gemeindeordnung (the city's charter) first, then the city's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1-go/` | Gemeindeordnung (SRS 1.1-1) | 4 | oldest version available, then each consolidated version: 1 January 2022 to 1 July 2026 |
| `1-2-1/` | Publikationsreglement (SRS 1.2-1) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 November 2025 |
| `1-2-2/` | Datenschutzreglement (SRS 1.2-2) | 2 | as enacted, then each consolidated version: 1 July 1996 to 1 June 2022 |
| `1-2-3/` | Weisung zum Umgang mit Bildern (SRS 1.2-3) | 1 | as enacted, 27 October 2021 |
| `1-5-1/` | Geschäftsreglement Gemeinderat (SRS 1.5-1) | 3 | as enacted, then each consolidated version: 1 January 2022 to 1 May 2025 |
| `1-6-1/` | Organisationsreglement des Stadtrates (SRS 1.6-1) | 2 | as enacted, then each consolidated version: 1 July 2022 to 1 July 2026 |
| `1-6-2-entschvo/` | Verordnung über die Entschädigung der Behörden, Kommissionen und Funktionärinnen und Funktionäre (SRS 1.6-2) | 2 | as enacted, then each consolidated version: 30 June 2012 to 1 July 2022 |
| `1-6-2-1-vbentschvo/` | Vollzugsbestimmungen zur Verordnung über die Entschädigung der Behörden, Kommissionen und Funktionärinnen und Funktionäre (SRS 1.6-2.1) | 4 | oldest version available, then each consolidated version: 22 November 2016 to 1 July 2026 |
| `1-6-3/` | Organisationsreglement Sozialkommission (SRS 1.6-3) | 1 | as enacted, 1 January 2022 |
| `1-6-4/` | Organisationsreglement der Baukommission (SRS 1.6-4) | 1 | as enacted, 1 January 2022 |
| `1-6-5/` | Organisationsreglement Grundsteuerkommission (SRS 1.6-5) | 1 | as enacted, 1 January 2022 |
| `1-6-6/` | Organisationsreglement Bürgerrechtskommission (SRS 1.6-6) | 1 | as enacted, 1 January 2022 |
| `1-6-7/` | Organisationsreglement der Energiekommission (SRS 1.6-7) | 2 | as enacted, then each consolidated version: 16 February 2021 to 1 November 2026 |
| `1-6-8-vregl/` | Verwaltungsreglement (SRS 1.6-8) | 1 | as enacted, 1 January 2022 |
| `1-6-9/` | Organisationsreglement Kulturkommission (SRS 1.6-9) | 1 | as enacted, 14 November 2022 |
| `1-6-10/` | Organisationsreglement Alterskommission (SRS 1.6-10) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 April 2025 |
| `1-7-1-mavo/` | Verordnung über das Anstellungsverhältnis der Mitarbeiterinnen und Mitarbeiter (SRS 1.7-1) | 2 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2023 |
| `1-7-1-1-vbmavo/` | Vollzugsbestimmungen zur Verordnung über das Anstellungsverhältnis der Mitarbeiterinnen und Mitarbeiter (SRS 1.7-1.1) | 3 | oldest version available, then each consolidated version: 7 July 2020 to 1 October 2025 |
| `1-7-2/` | Spesenreglement (SRS 1.7-2) | 1 | as enacted, 1 January 2018 |
| `1-7-2-1/` | Zusatz-Spesenreglement der Stadt Kloten für leitendes Personal (SRS 1.7-2.1) | 1 | as enacted, 1 January 2018 |
| `1-7-3-pikettreglement/` | Reglement über Pikettdienst, besondere Dienste und Zulagen (SRS 1.7-3) | 1 | as enacted, 1 October 2025 |
| `2-1-1/` | Vertrag über die Zusammenarbeit unter Gemeinden im Kindes- und Erwachsenenschutzkreis Bülach Süd (SRS 2.1-1) | 1 | as enacted, 24 October 2012 |
| `2-1-2/` | Vertrag über die Zusammenarbeit der Gemeinden im Zivilstandskreis Kloten (SRS 2.1-2) | 1 | as enacted, 5 March 2003 |
| `4-1-2/` | Reglement über die Subventionsberechtigung in der Familien- und Schulergänzenden Betreuung (SRS 4.1-2) | 1 | as enacted, 1 April 2020 |
| `4-2-2/` | Sicherheitsüberwachung mittels Videosystem der Schule Kloten (SRS 4.2-2) | 1 | as enacted, 23 September 2011 |
| `4-2-3/` | Elternratsreglement der Schule Kloten (SRS 4.2-3) | 2 | as enacted, then each consolidated version: 16 May 2013 to 1 August 2025 |
| `4-2-4/` | Reglement für Exkursionen, Schulreisen, Abschlussreisen und Klassenlager der Schule Kloten (SRS 4.2-4) | 2 | as enacted, then each consolidated version: 24 January 2019 to 1 October 2026 |
| `4-2-5/` | Konzept für die Prüfungsvorbereitungskurse zur Aufnahmeprüfung Gymnasium und Berufsmaturität (SRS 4.2-5) | 1 | as enacted, 1 August 2020 |
| `4-2-6/` | Partnerschaftsvertrag zwischen der Stadt Kloten und der Partnergemeinde Opfikon über die Beteiligung an der Berufswahlschule Kloten (SRS 4.2-6) | 1 | as enacted, 29 November 2018 |
| `4-2-7/` | Schulpsychologischer Dienst Kloten-Opfikon: Kooperationsvereinbarung und Organisationsbeschrieb (SRS 4.2-7) | 1 | as enacted, 1 August 2017 |
| `4-2-8/` | Reglement über die Schulbus-Transporte (SRS 4.2-8) | 1 | as enacted, 7 May 2015 |
| `4-2-9/` | Verordnung über die Jugendzahnpflege (SRS 4.2-9) | 1 | as enacted, 20 December 2005 |
| `4-2-10/` | Organisationsreglement Schulpflege Kloten (Teil des Organisationsstatuts) (SRS 4.2-10) | 2 | as enacted, then each consolidated version: 1 July 2022 to 1 August 2025 |
| `4-2-11/` | Organisationsreglement Bildung und Kind (Teil des Organisationsstatuts) (SRS 4.2-11) | 2 | as enacted, then each consolidated version: 1 July 2022 to 1 August 2025 |
| `4-3-1/` | Allgemeine Geschäftsbedingungen der Musikschule Kloten Bassersdorf Lufingen (SRS 4.3-1) | 1 | as enacted, 10 July 2014 |
| `4-3-2/` | Gebührenreglement der Musikschule (SRS 4.3-2) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 August 2023 |
| `4-7-1/` | Reglement zur Vergabe des Kultur- und des Kulturförderpreises (SRS 4.7-1) | 1 | as enacted, 1 June 2025 |
| `5-1-1-polv/` | Polizeiverordnung (SRS 5.1-1) | 3 | as enacted, then each consolidated version: 8 June 2004 to 1 October 2025 |
| `5-1-2/` | Kommunalpolizeiliche Zusammenarbeit der Gemeinden Bassersdorf, Dietlikon, Kloten, Opfikon und Wallisellen (SRS 5.1-2) | 1 | as enacted, 1 January 2004 |
| `5-1-2-1/` | Kommunalpolizeiliche Zusammenarbeit der Gemeinden Bassersdorf - Dietlikon - Kloten - Opfikon - Wallisellen: Ausführungsbestimmungen (SRS 5.1-2.1) | 1 | as enacted, 1 January 2004 |
| `5-1-2-2/` | Dienstanweisung betreffend regionale Zusammenarbeit (SRS 5.1-2.2) | 1 | as enacted, 1 January 2004 |
| `5-3-1/` | Vereinbarung über die Bildung einer gemeinsamen Zivilschutzorganisation (SRS 5.3-1) | 1 | as enacted, 1 January 2015 |
| `5-3-1-1/` | Geschäftsreglement der Zivilschutzorganisation Hardwald (ZSO Hardwald) (SRS 5.3-1.1) | 1 | as enacted, 13 January 2016 |
| `6-4-1/` | Verordnung über die Gemeindegebühren der Stadt Kloten (SRS 6.4-1) | 1 | as enacted, 1 July 2021 |
| `6-4-1-1/` | Allgemeines Gebührenreglement (SRS 6.4-1.1) | 1 | as enacted, 1 February 2022 |
| `6-4-1-2/` | Gebührenreglement über das Bürgerrechtswesen (SRS 6.4-1.2) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 July 2023 |
| `6-4-1-4/` | Gebührenreglement Schulgelder Volksschule (SRS 6.4-1.4) | 1 | as enacted, 1 February 2022 |
| `6-4-1-5/` | Gebührenreglement Berufswahlschule (SRS 6.4-1.5) | 1 | as enacted, 1 February 2022 |
| `6-4-1-6/` | Gebührenreglement Förder- und Freizeitangebote für die Schule (SRS 6.4-1.6) | 1 | as enacted, 1 February 2022 |
| `6-4-1-7/` | Gebührenreglement Vermietung von Bildungsräumen (SRS 6.4-1.7) | 1 | as enacted, 1 February 2022 |
| `6-4-1-8/` | Gebührenreglement Freizeit und Sport (SRS 6.4-1.8) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 January 2024 |
| `6-4-1-9/` | Gebührenreglement für Sicherheit, Verkehr, Polizei und Stadtrichteramt (SRS 6.4-1.9) | 3 | as enacted, then each consolidated version: 1 February 2022 to 1 September 2025 |
| `6-4-1-10/` | Baugebührenreglement (SRS 6.4-1.10) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 February 2024 |
| `6-4-1-11/` | Gebührenreglement für Umwelt und Planung (SRS 6.4-1.11) | 1 | as enacted, 1 February 2022 |
| `6-4-1-12/` | Gebührenreglement über das Abfallwesen (SRS 6.4-1.12) | 5 | as enacted, then each consolidated version: 1 February 2022 to 1 January 2026 |
| `6-4-1-13/` | Gebührenreglement Tiefbau (SRS 6.4-1.13) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 January 2023 |
| `6-4-1-14/` | Gebührenreglement Sondergebrauch und Sondernutzung für den Stadtplatz (SRS 6.4-1.14) | 1 | as enacted, 1 February 2022 |
| `6-4-1-15/` | Gebührenreglement über das Friedhofs- und Bestattungswesen (SRS 6.4-1.15) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 March 2026 |
| `6-4-1-16/` | Gebührenreglement der Spitex (SRS 6.4-1.16) | 2 | as enacted, then each consolidated version: 1 February 2022 to 1 October 2022 |
| `6-4-1-17/` | Gebührenreglement des Pflegezentrums im Spitz (SRS 6.4-1.17) | 4 | as enacted, then each consolidated version: 1 February 2022 to 1 January 2026 |
| `6-4-1-18/` | Gebührenreglement Frühförderung und Krippe Looren (SRS 6.4-1.18) | 2 | as enacted, then each consolidated version: 1 August 2024 to 1 January 2025 |
| `6-4-1-19/` | Gebührenreglement Subventionen familienergänzende Betreuung (SRS 6.4-1.19) | 1 | as enacted, 1 August 2024 |
| `6-4-1-20/` | Gebührenreglement Schulhorte (SRS 6.4-1.20) | 3 | as enacted, then each consolidated version: 1 August 2024 to 1 August 2026 |
| `6-6-1/` | Vereinbarung zur 300 m-Schiessanlage Bettensee, Kloten (SRS 6.6-1) | 1 | as enacted, 1 January 2020 |
| `6-6-1-1/` | Anschlussvertrag über die Mitbenützung der 300 m-Schiessanlage Bettensee in Kloten durch die Gemeinden Bassersdorf und Dietlikon (SRS 6.6-1.1) | 1 | as enacted, 1 September 2013 |
| `6-6-1-2/` | Reglement über die Benützung der 300 m-Schiessanlage Bettensee, Kloten (SRS 6.6-1.2) | 1 | as enacted, 15 April 1989 |
| `7-1-1/` | Bau- und Zonenordnung (SRS 7.1-1) | 2 | oldest version available, then each consolidated version: 2 June 2021 to 13 October 2023 |
| `7-1-2/` | Verordnung zum kommunalen Mehrwertausgleichsfonds (SRS 7.1-2) | 1 | as enacted, 1 September 2022 |
| `7-1-3/` | Statuten des regionalen Planungsverbandes Zürcher Planungsgruppe Glattal (ZPG) (SRS 7.1-3) | 1 | as enacted, 1 January 2021 |
| `7-1-4/` | Reglement über die Ersatzabgabe für Fahrzeugabstellplätze (SRS 7.1-4) | 1 | as enacted, 10 February 1987 |
| `7-1-5/` | Parkplatzreglement (SRS 7.1-5) | 2 | as enacted, then each consolidated version: 1 October 2010 to 13 October 2023 |
| `7-1-6/` | Richtlinien über die Familien- und Schrebergartenareale (SRS 7.1-6) | 1 | as enacted, 1 October 2026 |
| `7-3-1/` | Kommunale Verordnung über den Natur- und Landschaftsschutz (SRS 7.3-1) | 1 | as enacted, 21 March 1995 |
| `7-4-1/` | Konzessionsvertrag für die Wasserversorgung (SRS 7.4-1) | 1 | as enacted, 19 January 1999 |
| `7-4-2/` | Konzessionsvertrag für die Energieversorgung (SRS 7.4-2) | 1 | as enacted, 1 October 2008 |
| `7-4-3/` | Abfallverordnung (SRS 7.4-3) | 1 | as enacted, 10 March 2021 |
| `7-4-4-sevo/` | Siedlungsentwässerungsverordnung (SRS 7.4-4) | 1 | as enacted, 9 February 2010 |
| `7-4-4-1/` | Verordnung über die Gebühren für Siedlungsentwässerungsanlagen (SRS 7.4-4.1) | 2 | as enacted, then each consolidated version: 5 November 2013 to 1 January 2025 |
| `7-4-5/` | Reglement zur Förderung von Photovoltaikanlagen (SRS 7.4-5) | 1 | as enacted, 1 January 2023 |
| `7-4-6-vogl/` | Verordnung über die gemeinnützigen Leistungen der Industriellen Betriebe Kloten AG und Abgaben (SRS 7.4-6) | 1 | as enacted, 1 October 2024 |
| `7-6-1/` | Verordnung über den Unterhalt der Waldwege (SRS 7.6-1) | 1 | as enacted, 5 March 1980 |
| `7-6-2/` | Verordnung über den Unterhalt der Feldwege und Drainagen (SRS 7.6-2) | 1 | as enacted, 6 August 1997 |
| `7-6-3-privatstrassenverordnung/` | Verordnung über den Unterhalt und die Benützung der privaten Strassen und Wege (SRS 7.6-3) | 1 | as enacted, 30 May 1968 |
| `7-6-4/` | Verordnung über die Häusernummerierung (SRS 7.6-4) | 1 | as enacted, 20 February 1990 |
| `7-7-1-parkverordnung/` | Verordnung über das unbeschränkte Parkieren in Blauen Zonen (SRS 7.7-1) | 2 | as enacted, then each consolidated version: 6 December 1994 to 1 January 2023 |
| `8-1-1/` | Statuten der Spital Bülach AG (SRS 8.1-1) | 1 | as enacted, 19 May 2016 |
| `8-2-1/` | Reglement über das Friedhofs- und Bestattungswesen (SRS 8.2-1) | 3 | as enacted, then each consolidated version: 1 May 2018 to 1 March 2026 |
| `8-2-1-1/` | Richtlinien für Grabmäler (SRS 8.2-1.1) | 1 | as enacted, 1 January 2021 |
| `8-2-2/` | Anschlussvertrag betreffend die Beisetzung von Verstorbenen muslimischen Glaubens auf dem Friedhof Witikon (SRS 8.2-2) | 1 | as enacted, 1 May 2019 |
| `8-7-1/` | Reglement über die Zusatzleistungen zur eidgenössischen Alters-, Hinterlassenen- und Invalidenversicherung (AHV/IV): Gemeindezuschüsse (SRS 8.7-1) | 2 | oldest version available, then each consolidated version: 27 June 2006 to 1 March 2025 |
| `8-7-2/` | Verordnung über den Betrieb des Pflegezentrums im Spitz (inkl. Pflegestation Kirchgasse und Pflegewohnung) (SRS 8.7-2) | 3 | as enacted, then each consolidated version: 1 September 2021 to 1 January 2026 |
| `8-7-3/` | Anstaltsvertrag interkommunale Anstalt KZU (SRS 8.7-3) | 1 | as enacted, 1 January 2011 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://kloten.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@kloten.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
