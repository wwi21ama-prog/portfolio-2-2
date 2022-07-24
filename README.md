# Markdown-Basiertes Projektmanagement (Portfolioprüfung)

Bei diesm Projekt geht es darum, ein Projektmanagement-Konzept umzusetzen,
bei dem die Projekte, Aufgaben, Deadlines etc. in einer Art Wiki mittels
Markdown-Dateien verwaltet werden.

Ziel ist es, ein einfaches Projektmanagement-System zu haben, das ohne Datenbank
auskommt und menschenlesbar in Textdateien gespeichert wird.
Zunächst folgt eine kurze Beschreibung des Datenformats.
Die Aufgabe ist, für dieses Datenformat eine Software zu schreiben,
die es durchsuchen und eine Zusammenfassung der darin formulierten Aufgaben
inkl. Terminen etc. produzieren kann.

## Aufbau / Beschreibung der Projekte

Ein *Projekt* besteht jeweils aus einer Markdown-Datei.
Eine solche Projekt-Datei enthält die Beschreibung des Projekts,
eine oder mehrere Listen von Aufgaben und sie kann auf andere Projekte
verlinken, die dann in eigenen Dateien stehen.
Dies können Unterprojekte sein, oder auch unabhängige andere Projekte,
zu denen irgendeine Art von Beziehung besteht.

In jeder Markdown-Datei soll es möglich sein, Aufgaben zu formulieren und
für diese Aufgaben verschiedene Metadaten zu verwalten. Beispiele:

* Termin für die Aufgabe
* Markieren, ob die Aufgabe erledigt ist
* Fortschrittsangabe in Prozent
* Abschätzung für die Zeit bzw. den Aufwand der Aufgabe
* Bisher aufgewendete Zeit

Außerdem soll es möglich sein, den einzelnen Projekten Tags zuzuweisen, um sie
zu kategorisieren.

## Anforderungen an die Analysesoftware für das Datenformat

Es soll eine Software geschrieben werden, die - ausgehend von einer Startseite -
die Daten eines Projekts durchsuchen und Informationen dazu anzeigen kann.
Beispiele:

* Auflistung aller Teilprojekte
* Auflistung aller einzelnen Aufgaben, die im Projekt und den Teilprojekten
  definiert werden
* Auflistung aller unfertigen Aufgaben
* Auflistung aller Aufgaben, die bis zu einem bestimmten Datum erledigt werden müssen
* Filtern der Teilprojekte/Aufgaben nach Tags
