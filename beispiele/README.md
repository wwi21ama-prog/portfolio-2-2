# Beispiel-Projekte

In diesem Ordner gibt es Beispielprojekte, die das Datenformat verdeutlichen sollen und
die als Testdaten genommen werden können.

Bei den Beschreibungen der Beispiele werden hier auch Anforderungen definiert.
Diese beschreiben, was die Analyse-Software für das jeweilige Projekt leisten soll.
D.h. diese Anforderungen sind keine harten Anforderungen, sondern sie sollen eine
Intuition geben, was gebraucht wird. Insofern sind sie eher als User-Stories zu sehen.

## Einfache To-Do-Liste

Einfache Aufgabenliste mit ein paar Aufgaben, für die abgehakt werden kann, ob sie erledigt sind.

* Startdatei: [todolist_einfach.md](todolist_einfach/todolist_einfach.md)
* Anforderungen:
  * Filterung der Liste nach erledigten / unerledigten Aufgaben

## TO-DO-Liste mit Deadlines

Aufgabenliste mit Aufgaben, inklusive Erledigt-Checkbox und Fälligkeitsdaten.

* Startdatei: [todolist_deadlines.md](todolist_deadlines/todolist_deadlines.md)
* Anforderungen:
  * Filterung der Liste nach erledigten / unerledigten Aufgaben
  * Fitlerung der Liste nach Aufgaben, die in den nächsten X Tagen anstehen
  * Filterung der Liste nach Aufgaben, deren Datum schon überschritten ist
  * Sortierte Anzeige nach Deadlines

## Bastelprojekt mit Unteraufgaben

Ein kleines Projekt für die Herstellung eines Möbelstücks, das aus verschiedenen
Teilprojekten besteht.

* Startdatei: [moebelbau.md](bastelprojekt_teilprojekte/moebelbau.md)
* Anforderungen:
  * Anzeige aller Bau-Aufgaben, die in den verschiedenen Teilprojekten definiert sind
    * Siehe dazu das Tag `#bau-aufgaben` in den Dateien
  * Anzeige aller Einkaufs-Aufgaben
    * Siehe dazu das Tag `#einkaufen` in den Dateien
    * Doppelte Einträge aus mehreren Dateien sollen zusammengefasst werden.
  * Anzeige der nicht-getaggten Vorbereitungsaufgaben
  * Anzeige aller Aufgaben, sortiert nach Tag
  * Filterung nach erledigt / nicht erledigt
