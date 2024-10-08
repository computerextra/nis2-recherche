# NIS 2 Richtlinie

> [!IMPORTANT]
> Autor: Johannes Kirchner\
> Firma: Computer Extra GmbH\
> E-Mail: [johannes.kirchner@computer-extra.de](mailto:johannes.kirchner@computer-extra.de)

> [!NOTE]
> Erstellt: 07.10.2024\
> Letztes Update: 08.10.2024

![NIS2 Beispielbild](/img/nis.png)

## Downloads / Links

- [Merkblatt NIS-2-Richtlinie (PDF) Quelle: G Data](https://www.gdata.de/fileadmin/web/de/documents/flyer/G_DATA_NIS2_Merkblatt.pdf)
- [Gesetzes Entwurf](https://www.bmi.bund.de/SharedDocs/gesetzgebungsverfahren/DE/Downloads/kabinettsfassung/CI1/nis2-regierungsentwurf.pdf?__blob=publicationFile&v=1)
- [Selbstprüfung BSI](https://betroffenheitspruefung-nis-2.bsi.de/)
- [Entscheidungsbaum der NIS-2-Betroffenenprüfung des BSI (PDF)](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/NIS-2/nis-2-betroffenheit-entscheidungsbaum.pdf?__blob=publicationFile&v=9)
- [NIS2: Ein Mindestniveau für die IT-Sicherheit in Europa (PDF)](/files/securepoint-nis2-whitepaper.pdf)
- [Richtlinie über Maßnahmen für ein hohes gemeinsames Cybersicherheitsniveau in der Union (PDF)](/files/securepoint-webinar-praesentation-nis2-richtlinie.pdf)
- [IT-Notfallmanagement (PDF)](/files/ADLON_Leitfaden_Notfallmanagement.pdf)

## Inhalt

- [NIS 2 Richtlinie](#nis-2-richtlinie)
  - [Downloads / Links](#downloads--links)
  - [Inhalt](#inhalt)
  - [Was ist das Eigentlich?](#was-ist-das-eigentlich)
    - [Was ist NIS-2?](#was-ist-nis-2)
    - [Wann tritt NIS-2 in Kraft?](#wann-tritt-nis-2-in-kraft)
    - [Wie fange ich mit der Umsetzung an?](#wie-fange-ich-mit-der-umsetzung-an)
      - [Weitere Maßnahmen](#weitere-maßnahmen)
    - [Was IT-Dienstleister und Fachhändler über NIS2 wissen sollten](#was-it-dienstleister-und-fachhändler-über-nis2-wissen-sollten)
    - [Was müssen von NIS-2 betroffene Unternehmen und Organisationen tun?](#was-müssen-von-nis-2-betroffene-unternehmen-und-organisationen-tun)
      - [Maßnahmen zum Risikomanagement für Cybersicherheit](#maßnahmen-zum-risikomanagement-für-cybersicherheit)
        - [Sicherheitsvorfall](#sicherheitsvorfall)
      - [Verantwortung der Geschäftsführung](#verantwortung-der-geschäftsführung)
      - [Meldepflicht von Sicherheitsvorfällen](#meldepflicht-von-sicherheitsvorfällen)
        - [Fristen für die Meldung](#fristen-für-die-meldung)
      - [Registrierung](#registrierung)
  - [Wer ist eigentlich betroffen?](#wer-ist-eigentlich-betroffen)
    - [Sektoren](#sektoren)
      - [Sektoren mit hoher Kritikalität](#sektoren-mit-hoher-kritikalität)
        - [Energie](#energie)
        - [Verkehr](#verkehr)
        - [Bankwesen](#bankwesen)
        - [Finanzmarktinfrastruktur](#finanzmarktinfrastruktur)
        - [Gesundheitswesen](#gesundheitswesen)
        - [Trinkwasser](#trinkwasser)
        - [Abwasser](#abwasser)
        - [Digitale Infrastruktur](#digitale-infrastruktur)
        - [Verwaltung von ITK-Diensten (B2B)](#verwaltung-von-itk-diensten-b2b)
        - [Öffentliche Verwaltung](#öffentliche-verwaltung)
        - [Weltraum](#weltraum)
      - [Sonstige kritische Sektoren](#sonstige-kritische-sektoren)
        - [Post- und Kurierdienste](#post--und-kurierdienste)
        - [Abfallbewirtschaftung](#abfallbewirtschaftung)
        - [Produktion, Herstellung und Handel mit chemischen Stoffen](#produktion-herstellung-und-handel-mit-chemischen-stoffen)
        - [Produktion, Herstellung und Vertrieb von Lebensmitteln](#produktion-herstellung-und-vertrieb-von-lebensmitteln)
        - [Verarbeitendes Gewerbe/Herstellung von Waren](#verarbeitendes-gewerbeherstellung-von-waren)
        - [Anbieter digitaler Dienste](#anbieter-digitaler-dienste)
        - [Forschung](#forschung)
    - [Sonderfälle](#sonderfälle)
  - [Was passiert, wenn Sie die NIS-2 Vorschriften nicht einhalten?](#was-passiert-wenn-sie-die-nis-2-vorschriften-nicht-einhalten)
  - [NACE Rev. 2](#nace-rev-2)
    - [Statistische Systematik der Wirtschaftszweige in der Europäischen Gemeinschaft](#statistische-systematik-der-wirtschaftszweige-in-der-europäischen-gemeinschaft)
    - [Hauptbetroffene Bereiche](#hauptbetroffene-bereiche)
      - [1. Landwirtschaft, Forstwirtschaft und Fischerei (Abschnitt A)](#1-landwirtschaft-forstwirtschaft-und-fischerei-abschnitt-a)
      - [2. Bergbau und Gewinnung von Steinen und Erden (Abschnitt B)](#2-bergbau-und-gewinnung-von-steinen-und-erden-abschnitt-b)
      - [3. Verarbeitendes Gewerbe (Abschnitt C)](#3-verarbeitendes-gewerbe-abschnitt-c)
      - [4. Energieversorgung (Abschnitt D) und Wasserversorgung (Abschnitt E)](#4-energieversorgung-abschnitt-d-und-wasserversorgung-abschnitt-e)
      - [5. Baugewerbe (Abschnitt F)](#5-baugewerbe-abschnitt-f)
      - [6. Handel; Instandhaltung und Reparatur von Kraftfahrzeugen (Abschnitt G)](#6-handel-instandhaltung-und-reparatur-von-kraftfahrzeugen-abschnitt-g)
      - [7. Verkehr und Lagerei (Abschnitt H)](#7-verkehr-und-lagerei-abschnitt-h)
      - [8. Gastgewerbe (Abschnitt I)](#8-gastgewerbe-abschnitt-i)
      - [9. Information und Kommunikation (Abschnitt J)](#9-information-und-kommunikation-abschnitt-j)
      - [10. Finanz- und Versicherungsdienstleistungen (Abschnitt K)](#10-finanz--und-versicherungsdienstleistungen-abschnitt-k)
      - [11. Grundstücks- und Wohnungswesen (Abschnitt L)](#11-grundstücks--und-wohnungswesen-abschnitt-l)
      - [12. Freiberufliche, wissenschaftliche und technische Dienstleistungen (Abschnitt M)](#12-freiberufliche-wissenschaftliche-und-technische-dienstleistungen-abschnitt-m)
      - [13. Sonstige wirtschaftliche Dienstleistungen (Abschnitt N)](#13-sonstige-wirtschaftliche-dienstleistungen-abschnitt-n)
      - [14. Öffentliche Verwaltung, Verteidigung; Sozialversicherung (Abschnitt O)](#14-öffentliche-verwaltung-verteidigung-sozialversicherung-abschnitt-o)
      - [15. Erziehung und Unterricht (Abschnitt P) sowie Gesundheits- und Sozialwesen (Abschnitt Q)](#15-erziehung-und-unterricht-abschnitt-p-sowie-gesundheits--und-sozialwesen-abschnitt-q)
    - [Struktur der NACE Rev. 2](#struktur-der-nace-rev-2)
  - [Ansätze](#ansätze)
    - [Risikobasierter Ansatz](#risikobasierter-ansatz)
      - [Welche Maßnahmen sind angemessen?](#welche-maßnahmen-sind-angemessen)
  - [Leitfaden Notfallmanagement](#leitfaden-notfallmanagement)
    - [Must-Haves für NIS2](#must-haves-für-nis2)
      - [Für den Ernstfall vorbereiten](#für-den-ernstfall-vorbereiten)
    - [Einstieg ins Notfallmanagement](#einstieg-ins-notfallmanagement)
    - [Perfekt für den Notfall gerüstet mit einem Notfallplan](#perfekt-für-den-notfall-gerüstet-mit-einem-notfallplan)
      - [Auszug eines IT-Notfallplans](#auszug-eines-it-notfallplans)
    - [Pragmatische Vorgehensweise](#pragmatische-vorgehensweise)
    - [Weitere Anforderungen durch NIS2](#weitere-anforderungen-durch-nis2)
    - [Prävention statt Krise](#prävention-statt-krise)
  - [Quellen](#quellen)

## Was ist das Eigentlich?

### Was ist NIS-2?

NIS-2 beinhaltet Sicherheitsmaßnahmen und Meldepflichten für Unternehmen in kritischen Sektoren.
Es gibt 18 Sektoren, die unter diese Regelung fallen.

### Wann tritt NIS-2 in Kraft?

Aktuell (Stand 07.10.2024) liegt das Gesetz nur als [Entwurf](https://www.bmi.bund.de/SharedDocs/gesetzgebungsverfahren/DE/Downloads/kabinettsfassung/CI1/nis2-regierungsentwurf.pdf?__blob=publicationFile&v=1) vor.
Es wird von der EU Verlangt, dass ein Gesetz bis zum 17.10.2024 umgesetzt wird.
Es wird aktuell vermuted, dass das Gesetz (NIS2UmsuCG) _nicht_ bis um 17.10.2024 umgesetzt wird.

### Wie fange ich mit der Umsetzung an?

<!-- TODO: Artikel -->

- Einführung eines Incident Managements: Monitoring, Bewertung, Reaktion und Behebung von Sicherheitsvorfällen
- Einführung eines Business Continuity Managements (BCM): Backup-Management, Widerherstellung, Krisenmanagement
- Einführung eines Risikomanagements: insbesondere rund um Cybersicherheit, Sicherheit der Informationssysteme und Sicherheit in der Lieferkette
- Ausarbeitung von Konzepten und Verfahren für den Einsatz von Kryptografie und Verschlüsselung
- Einrichtung einer Multi-Faktor-Authentifizierung oder kontinuierlicher Authentifizierung
- Umsetzung von Maßnahmen der "Cyberhygiene": z. B. regelmäßige Updates, Mitarbeiter-Schulungen zur Cybersicherheit

#### Weitere Maßnahmen

Zudem muss ein Meldesystem etabliert werden, denn: Bei erheblichen Sicherheitsvorfällen sind Unternehmen verpflichtet, innerhalb von 24 Stunden ab Kenntnis eine Frühwarnung an das BSI (Bundesamt für Sicherheit in der Informationstechnik) zu leisten. Innerhalb von 72 Stunden ist ein ausführlicher Bericht mit Bewertung einzureichen und nach einem Monat ein Abschlussbericht inklusive Maßnahmen.

### Was IT-Dienstleister und Fachhändler über NIS2 wissen sollten

NIS2 bei den Kunden rechtzeitig umzusetzen, ist eine Herausforderung – und eine Chance. Systemhäuser und Fachhändler gehen mit ihrer eigenen Expertise für die IT-Sicherheit bei der Beratung ihrer Kunden voran und sorgen für den notwendigen Schutz.

Unter bestimmten Voraussetzungen können IT-Dienstleister außerdem selbst in den Geltungsbereich der Richtlinie fallen. Welche Aspekte sind dafür von Bedeutung?

In einem [Whitepaper](<!-- TODO: Link to File -->) haben wir (Securepoint) die wichtigsten Informationen zu NIS2 zusammengestellt. Weitere Informationen vermittelt zudem eine Präsentation, die im Rahmen eines Webinars für IT-Dienstleister stattgefunden hat.

### Was müssen von NIS-2 betroffene Unternehmen und Organisationen tun?

#### Maßnahmen zum Risikomanagement für Cybersicherheit

(Art. 1 §30 im NIS2UmsuCG-Entwurf)

Laut NIS2 müssen folgende Cybersecurity Maßnahmen umgesetzt werden:
Wie viel genau **angemessen** ist, soll das Unternehmen nach einem [risikobasierten Ansatz](#risikobasierter-ansatz) selbst festlegen.

- **Policies:** Konzepte für Risikoanalyse und Sicherheit für Informationssysteme
- **Vorfallsbewältigung:** Erkennung, Analyse, Eindämmung und Reaktion auf Vorfälle
- **Business Continuity:** Backup-Management und Wiederherstellung, Krisenmanagement
- **Supply Chain:** Sicherheit in der Lieferkette[^1]
- **Einkauf:** Sicherheit bei Erwerb, Entwicklung und Wartung der IT-Systeme, einschließlich Management und Offenlegung von Schwachstellen
- **Wirksamkeit:** Bewertung der Wirksamkeit der Risikomanagementmaßnahmen
- **Cyberhygiene, Schulung:** Cyberhygiene (z.B. Updates) und Schulungen in Cyber Security
- **Kryptografie:** Einsatz von Kryptografie und gegebenenfalls Verschlüsselung
- **Personal, Zugriffe, Assets:** Personalsicherheit, Zugriffskontrolle und Asset Management
- **Authentifizierung:** Multi-Faktor-Authentifizierung oder kontinuierliche Authentifizierung
- **Kommunikation:** Sichere Sprach-, Video- und Text-Kommunikation, ggf. auch im Notfall

##### Sicherheitsvorfall

Ein Sicherheitsvorfall gilt als „erheblich“, wenn:

- er schwerwiegende Betriebsstörungen der Dienste oder finanzielle Verluste für die betreffende Einrichtung verursacht hat oder verursachen kann
- er andere natürliche oder juristische Personen durch erhebliche materielle oder immaterielle Schäden beeinträchtigt hat oder beeinträchtigen kann.

Die EU-Kommission wird zur Definition eines „erheblichen Sicherheitsvorfalls“ für bestimmte Unternehmen weitere Vorgaben machen. Dazu hat sie bereits einen [Entwurf](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/14241-Cybersicherheitsrisikomanagement-und-Berichtspflichten-fur-digitale-Infrastrukturen-Anbieter-und-IKT-Servicemanager_de) veröffentlicht.

[^1]: Immer häufiger finden Cyberangriffe über die Lieferkette statt. Die EU NIS2 Direktive schreibt daher vor, dass betroffene Einrichtungen die IT-Sicherheit bei ihren unmittelbaren Zulieferern oder Dienstleistern prüfen müssen: Gibt es spezifische Schwachstellen? Wie sieht deren Gesamtqualität der Produkte und IT-Sicherheitspraxis aus, einschließlich der Sicherheit ihrer Entwicklungsprozesse?

#### Verantwortung der Geschäftsführung

(Art. 1 § 38 im NIS2UmsuCG-Entwurf)

- muss die Maßnahmen umsetzen und die Umsetzung überwachen
- haftet für Verstöße nach den Regeln des jeweiligen Gesellschaftsrechts
- muss an Schulungen teilnehmen

#### Meldepflicht von Sicherheitsvorfällen

(Art. 1 § 32 im NIS2UmsuCG-Entwurf)

[Erhebliche Sicherheitsvorfälle](#sicherheitsvorfall) müssen der nationalen Behörde und gegebenenfalls dem Empfänger der eigenen Dienste gemeldet werden.

##### Fristen für die Meldung

- **Frühwarnung innerhalb von 24 h ab Kenntnis:**\
  Verdacht, ob der Vorfall auf rechtswidriger oder böswilliger Handlung beruht und ob grenzüberschreitend.
- **Ausführlicher Bericht innerhalb von 72 h ab Kenntnis:**\
  Erste Bewertung des Sicherheitsvorfalls, inklusive Schweregrad, Auswirkungen und ggf. die Kompromittierungsindikatoren.
- **Fortschritts-/Abschlussbericht ein Monat nach Meldung:**\
  Ausführliche Beschreibung, Angaben zur Art der Bedrohung, Ursachen, Abhilfemaßnahmen, ggf. die grenzüberschreitenden Auswirkungen.

#### Registrierung

(Art. 1 § 33-34 im NIS2UmsuCG-Entwurf)

Wenn für das Unternehmen NIS-2 gilt, muss eine Registrierung erfolgen. Die Registrierung wird bei der nationalen Behörde vorgenommen.
Wie genau, wurde noch nicht festgelegt. Wenn es dann soweit ist, sollte das auf der Webseite vom BSI veröffentlicht werden.

**Folgende Informationen sind einzureichen:**

- Name der Einrichtung, einschließlich der Rechtsform und soweit einschlägig der Handelsregisternummer
- Anschrift und aktuelle Kontaktdaten, einschließlich E-Mail-Adresse
- öffentliche IP-Adressbereiche und Telefonnummern
- relevanter in Anlage 1 oder 2 genannter Sektor oder soweit einschlägig Branche
- Auflistung derjenigen Mitgliedstaaten der Europäischen Union, in denen die Einrichtung Dienste der in Anlage 1 oder 2 genannten Einrichtungsarten erbringen
- die für die Tätigkeiten, aufgrund derer die Registrierung erfolgt, zuständigen Aufsichtsbehörden des Bundes und der Länder
- ggf. weitere Informationen je nach Einrichtungsart

## Wer ist eigentlich betroffen?

Das BSI hat eine ["Prüfung"](https://betroffenheitspruefung-nis-2.bsi.de/) zur Verfügung gestellt. Hier können Unternehmen selbst schauen, ob sie Betroffen sind.

> [!NOTE]
> Die NIS-2-Betroffenheitsprüfung dient als automatische Orientierungshilfe auf Grundlage von Eigenangaben, deren Ergebnis nicht rechtlich bindend ist. Die NIS-2-Betroffenheitsprüfung ersetzt die Prüfung zur Selbst-Identifizierung nicht und hat für eventuelle Verfahren keine Indizwirkung.

Voraussetzung:

- Unternehmen in einer der [Sektoren](#sektoren)
- Unternehmen mit mindestens 50 Mitarbeitern oder
- 10 Mio. € Jahresumsatz
- Einige [Sonderfälle](#sonderfälle) unabhängig von ihrer Größe

### Sektoren

#### Sektoren mit hoher Kritikalität

##### Energie

| Teilsektor           | Art der Einrichtung                                                                                                                    |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Elektrizität         | - Elektrizitätsunternehmen                                                                                                             |
|                      | - Verteilernetzbetreiber                                                                                                               |
|                      | - Übertragungsnetzbetreiber                                                                                                            |
|                      | - Erzeuger                                                                                                                             |
|                      | - nominierte Strommarktbetreiber                                                                                                       |
|                      | - Marktteilnehmer, die Aggregierungs-, Laststeuerungs- oder Energiespeicherungsdienste anbieten                                        |
|                      | - Betreiber von Ladepunkten für Elektromobilität                                                                                       |
| Fernwärme und -kälte | - Betreiber von Fernwärme oder Fernkälte                                                                                               |
| Erdöl                | - Betreiber von Erdöl-Fernleitungen                                                                                                    |
|                      | - Betreiber von Anlagen zur Produktion, Raffination und Aufbereitung von Erdöl sowie Betreiber von Erdöllagern und Erdöl-Fernleitungen |
|                      | - zentrale Bevorratungsstellen                                                                                                         |
| Erdgas               | - Versorgungsunternehmen                                                                                                               |
|                      | - Verteilernetzbetreiber                                                                                                               |
|                      | - Fernleitungsnetzbetreiber                                                                                                            |
|                      | - Betreiber einer Speicheranlage                                                                                                       |
|                      | - Betreiber einer LNG-Anlage                                                                                                           |
|                      | - Erdgasunternehmen                                                                                                                    |
|                      | - Betreiber von Anlagen zur Raffination und Aufbereitung von Erdgas                                                                    |
| Wasserstoff          | - Betreiber im Bereich Wasserstofferzeugung, -speicherung und -fernleitung                                                             |

##### Verkehr

| Teilsektor      | Art der Einrichtung                                                                                                                                                                                                                                                          |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Luftverkehr     | - Luftfahrtunternehmen                                                                                                                                                                                                                                                       |
|                 | - Flughafenleitungsorgane                                                                                                                                                                                                                                                    |
|                 | - Betreiber von Verkehrsmanagement- und Verkehrssteuerungssystemen                                                                                                                                                                                                           |
| Schienenverkehr | - Infrastrukturbetreiber                                                                                                                                                                                                                                                     |
|                 | - Eisenbahnunternehmen                                                                                                                                                                                                                                                       |
| Schifffahrt     | - Passagier- und Frachtbeförderungsunternehmen der Binnen-, See- und Küstenschifffahrt                                                                                                                                                                                       |
|                 | - Leitungsorgane von Häfen, einschließlich ihrer Hafenanlagen                                                                                                                                                                                                                |
|                 | - Einrichtungen, die innerhalb von Häfen befindliche Anlagen und Ausrüstung betreiben                                                                                                                                                                                        |
|                 | - Betreiber von Schiffsverkehrsdiensten                                                                                                                                                                                                                                      |
| Straßenverkehr  | - Straßenverkehrsbehörden, die für Verkehrsmanagement und Verkehrssteuerung verantwortlich sind (außer öffentliche Einrichtungen, für die das Verkehrsmanagement oder der Betrieb intelligenter Verkehrssysteme ein nicht wesentlicher Teil ihrer allgemeinen Tätigkeit ist) |
|                 | - Betreiber intelligenter Verkehrssysteme                                                                                                                                                                                                                                    |

##### Bankwesen

| Teilsektor | Art der Einrichtung |
| ---------- | ------------------- |
| -          | - Kreditinstitute   |

##### Finanzmarktinfrastruktur

| Teilsektor | Art der Einrichtung            |
| ---------- | ------------------------------ |
| -          | - Betreiber von Handelsplätzen |
|            | - zentrale Gegenparteien       |

##### Gesundheitswesen

| Teilsektor | Art der Einrichtung                                                                                           |
| ---------- | ------------------------------------------------------------------------------------------------------------- |
| -          | - Gesundheitsdienstleister                                                                                    |
|            | - EU-Referenzlaboratorien                                                                                     |
|            | - Einrichtungen, die Forschungs- und Entwicklungstätigkeiten in Bezug auf Arzneimittel ausüben                |
|            | - Einrichtungen, die bestimmte pharmazeutische Erzeugnisse herstellen                                         |
|            | - Einrichtungen, die kritische Medizinprodukte für Notlagen im Bereich der öffentlichen Gesundheit herstellen |

##### Trinkwasser

| Teilsektor | Art der Einrichtung                                                                                                                                                                       |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -          | - Lieferanten von und Unternehmen der Versorgung mit „Wasser für den menschlichen Gebrauch“                                                                                               |
|            | - außer Lieferanten, für die die Lieferung von Wasser für den menschlichen Gebrauch ein nicht wesentlicher Teil ihrer allgemeinen Tätigkeit der Lieferung anderer Rohstoffe und Güter ist |

##### Abwasser

| Teilsektor | Art der Einrichtung                                                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -          | - Unternehmen, die kommunales Abwasser, häusliches Abwasser oder industrielles Abwasser sammeln, entsorgen oder behandeln                                  |
|            | - außer Unternehmen, für die das Sammeln, die Entsorgung oder die Behandlung solchen Abwassers ein nicht wesentlicher Teil ihrer allgemeinen Tätigkeit ist |

##### Digitale Infrastruktur

| Teilsektor | Art der Einrichtung                                                     |
| ---------- | ----------------------------------------------------------------------- |
| -          | - Betreiber von Internet-Knoten                                         |
|            | - DNS-Dienstanbieter, ausgenommen Betreiber von Root-Namenservern       |
|            | - TLD-Namenregister                                                     |
|            | - Anbieter von Cloud-Computing-Diensten                                 |
|            | - Anbieter von Rechenzentrumsdiensten                                   |
|            | - Betreiber von Inhaltszustellnetzen                                    |
|            | - Vertrauensdiensteanbieter                                             |
|            | - Anbieter öffentlicher elektronischer Kommunikationsnetze              |
|            | - Anbieter öffentlich zugänglicher elektronischer Kommunikationsdienste |

##### Verwaltung von ITK-Diensten (B2B)

| Teilsektor | Art der Einrichtung                       |
| ---------- | ----------------------------------------- |
| -          | - Anbieter verwalteter Dienste            |
|            | - Anbieter verwalteter Sicherheitsdienste |

##### Öffentliche Verwaltung

| Teilsektor | Art der Einrichtung                                                                                                                        |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| -          | - Einrichtungen der öffentlichen Verwaltung von Zentralregierungen entsprechend der Definition eines Mitgliedstaats gemäß nationalem Recht |
|            | - Einrichtungen der öffentlichen Verwaltung auf regionaler Ebene entsprechend der Definition eines Mitgliedstaats gemäß nationalem Recht   |

##### Weltraum

| Teilsektor | Art der Einrichtung                                                                                                                                                                                                             |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| -          | - Betreiber von Bodeninfrastrukturen, die sich im Eigentum von EU-Mitgliedstaaten oder privaten Parteien befinden und von diesen verwaltet und betrieben werden und die Erbringung von weltraumgestützten Diensten unterstützen |
|            | - außer Anbieter öffentlicher elektronischer Kommunikationsnetze                                                                                                                                                                |

#### Sonstige kritische Sektoren

##### Post- und Kurierdienste

| Teilsektor | Art der Einrichtung                          |
| ---------- | -------------------------------------------- |
| -          | - Anbieter von Postdiensten                  |
|            | - einschließlich Anbieter von Kurierdiensten |

##### Abfallbewirtschaftung

| Teilsektor | Art der Einrichtung                                                                               |
| ---------- | ------------------------------------------------------------------------------------------------- |
| -          | - Unternehmen der Abfallbewirtschaftung                                                           |
|            | - ausgenommen Unternehmen, für die Abfallbewirtschaftung nicht ihre Hauptwirtschaftstätigkeit ist |

##### Produktion, Herstellung und Handel mit chemischen Stoffen

| Teilsektor | Art der Einrichtung                                                                   |
| ---------- | ------------------------------------------------------------------------------------- |
| -          | - Unternehmen, die chemische Stoffe herstellen und mit Stoffen oder Gemischen handeln |
|            | - Unternehmen, die Erzeugnisse aus diesen Stoffen oder Gemischen produzieren          |

##### Produktion, Herstellung und Vertrieb von Lebensmitteln

| Teilsektor | Art der Einrichtung                                                                                            |
| ---------- | -------------------------------------------------------------------------------------------------------------- |
| -          | - Lebensmittelunternehmen, die im Großhandel sowie in der industriellen Produktion und Verarbeitung tätig sind |

##### Verarbeitendes Gewerbe/Herstellung von Waren

| Teilsektor                                                                           | Art der Einrichtung                                                                                                              |
| ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Herstellung von Medizinprodukten und In-vitro-Diagnostika                            | - Einrichtungen, die Medizinprodukte herstellen                                                                                  |
|                                                                                      | - Einrichtungen, die In-vitro-Diagnostika herstellen                                                                             |
|                                                                                      | - außer Einrichtungen aus Anhang I, die kritische Medizinprodukte für Notlagen im Bereich der öffentlichen Gesundheit herstellen |
| Herstellung von Datenverarbeitungsgeräten, elektronischen und optischen Erzeugnissen | - Unternehmen, die in diesem Wirtschaftszweig gemäß [NACE Rev. 2](#nace-rev-2) tätig sind                                        |
| Herstellung von elektrischen Ausrüstungen                                            | - Unternehmen, die in diesem Wirtschaftszweig gemäß [NACE Rev. 2](#nace-rev-2) tätig sind                                        |
| Maschinenbau                                                                         | - Unternehmen, die in diesem Wirtschaftszweig gemäß [NACE Rev. 2](#nace-rev-2) tätig sind                                        |
| Herstellung von Kraftwagen und Kraftwagenteilen                                      | - Unternehmen, die in diesem Wirtschaftszweig gemäß [NACE Rev. 2](#nace-rev-2) tätig sind                                        |
| sonstiger Fahrzeugbau                                                                | - Unternehmen, die in diesem Wirtschaftszweig gemäß [NACE Rev. 2](#nace-rev-2) tätig sind                                        |

##### Anbieter digitaler Dienste

| Teilsektor | Art der Einrichtung                                       |
| ---------- | --------------------------------------------------------- |
| -          | - Anbieter von Online-Marktplätzen                        |
|            | - Anbieter von Online-Suchmaschinen                       |
|            | - Anbieter von Plattformen für Dienste sozialer Netzwerke |

##### Forschung

| Teilsektor | Art der Einrichtung       |
| ---------- | ------------------------- |
| -          | - Forschungseinrichtungen |

### Sonderfälle

Diese Einrichtungen fallen unabhängig von ihrer Größe unter die NIS-2:

- Betreiber kritischer Anlagen
- Qualifizierte Vertrauensdiensteanbieter
- Top Level Domain Name Registries oder DNS-Diensteanbieter
- Vertrauensdiensteanbieter
- Anbieter öffentlich zugänglicher Telekommunikationsdienste oder Betreiber öffentlicher Telekommunikationsnetze
- Bundesbehörden
- öffentlich-rechtlich organisierte IT-Dienstleister der Bundesverwaltung
- weitere Körperschaften, Anstalten und Stiftungen des öffentlichen Rechts sowie ihre Vereinigungen, ungeachtet ihrer Rechtsform, auf Bundesebene, soweit durch das Bundesamt im Einvernehmen mit dem jeweils zuständigen Ressort angeordnet; mit einigen Ausnahmen

Zusätzlich gilt die neue Richtlinie indirekt auch für Dienstleister und Lieferanten von betroffenen Einrichtungen.

## Was passiert, wenn Sie die NIS-2 Vorschriften nicht einhalten?

Bei Verstößen gegen die Risikomanagementmaßnahmen (Art. 1 § 30 im NIS2UmsuCG-Entwurf) oder Meldepflicht von Sicherheitsvorfällen (Art. 1 § 32 im NIS2UmsuCG-Entwurf) drohen hohe Geldstrafen.

Der deutsche NIS2UmsuCG-Entwurf trifft eine Einteilung in besonders wichtige und wichtige Einrichtungen.

Während die Pflichten grundsätzlich gleich sind, unterscheiden sie sich darin, wie streng die Aufsicht ist und wie hoch die Geldstrafen bei Non-Compliance ausfallen.

|                                              | **Besonders wichtige Einrichtungen**                                                                                                  | **Wichtige Einrichtungen**                                                                                                             |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **Aufsicht durch Behörden** (Art. 1 § 61-62) | Proaktive Aufsicht ohne vorige Hinweise auf Verstöße, zum Beispiel (nach Ermessen des BSI):                                           | Reaktive Aufsicht nur nach Hinweisen auf Verstöße, zum Beispiel (nach Ermessen des BSI):                                               |
|                                              | - Anordnung, dass unabhängige Stellen die Umsetzung prüfen (keine freie Wahl von Prüfern)                                             | - Anordnung, dass unabhängige Stellen die Umsetzung prüfen (keine freie Wahl von Prüfern)                                              |
|                                              | - Anforderung von Nachweisen (erst ab 3 Jahren nach Inkrafttreten)                                                                    | - Anforderung von Nachweisen (erst ab 3 Jahren nach Inkrafttreten)                                                                     |
|                                              | - direkte Prüfungen vor Ort und durch vom BSI beauftragte Dritte                                                                      | - direkte Prüfungen vor Ort und durch vom BSI beauftragte Dritte                                                                       |
|                                              | - Sanktionen bis hin zur vorübergehenden Abberufung der Geschäftsleitung und Entzug der Betriebsgenehmigung                           | - Sanktionen bis hin zur vorübergehenden Abberufung der Geschäftsleitung und Entzug der Betriebsgenehmigung                            |
| **Geldstrafen bei Verstößen** (Art. 1 § 65)  | Höchstbetrag von mindestens 10 Millionen Euro oder 2 % des weltweiten Umsatzes im vorigen Jahr – je nachdem, welcher Betrag höher ist | Höchstbetrag von mindestens 7 Millionen Euro oder 1,4 % des weltweiten Umsatzes im vorigen Jahr – je nachdem, welcher Betrag höher ist |
| **Wer zählt dazu?**                          | **Große Unternehmen aus Anlage 1 im NIS2UmsuCG-Entwurf:**                                                                             | **Große Unternehmen aus Anlage 2 im NIS2UmsuCG-Entwurf:**                                                                              |
|                                              | - > 249 Beschäftigte, oder                                                                                                            | - > 249 Beschäftigte, oder                                                                                                             |
|                                              | > 50 Mio. EUR Umsatz und > 43 Mio. EUR Bilanz                                                                                         | > 50 Mio. EUR Umsatz und > 43 Mio. EUR Bilanz                                                                                          |
|                                              | **Größenunabhängige [Sonderfälle](#sonderfälle)**                                                                                     | **Mittlere Unternehmen aus Anlage 1 oder Anlage 2 im NIS2UmsuCG-Entwurf:**                                                             |
|                                              |                                                                                                                                       | - mind. 50 Beschäftigte, oder                                                                                                          |
|                                              |                                                                                                                                       | - > 10 Mio. EUR Umsatz und > 10 Mio. EUR Bilanz                                                                                        |
|                                              |                                                                                                                                       | - kein großes Unternehmen                                                                                                              |
|                                              |                                                                                                                                       | **Größenunabhängige [Sonderfälle](#sonderfälle)**                                                                                      |
|                                              |                                                                                                                                       | Hinweis: Die Einstufung als „besonders wichtig“ geht immer vor.                                                                        |

## NACE Rev. 2

### Statistische Systematik der Wirtschaftszweige in der Europäischen Gemeinschaft

Link: [PDF](https://ec.europa.eu/eurostat/documents/3859598/5902453/KS-RA-07-015-DE.PDF)

Die NACE Rev. 2 ist die statistische Systematik der Wirtschaftszweige in der Europäischen Gemeinschaft und dient der Erfassung und Analyse wirtschaftlicher Aktivitäten. Sie betrifft eine Vielzahl von Unternehmen und Wirtschaftszweigen, die in verschiedene Abschnitte, Abteilungen, Gruppen und Klassen unterteilt sind. Hier sind die wichtigsten betroffenen Bereiche:

### Hauptbetroffene Bereiche

#### 1. Landwirtschaft, Forstwirtschaft und Fischerei (Abschnitt A)

- Umfasst Tätigkeiten wie den Anbau von Pflanzen, Tierhaltung, Forstwirtschaft und Fischerei.

#### 2. Bergbau und Gewinnung von Steinen und Erden (Abschnitt B)

- Beinhaltet den Abbau von Kohle, Öl, Gas sowie anderen mineralischen Ressourcen.

#### 3. Verarbeitendes Gewerbe (Abschnitt C)

- Umfasst die Herstellung von Waren in Bereichen wie Nahrungsmittel, Textilien, Chemikalien, Maschinen und Elektronik.

#### 4. Energieversorgung (Abschnitt D) und Wasserversorgung (Abschnitt E)

- Beinhaltet die Erzeugung und Verteilung von Strom, Gas und Wasser sowie Abfallentsorgung.

#### 5. Baugewerbe (Abschnitt F)

- Umfasst Bauarbeiten im Hoch- und Tiefbau sowie spezialisierte Bauinstallationen.

#### 6. Handel; Instandhaltung und Reparatur von Kraftfahrzeugen (Abschnitt G)

- Beinhaltet Groß- und Einzelhandel sowie Reparaturdienste für Fahrzeuge.

#### 7. Verkehr und Lagerei (Abschnitt H)

- Umfasst Transportdienstleistungen auf Straße, Schiene, Wasser und Luft sowie Lagerhaltung.

#### 8. Gastgewerbe (Abschnitt I)

- Beinhaltet Beherbergung und Gastronomie.

#### 9. Information und Kommunikation (Abschnitt J)

- Umfasst Telekommunikation, IT-Dienstleistungen und Medienproduktion.

#### 10. Finanz- und Versicherungsdienstleistungen (Abschnitt K)

- Beinhaltet Banken, Versicherungen und andere Finanzdienstleistungen.

#### 11. Grundstücks- und Wohnungswesen (Abschnitt L)

- Umfasst Immobilienvermittlung, -verwaltung und -entwicklung.

#### 12. Freiberufliche, wissenschaftliche und technische Dienstleistungen (Abschnitt M)

- Beinhaltet Rechtsberatung, Buchhaltung, Architektur und Ingenieurwesen.

#### 13. Sonstige wirtschaftliche Dienstleistungen (Abschnitt N)

- Umfasst Vermietung von Maschinen, Reisebüros und Sicherheitsdienste.

#### 14. Öffentliche Verwaltung, Verteidigung; Sozialversicherung (Abschnitt O)

- Beinhaltet staatliche Verwaltungsdienste auf verschiedenen Ebenen.

#### 15. Erziehung und Unterricht (Abschnitt P) sowie Gesundheits- und Sozialwesen (Abschnitt Q)

- Umfasst Bildungsinstitutionen sowie Krankenhäuser und soziale Einrichtungen.

### Struktur der NACE Rev. 2

Die NACE Rev. 2 ist hierarchisch strukturiert:

- Abschnitte: Alphabetisch gekennzeichnet.
- Abteilungen: Zweistelliger numerischer Code.
- Gruppen: Dreistelliger numerischer Code.
- Klassen: Vierstelliger numerischer Code
  Diese Systematik ermöglicht eine detaillierte Klassifizierung wirtschaftlicher Aktivitäten in der EU zur Unterstützung von Statistiken für politische Entscheidungen, wirtschaftliche Analysen und Unternehmensstrategien

> [!WARNING]
> Diese Aufstellung wurde durch Perplexity Pro mit dem KI-Modell GPT-4o erstellt.

## Ansätze

### Risikobasierter Ansatz

#### Welche Maßnahmen sind angemessen?

Unternehmen müssen geeignete, verhältnismäßige und wirksame technische und organisatorische Maßnahmen ergreifen, die den Stand der Technik einhalten und die die einschlägigen europäischen und internationalen Normen berücksichtigen. Um zu bewerten, ob die Maßnahmen verhältnismäßig sind, ist Folgendes zu beachten:

- Ausmaß der Risikoexposition
- Größe der Einrichtung
- Umsetzungskosten
- Eintrittswahrscheinlichkeit und Schwere von Sicherheitsvorfällen
- Gesellschaftliche und wirtschaftliche Auswirkungen von Sicherheitsvorfällen

## Leitfaden Notfallmanagement

### Must-Haves für NIS2

#### Für den Ernstfall vorbereiten

Welche Notfälle gibt es denn so?

- Naturkatastrophen
- Brände
- Personalausfall
- IT Notfälle
  - z.B. Ransomware

Dementsprechend schreibt die neue europäische Networks-and-Security-Richtlinie 2.0 - kurz NIS2 auch ein IT-Notfallmanagement vor.

Folgende Fragen stellen sich hier:

- Was umfasst das Notfallmanagement?
- Wie erstellt man einen Notfallplan und wie sieht ein solcher aus?
- Warum lohnt sich gerade eine pragmatische Vorgehensweise? Auf was ist bei der Umsetzung zu achten?
- Welche Maßnahmen sind präventiv notwendig?

> Nur mit einem effektiven Notfallmanagement können Unternehmen während und nach eines Notfalls ihren Geschäftsbetrieb und ihre Existenz sicherstellen.[^2]

### Einstieg ins Notfallmanagement

Mit ISO 22301 sind die Anforderungen an die Planung, den strukturierten Aufbau, die Implementierung, Überwachung und Verbesserung des Notfallmanagements spezifiziert.

<!-- TODO: Recherche -->

Für welche Bereiche und Szenarien wird ein Notfallplan benötigt?

Häufige Bereiche sind:

- Endgeräte
- Hardware
- IT-Systeme und Applikationen
- Cloud-Services
- Internes Rechenzentrum
- ...

Die Bereiche sind immer Unternehmensindividuell. Grundlagen ist jedoch immer eine "Business Impact Analyse". Diese gibt Aufschluss darüber, welche Prozesse besonders abzusichern sind.
Die Bewertung erfolgt anhand der Schwere der zu erwartenden Schäden eines Notfalls (z.B. finanziell, Auswirkung auf Kunden, Image, etc.) sowie der Kritikalität des Prozesses.

### Perfekt für den Notfall gerüstet mit einem Notfallplan

Nach der Identifikation und Bewertung der kritischen Prozesse durch die "Business Impact Analyse" gilt es, einen Notfallplan zu erstellen.
Eine der häufigsten Anwendungsfälle ist beispielsweise die Frage, wie prozessrelevante Datenbestände nach einer Ransomware-Attacke wieder zum laufen gebracht werden.
Ein Notfallplan beschreibt zum einen die konkreten Abläufe und Sofort-Maßnahmen bei Eintritt eines Notfalls.
Zum anderen werden hier die zur Wiederherstellung eines Ausfalls benötigten Ressourcen und Schritte sowie zeitlichen Rahmenbedingungen spezifiziert.
**Ein Notfallplan ist klar strukturiert aufgebaut, verständlich und auch für Dritte leicht zu befolgen. Damit im Ernstfall jeder weiß, was zu tun ist.**

Die Erstellung eines Notfallplans erfordert eine enge Zusammenarbeit zwischen IT, Geschäftsleitung und den betroffenen Fachabteilungen.
Je nachdem, in welchem Bereich ein Notfallplan erstellt wird, sollten auch Partner und Dienstleister sowie Rechtsberater bei der Erstellung mitwirken.
Zusätzlich muss für jeden Notfallplan ein Wiederherstellungsmanager (z.B. Geschäftsleitung, CIO, CEO) und ein Krisenstab benannt werden.
Dieser bildet bei einem Notfall das "zentrale Gremium" und den Kreis der Wiederhersteller.

Die Entwicklung eines Notfallplans is komplex und erfordert in der Praxis eine Reihe von Analysen, Workshops, Abstimmungen und: Erfahrung.

#### Auszug eines IT-Notfallplans

1. Einordnung des IT-Notfallplans
2. Alarmierung und Eskalation
3. IT-Sofortmaßnahmen
4. IT-Notfall-Stab

5. Benötigte Ressourcen

Die folgenden Ressourcen werden für die Wiederherstellung eingesetzt:

| Name der Ressource                                       | Beschreibung | Menge / Anzahl | Wann wird die Ressource benötigt | Verantwortlich für die Beschaffung der Ressource |
| -------------------------------------------------------- | ------------ | -------------- | -------------------------------- | ------------------------------------------------ |
| Personen                                                 |              |                |                                  |                                                  |
| ...                                                      |              |                |                                  |                                                  |
| Anwendungen/ Datenbanken                                 |              |                |                                  |                                                  |
| ...                                                      |              |                |                                  |                                                  |
| Daten in elektronischer Form                             |              |                |                                  |                                                  |
| z.B. Strategie für Kontinuität und Pläne für Aktivitäten |              |                | z.B. innerhalb von 2 Stunden     |                                                  |
| ...                                                      |              |                |                                  |                                                  |
| Daten in Papierform                                      |              |                |                                  |                                                  |
| ...                                                      |              |                | z.B. sofort                      |                                                  |
| IT- und Kommunikationsausstattung                        |              |                |                                  |                                                  |
| z.B. Arbeitsstationen                                    |              |                | z.B. innerhalb von 2 Tagen       |                                                  |
| ...                                                      |              |                |                                  |                                                  |

6. Schritte zur Wiederherstellung

Die Informationen in diesem Abschnitt definieren die Tätigkeiten zur Umsetzung der Lösung/von Lösungen für die Wiederherstellung

| Wiederherstellungs-Verfahren (wichtige Schritte/ individuelle Angaben) | Verantwortlich für die Umsetzung | Kommunikation (Inhalt, an wen) | Umsetzungs-Protokoll (Datum/ Zeit) |
| ---------------------------------------------------------------------- | -------------------------------- | ------------------------------ | ---------------------------------- |
| [Bezeichnung Schritt Nr. 1]                                            |                                  |                                |                                    |
| [Aufgabe Nr 1.1]                                                       |                                  |                                |                                    |
| [Aufgabe Nr 1.2]                                                       |                                  |                                |                                    |
| ...                                                                    |                                  |                                |                                    |
| [Bezeichnung Schritt Nr. 2]                                            |                                  |                                |                                    |
| [Aufgabe Nr 2.1]                                                       |                                  |                                |                                    |
| [Aufgabe Nr 2.2]                                                       |                                  |                                |                                    |
| ...                                                                    |                                  |                                |                                    |

7. Überführung in den Normalbetrieb
8. Notfallübungen und -tests
9. Verzeichnisse

### Pragmatische Vorgehensweise

Das Notfallmanagement ist komplex und umfangreich.

Vor diesem Hintergrund lohnt es sich, klare Prioritäten auf Basis der Analyse abzuleiten und das Notfallmanagement Schritt für Schritt umzusetzen.
Man sollte nicht einen riesigen Notfallplan ausarbeiten. Lieber einen kompakten Plan für einen konkreten Notfall - beispielsweise den Ausfall des ERP-Systems.
Unter der Vorratssetzung, das alles, außer das ERP-System läuft.
Ist dieser Plan erstellt, dann den nächsten Plan ausarbeiten, z.B. einen Hardware Notfall.
Das wird solange weitergeführt, bis für die wichtigsten Bereiche ein Notfallplan vorliegt.

> Ein Notfallplan darf nicht nur ein Dokument sein, das in der Schublade verschwindet. Es muss regelmäßig durchgespielt, erprobt und angepasst werden.[^2]

[^2]: Sven Hillebrecht, General Manager & ISMB ADLON

Beim Notfallmanagement ist auf ein pragmatisches und praxisnahes Vorgehen zu achten.
Doch: Der Aufwand ist und bleibt hoch und die Zeit durch NIS2 knapp.

### Weitere Anforderungen durch NIS2

Ein solides Notfallmanagement im IT-Bereich ist für jedes Unternehmen existenziell. Daneben erfordert NIS2 u.a. auch die Einrichtung eines Risikomanagements sowie regelmäßige Risikoanalysen. Apropos Risiken: Zu den häufigsten IT-Risiken gehören neben Ransomware-Attacken auf Denial of Service Attacken (DDoS), Supply-Chain-Attacken, Social-Engineering-Attacken sowie Schwachstellen in Cloud-Diensten und IoT-Geräten.

Daher ist besonderer Fokus zu legen auf den:

- Schutz der Endgeräte
- Schutz der Identitäten und Konten
- Schutz der Kommunikation
- Schutz der Cloud Apps

Zum präventiven Schutz ist der Einsatz von Security-Technologien unabdingbar.

### Prävention statt Krise

Die neue EU-Richtlinie NIS2 fördert und fordert Cybersicherheit auf breiter Ebene.

1. Vorbereitung auf den Ernstfall: Ein solides Notfallmanagement etablieren. Bewährt hat sich hierbei ein pragmatisches, praxisnahes und schrittweises Vorgehen gemeinsam mit einem externen Partner.
2. Nicht nur an den Notfall denken, sondern für umfassende präventive Maßnahmen sorgen.
3. Ein solides und gleichzeitig pragmatisches Risikomanagement einsetzen. Regelmäßige Risikoanalysen durchführen, dabei auf die Dokumentation achten.

## Quellen

- [https://www.gdata.de/business/nis-2-richtlinie?utm_source=google&utm_medium=ppc&utm_campaign=nis2-kw&utm_content=search&utm_term=nis2&gad_source=1&gclid=Cj0KCQjwjY64BhCaARIsAIfc7YbZQ8PAnrh_wE1fT_joajeWMExPN9kAgh6F2T8OkjEoXhJZI0MxYVMaAi8GEALw_wcB](https://www.gdata.de/business/nis-2-richtlinie?utm_source=google&utm_medium=ppc&utm_campaign=nis2-kw&utm_content=search&utm_term=nis2&gad_source=1&gclid=Cj0KCQjwjY64BhCaARIsAIfc7YbZQ8PAnrh_wE1fT_joajeWMExPN9kAgh6F2T8OkjEoXhJZI0MxYVMaAi8GEALw_wcB)
- [https://www.gdata.de/fileadmin/web/de/documents/flyer/G_DATA_NIS2_Merkblatt.pdf](https://www.gdata.de/fileadmin/web/de/documents/flyer/G_DATA_NIS2_Merkblatt.pdf)
- [https://www.gdata.de/webinar-nis-2-fristen-pflichten-uebergang](https://www.gdata.de/webinar-nis-2-fristen-pflichten-uebergang)
- [https://betroffenheitspruefung-nis-2.bsi.de/](https://betroffenheitspruefung-nis-2.bsi.de/)
- [https://www.bmi.bund.de/SiteGlobals/Forms/suche/gesetzgebungsverfahren-formular.html](https://www.bmi.bund.de/SiteGlobals/Forms/suche/gesetzgebungsverfahren-formular.html)
- [https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/14241-Cybersicherheitsrisikomanagement-und-Berichtspflichten-fur-digitale-Infrastrukturen-Anbieter-und-IKT-Servicemanager_de](https://ec.europa.eu/info/law/better-regulation/have-your-say/initiatives/14241-Cybersicherheitsrisikomanagement-und-Berichtspflichten-fur-digitale-Infrastrukturen-Anbieter-und-IKT-Servicemanager_de)
- [https://www.perplexity.ai/](https://www.perplexity.ai/)
- [https://www.securepoint.de/fuer-partner/alles-zu-nis-2](https://www.securepoint.de/fuer-partner/alles-zu-nis-2)
- [https://adlon.de/services/nis2-umsetzung/](https://adlon.de/services/nis2-umsetzung/)
- [https://adlon.de/leitfaden-notfallmanagement/](https://adlon.de/leitfaden-notfallmanagement/)
