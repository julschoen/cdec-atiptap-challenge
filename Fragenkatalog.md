# Fragenkatalog A TipTap Challenge

## **Lets get Started: Einstieg in Daten und Tools (Beginner Level)**

1. **Identifikation von Trinkwasserquellen**
   - Aufgabe: Beschafft die Daten zu Trinkwasserquellen für Berlin und Versucht sie zu visualisieren.
   - Ziel: Daten werden heruntergeladen, geeignet formatiert und mit einer gewählten Methode (z.B. QGIS oder Python) visualisiert.

2. **Satellitendaten herunterladen**
   - Aufgabe: Ladet die Satellitendaten zur Erkennung von Hitzeinseln herunter und visualisiert diese.
   - Ziel: Die Daten werden mit Methode der Wahl visualiert und evtl schon mit den Trinkwasserquellen kombiniert.

3. **Bevölkerungsdaten herunterladen**
   - Aufgabe: Ladet die Bevölkerungsdaten für Berlin herunter und visualisiert diese.
   - Ziel: Die Daten werden mit Methode der Wahl visualiert und evtl schon mit den Trinkwasserquellen und Hitzeinseln kombiniert.

4. **Datenformat und Vorbereitung**
   - Aufgabe: Konvertiert die heruntergeladenen Daten so, das ihr sie mit einander kombinieren könnt und versucht ob ihr sie zusammen visualisieren könnt.
   - Ziel: Saubere, strukturierte und kombinierbare Datenbasis, die für weitere Analysen geeignet ist.
  
5. **Datenqualität prüfen**
   - Aufgabe: Prüft die Zuverlässigkeit der Trinkwasserquellen-Daten. Welche Quellen sind möglicherweise ungeeignet (z. B. Friedhofswasserstellen) oder gibt es Duplikate?
   - Ziel: Eine bereinigte Version der Daten, die nur sichere öffentliche Trinkwasserstellen enthält.
  
6. **Erste berrechnungen**
   - Aufgabe: Bei wem aus eurem Team, die aus Berlin kommen, sind die meisten Trinkorte in der Nähe? 
   - Ziel: Evtl radius definieren in dem geschaut wird, manuelles oder automatisiertes zählen der Trinkorte, erstes erkunden von den Daten.

---

## **Turn up the heat: Datenaufbereitung und erste Analysen zu Hitzeinseln (Intermediate Level)**

7. **Hitzeinseln definieren**  
   - Aufgabe: Wie definiert ihr an hand von den gesammelten Daten Hitzeinseln?
   - Ziel: Einfache definition von Hitzeinseln. E.g. X grad über durchschnitts Temperatur oder so. Kann recht frei definiert sein.

8. **Hitzeinseln kartieren**
   - Aufgabe: Analysiert Satellitendaten, um städtische Hitzeinseln sichtbar zu machen.
   - Ziel: Vorheriges Kriterium wird genutzt um Hitzeinseln darzustellen.

9. **Integration von Trinkwasserquellen**
   - Aufgabe: Überlagert die Karte mit Hitzeinseln mit den Positionen der Trinkwasserquellen und schaut wie die Überlagerung ist.
   - Ziel: Welche Hitzeinseln haben aktuell keine ausreichende Versorgung durch öffentliche Trinkwasserquellen.

---

## **Look at all the people: Datenaufbereitung und erste Analysen zu Besiedlung (Intermediate Level)**

10. **Bevölkerungsdaten einbeziehen**
   - Aufgabe: Kombiniert Bevölkerungsdichte-Daten mit den bestehenden Karten zu Hitzeinseln (nur wenn ihr sie habt) und Trinkwasserquellen.
   - Ziel: Ermittelt, welche dicht besiedelten Gebiete mit Hitzeinseln unterversorgt sind.

11. **Abdeckung erkunden**
   - Aufgabe: Erkundet wie die verteilung der Trinkwasserstellen mit Bezug auf die Einwohner\*innen Zahlen ist. Welche Stadtteile haben vielleicht eine sehr hohe oder sehr niedrige Abdeckung?
   - Ziel: Erkundung der Wasserort verteilung im verhältniss zu Einwohner\*innen.

12. **Analyse von Bevölkerungsgruppen**  
   - Aufgabe: Wie unterscheiden sich die Bedürfnisse nach Trinkwasserstellen in verschiedenen Bevölkerungsgruppen (z. B. Alter, Mobilität)? Findet ihr zusätzliche Daten um den Bedarf in eure Analyse mit einzubeziehen?
   - Ziel: Offen

13. **Zugänglichkeit bewerten**  
   - Aufgabe: Wie weit sollte eine Person im Durchschnitt laufen müssen, um eine Trinkwasserstelle zu erreichen? Wie ist es gerade? Wo ist die Distanz besonders hoch oder niedrig?
   - Ziel: Gehdistanzen zu nächstgelegenen Trinkwasserstellen zu berechnen, analysieren.


---

## **Lets get technical: Fortgeschrittene Analysen und Visualisierungen (Advanced Level)**

14. **Bedarfsanalyse erstellen**
   - Aufgabe: Entwickelt eine Bedarfsanalyse für öffentliche Trinkwasserstellen basierend auf Hitzeinseln (und/oder) Bevölkerungszahlen und bestehenden Quellen.
   - Ziel: Datenbasierte Bedarfsanalyse.

