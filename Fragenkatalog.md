# Fragenkatalog A TipTap Challenge

## **Challenge Set 1: Einstieg in Daten und Tools (Beginner Level)**

1. **Identifikation von Trinkwasserquellen**
   - Aufgabe: Beschafft die Daten zu Trinkwasserquellen für Berlin aus einer der angegebenen Quellen (z. B. OpenStreetMap, Refill-Daten, BWB).
   - Ziel: Stellt die Daten in einem geeigneten Format (z. B. CSV oder GeoJSON) bereit und visualisiert sie auf einer Karte in QGIS oder Python.

2. **Satellitendaten herunterladen**
   - Aufgabe: Ladet öffentliche Satellitendaten herunter, die sich zur Erkennung von Hitzeinseln eignen (z. B. Sentinel-3, Landsat 8).
   - Ziel: Öffnet die Daten in QGIS und identifiziert auffällige Unterschiede in der Oberflächentemperatur.

3. **Datenformat und Vorbereitung**
   - Aufgabe: Konvertiert die heruntergeladenen Daten in ein einheitliches Format.
   - Ziel: Erstellt eine saubere, strukturierte Datenbasis, die für weitere Analysen geeignet ist.

4. **Datenquellen bewerten**  
   - Welche Vor- und Nachteile haben die unterschiedlichen Datenquellen (z. B. OpenStreetMap, Refill-Daten, BWB)?  
   - Wie vergleicht man diese Datenquellen hinsichtlich Vollständigkeit, Aktualität und Zuverlässigkeit?

5. **Satellitendaten extrahieren**  
   - Wie kann man bestimmte Daten wie Landoberflächentemperaturen oder Vegetationsindizes (z. B. NDVI) aus Satellitenbildern extrahieren?  
   - Welche Datenvorverarbeitungs-Schritte sind notwendig (z. B. Wolkenmaskierung, Reskalierung)?

---

## **Challenge Set 2: Datenaufbereitung und erste Analysen (Intermediate Level)**

6. **Hitzeinseln definieren**  
   - Wie definiert man eine Hitzeinsel mit quantitativen Kriterien? (z. B. Temperaturabweichung über x°C im Vergleich zur Umgebung)  
   - Wie können diese Schwellenwerte je nach Umgebung (städtisch vs. ländlich) variieren?

7. **Hitzeinseln kartieren**
   - Aufgabe: Analysiert Satellitendaten, um städtische Hitzeinseln sichtbar zu machen.
   - Ziel: Nutzt Schwellenwerte für Oberflächentemperaturen, um Hitzeinseln als Layer auf einer Karte darzustellen.

8. **Integration von Trinkwasserquellen**
   - Aufgabe: Überlagert die Karte mit Hitzeinseln mit den Positionen der Trinkwasserquellen.
   - Ziel: Identifiziert, welche Hitzeinseln aktuell keine ausreichende Versorgung durch öffentliche Trinkwasserquellen haben.

9. **Bevölkerungsdaten einbeziehen**
   - Aufgabe: Kombiniert Bevölkerungsdichte-Daten mit den bestehenden Karten zu Hitzeinseln und Trinkwasserquellen.
   - Ziel: Ermittelt, welche dicht besiedelten Gebiete mit Hitzeinseln unterversorgt sind.

10. **Populationsdichte kartieren**  
   - Wie kann man Bevölkerungsdichtekarten in das QGIS-Projekt integrieren?  
   - Welche Datenquellen für Bevölkerungszahlen sind für Berlin und Bochum verfügbar? Sind sie frei zugänglich?

11. **Analyse von Bevölkerungsgruppen**  
   - Wie unterscheiden sich die Bedürfnisse nach Trinkwasserstellen in verschiedenen Bevölkerungsgruppen (z. B. Alter, Mobilität)?  
   - Welche zusätzlichen Daten könnten helfen, solche Unterschiede zu analysieren?

12. **Zugänglichkeit bewerten**  
   - Wie weit sollte eine Person im Durchschnitt laufen müssen, um eine Trinkwasserstelle zu erreichen?  
   - Nutzt ein Routing-Tool, um durchschnittliche Gehzeiten zwischen Wohngebieten und den nächstgelegenen Trinkwasserstellen zu berechnen.

13. **Datenqualität prüfen**
   - Aufgabe: Prüft die Zuverlässigkeit der Trinkwasserquellen-Daten. Welche Quellen sind möglicherweise ungeeignet (z. B. Friedhofswasserstellen)?
   - Ziel: Erstellt eine bereinigte Version der Daten, die nur sichere öffentliche Trinkwasserstellen enthält.


---

## **Challenge Set 3: Fortgeschrittene Analysen und Visualisierungen (Advanced Level)**

14. **Bedarfsanalyse erstellen**
   - Aufgabe: Entwickelt eine Bedarfsanalyse für öffentliche Trinkwasserstellen basierend auf Hitzeinseln, Bevölkerungszahlen und bestehenden Quellen.
   - Ziel: Definiert Schwellenwerte (z. B. 1 Trinkstelle pro 1.000 Einwohner\*innen) und berechnet die Anzahl fehlender Trinkstellen pro Stadtteil.

15. **Multifaktorielle Analyse**  
    - Wie könnten Faktoren wie Grünflächen, Schatten oder Gebäudehöhen die Intensität von Hitzeinseln beeinflussen?  
    - Führt eine Analyse durch, die diese Faktoren in die Identifikation von Hitzeinseln einbezieht.

16. **Korrelationen untersuchen**  
    - Gibt es eine Korrelation zwischen Bevölkerungsdichte und der Anzahl vorhandener Trinkwasserquellen in einem Gebiet?  
    - Nutzt statistische Tools, um diese Beziehungen zu analysieren und zu visualisieren.

