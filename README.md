Erweitert die Text-(›Lynx‹)-Fahrplanauskunft der Bahn ( http://reiseauskunft.bahn.de/bin/query.exe/dl ) um Tür-zu-Tür- und POI-Routing.

**Vorher:** Als Start- und Zielpunkt können nur Haltestellen angegeben werden.

**Nachher:** Zusätzlich kann als Start- und Zielpunkt nun angegeben werden:

* eine **Hausadresse** (›Tür-zu-Tür‹ im Format ›Straße Hausnummer, PLZ Ort‹)
* einen **Point-of-Interest** (POI) wie z.B. Theater, Kirchen, öffentliche Einrichtungen etc.

Die Erkennung erfolgt automatisch.

**Beispiel:**

Von Kölner Dom nach Kurfürstenring 10, Wesel wird erkannt als:

von: ...... Köln, Kölner Dom (Öffentliche Einrichtungen)
nach: ..... Wesel, Kurfürstenring 10

**Ergebnis in der Übersicht:**

     +-------------------------+---------------------+----+--------+--------+
     |     Bahnhof ab          | Bahnhof an          | Um |   Ab   |   An   |
     +-------------------------+---------------------+----+--------+--------+
     |  1. Köln, Kölner Dom (Öf| Wesel, Kurfürstenrin|  0 |  12:23 |  14:09 |
     |  2. Köln, Kölner Dom (Öf| Wesel, Kurfürstenrin|  1 |  12:41 |  14:28 |
     |  3. Köln, Kölner Dom (Öf| Wesel, Kurfürstenrin|  2 |  13:02 |  14:45 |
     |  4. Köln, Kölner Dom (Öf| Wesel, Kurfürstenrin|  1 |  13:02 |  14:46 |
     +-------------------------+---------------------+----+--------+--------+

**Ergebnis in der Detailansicht:**

     +-------------------------+--------+--------+----------+----------------+
     | Köln, Kölner Dom (Öffen |        |        | Fußweg   | 5 Min.         |
     | Köln Hbf                |        |        | Fußweg   | 2 Min.         |
     | Köln Hbf                |        |  13:10 | IC  2218 |FR FB BR        |
     | Duisburg Hbf            |  13:44 |  13:58 | RB 10336 |FB              |
     | Friedrichsfeld(Niederrh |  14:28 |        | Fußweg   | 3 Min.         |
     | Friedrichsfeld Bahnhof, |        |  14:31 | Bus   80 |1. zG           |
     | Wesel Post              |  14:38 |        | Fußweg   | 7 Min.         |
     | Wesel, Kurfürstenring 1 |  14:45 |        |          |                |
     +-------------------------+--------+--------+----------+----------------+
     | Fahrzeit: 1:43;                                                       |
     | fährt Mo - Fr, nicht 22., 25. Apr, 2., 13., 23. Jun, 3. Okt, 1. Nov   |
     | Preisauskunft nicht möglich                                           |
     | FR: Fahrradmitnahme reservierungspflichtig                            |
     | FB: Fahrradmitnahme begrenzt möglich                                  |
     | 1.: Wesel Bahnhof                                                     |
     | FB: Fahrradmitnahme begrenzt möglich                                  |
     | BR: Bordrestaurant                                                    |
     | zG: Am 24., 25., 31.12. und 01.01. Verkehr nach besonderer Bekanntmach|
     +-------------------------+--------+--------+----------+----------------+