15. **Multifaktorielle Analyse**  
    - Aufgabe: Wie könnten Faktoren wie Grünflächen, Schatten oder Gebäudehöhen die Intensität von Hitzeinseln beeinflussen? Findet ihr Daten die ihr mit einbeziehen könnt? Wie wirkt sich das auf die Trinkwasserquellen aus?
    - Ziel: Analyse die gewählte zusätzliche Faktoren einbezieht.

16. **Korrelationen untersuchen**  
    - Aufgabe: Gibt es eine Korrelation zwischen Bevölkerungsdichte und der Anzahl vorhandener Trinkwasserquellen in einem Gebiet?  
    - Ziel: Statistische Tools benutzen, um diese Beziehungen zu analysieren und zu visualisieren.

17. **Optimierungsvorschläge entwickeln**
   - Aufgabe: Identifiziert potenzielle Standorte für neue Trinkwasserquellen, die die Versorgung mit bezug auf Hitzeinseln (und/oder) Bevölkerungsdichte verbessern könnten.
   - Ziel: Selbsterklärend

18. **Erweiterte Visualisierungstechniken**
   - Aufgabe: Erstellt eine interaktive Karte oder Dashboard, die Hitzeinseln, Trinkwasserquellen und/oder Bevölkerungsdichte kombiniert.
   - Ziel: Nutzt Tools, um die Ergebnisse dynamisch und ansprechend darzustellen.

19. **Clustering von Hitzeinseln**  
   - Aufgabe: Verwendet Algorithmen (z. B. DBSCAN, K-Means, ...) um grenzwerte für Hitzeinseln und Bevölkerungsdichte automatisch zu wählen.
   - Ziel: Wahl eines geeigneten Algos und Hyperparameter, und analyse der Resultate.

20. **Heatmap erstellen**  
    - Aufgabe: Erstellt eine Heatmap, die die Dichte der Trinkwasserquellen und die Intensität der Hitzeinseln (und/oder) Bevölkerungsdichte kombiniert.  
    - Ziel: Nutzt die Heatmap, um Gebiete mit hohem Bedarf an zusätzlichen Trinkwasserstellen zu identifizieren.

---

## **What do we want: Kreativität und Innovation**

21. **Daten aus der Zukunft simulieren**
   - Aufgabe: Simuliert ein Szenario, in dem durch den Klimawandel die Anzahl und Intensität der Hitzeinseln in Berlin zunimmt.
   - Ziel: Entwickelt eine Strategie, wie die Stadtverwaltung auf dieses Szenario reagieren sollte.

22. **Daten Verbessern für Alle**
   - Aufgabe: Entwickelt eine Methode oder Kampagne, um fehlende oder ungenaue Daten zu Trinkwasserquellen durch zu verbessern.

23. **Mission Trinkbrunnen unterstützen**
   - Aufgabe: Entwickelt ein Modell oder eine Strategie, das die beste Verteilung von Trinkbrunnen in Berlin (oder sogar Deutschland) basierend auf Bevölkerungsdichte und/oder Hitzeinseln vorschlägt.

24. **KI-Modell trainieren**  
    - Aufgabe: Könnt ihr ein Machine-Learning-Modell entwickeln, das vorhersagt, wo in Zukunft neue Trinkwasserquellen gebraucht werden?  

25. **Vorhersagemodell für Wasserbedarf**  
    - Aufgabe: Wie wird sich der zukünftigen Wasserbedarf in städtischen Gebieten basierend auf Klimaprognosen und/oder Bevölkerungswachstum entwickeln? Welchen einfluss hat das auf Trinkwasserquellen? Gibt es unterschiede in verschiedenen Stadtteilen?  

26. **Mobilitätsfreundliche Trinkwasserstellen**  
    - Aufgabe: Plant ein Netzwerk von Trinkwasserstellen, das nicht nur stationäre Brunnen, sondern auch mobile Lösungen (z. B. Trinkwasserwagen) beinhaltet.  

27. **Klimagerechtigkeit berücksichtigen**  
    - Aufgabe: Analysiert, wie sozial benachteiligte Stadtteile im Vergleich zu wohlhabenderen Vierteln mit Trinkwasserquellen ausgestattet sind.  

28. **Crowdsourcing-Plattform entwickeln**  
    - Aufgabe: Entwickelt ein Konzept für eine Plattform, die Bürger\*innen ermöglicht, neue Trinkwasserquellen zu melden oder bestehende zu bewerten.  

---

## **Hinweis**
Die Challenges sind so gestaltet, dass sie schrittweise aufeinander aufbauen, aber auch unabhängig voneinander bearbeitet werden können. Ihr könnt eure eigenen kreativen Ansätze einbringen, um die gestellten Probleme zu lösen. Ihr könnt euch auch einfach die Fragen Raussuchen die ihr spannend und machbar findet und müsst euch an keine Vorgaben halten. Lasst eurer kreativität Freien lauf die Fragen sind nur eine Idee wenn ihr irgendwas anderes an den Daten spannender findet könnt ihr auch das Erkunden! Viel Erfolg bei der Umsetzung!