17. **Szenarien entwickeln**  
    - Wie würde sich der Bedarf an Trinkwasserstellen verändern, wenn die Bevölkerungszahl in einem Stadtteil um 20 % steigt?  
    - Simuliert ein solches Szenario und zeigt die Ergebnisse auf einer Karte.

18. **Optimierungsvorschläge entwickeln**
   - Aufgabe: Identifiziert potenzielle Standorte für neue Trinkwasserquellen, die die Versorgung in unterversorgten Hitzeinseln verbessern könnten.
   - Ziel: Erstellt eine priorisierte Liste und visualisiert die Standorte auf einer Karte.

19. **Erweiterte Visualisierungstechniken**
   - Aufgabe: Erstellt eine interaktive Karte, die Hitzeinseln, Trinkwasserquellen und Bevölkerungsdichte kombiniert.
   - Ziel: Nutzt Python (z. B. mit Folium) oder andere Tools, um die Ergebnisse dynamisch und ansprechend darzustellen.

20. **Zeitliche Analysen**  
   - Wie verändert sich die Lage und Intensität der Hitzeinseln zu verschiedenen Tages- oder Jahreszeiten?  
   - Welche Satellitendaten sind dafür am besten geeignet (z. B. Sentinel-3 für tägliche Messungen)?

21. **Clustering von Hitzeinseln**  
   - Welche Algorithmen (z. B. DBSCAN, K-Means) können verwendet werden, um Hitzeinseln in räumliche Cluster zu unterteilen?  
   - Wie beeinflusst die Wahl der Parameter (z. B. Clustergröße) die Ergebnisse?


22. **Interaktive Dashboards**  
    - Erstellt ein interaktives Dashboard, das Nutzer\*innen erlaubt, Daten zu Hitzeinseln, Trinkwasserquellen und Bevölkerungsdichte zu filtern und zu erkunden.  
    - Welche Tools wie Dash, Streamlit oder Tableau eignen sich hierfür?

23. **Heatmap erstellen**  
    - Erstellt eine Heatmap, die die Dichte der Trinkwasserquellen und die Intensität der Hitzeinseln kombiniert.  
    - Nutzt die Heatmap, um Gebiete mit hohem Bedarf an zusätzlichen Trinkwasserstellen zu identifizieren.

---

## **Challenge Set 4: Kreativität und Innovation**

24. **Daten aus der Zukunft simulieren**
   - Aufgabe: Simuliert ein Szenario, in dem durch den Klimawandel die Anzahl und Intensität der Hitzeinseln in Berlin zunimmt.
   - Ziel: Entwickelt eine Strategie, wie die Stadtverwaltung auf dieses Szenario reagieren sollte.

25. **Crowdsourcing-Daten einbinden**
   - Aufgabe: Entwickelt eine Methode, um fehlende oder ungenaue Daten zu Trinkwasserquellen durch Crowdsourcing (z. B. MapRoulette) zu verbessern.
   - Ziel: Erstellt ein Konzept, wie Bürger\*innen aktiv an der Datenverbesserung teilnehmen können.

26. **Mission Trinkbrunnen unterstützen**
   - Aufgabe: Entwickelt ein Modell, das die beste Verteilung von Trinkbrunnen in Deutschland basierend auf Bevölkerungsdichte und Hitzeinseln vorschlägt.
   - Ziel: Präsentiert eure Lösung in Form eines Dashboards oder einer Story Map.

27. **KI-Modell trainieren**  
    - Entwickelt ein Machine-Learning-Modell, das basierend auf Satellitendaten und Bevölkerungsdichte vorhersagt, wo in Zukunft neue Hitzeinseln entstehen könnten.  
    - Welche Daten und Algorithmen wären dafür notwendig?

28. **Vorhersagemodell für Wasserbedarf**  
    - Entwickelt ein Modell, das den zukünftigen Wasserbedarf in städtischen Gebieten basierend auf Klimaprognosen und Bevölkerungswachstum vorhersagt.  
    - Wie könnten diese Prognosen in die Planung von Trinkwasserinfrastruktur integriert werden?

29. **Mobilitätsfreundliche Trinkwasserstellen**  
    - Plant ein Netzwerk von Trinkwasserstellen, das nicht nur stationäre Brunnen, sondern auch mobile Lösungen (z. B. Trinkwasserwagen) beinhaltet.  
    - Welche Daten würden helfen, die idealen Routen und Standorte für mobile Lösungen zu planen?

30. **Klimagerechtigkeit berücksichtigen**  
    - Analysiert, wie sozial benachteiligte Stadtteile im Vergleich zu wohlhabenderen Vierteln mit Trinkwasserquellen ausgestattet sind.  
    - Entwickelt eine Strategie, um diese Ungleichheit zu beheben.

31. **Crowdsourcing-Plattform entwickeln**  
    - Entwickelt ein Konzept für eine Plattform, die Bürger\*innen ermöglicht, neue Trinkwasserquellen zu melden oder bestehende zu bewerten.  
    - Welche Features sollte die Plattform enthalten, und wie könnte sie umgesetzt werden?

---

## **Hinweis**
Die Challenges sind so gestaltet, dass sie schrittweise aufeinander aufbauen, aber auch unabhängig voneinander bearbeitet werden können. Ihr könnt eure eigenen kreativen Ansätze einbringen, um die gestellten Probleme zu lösen. Ihr könnt euch auch einfach die Fragen Raussuchen die ihr spannend und machbar findet und müsst euch an keine Vorgaben halten. Viel Erfolg bei der Umsetzung!