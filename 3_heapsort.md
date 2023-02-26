# Heapsort


## Welchen Nutzen stellt der Heapsort-Algorithmus dar?
Sortierung von numerischen Werten

## Wie arbeitet der Heapsort-Algorithmus?
in zwei Phasen

## Wie funktioniert dieser Algorithmus?
1. Phase: Zu sortierende Array wird in Max-Heap umsortiert
2. Phase: Größte Element wird aus Heap entfernt, indem man es mit dem Knoten an der letzten Position tauscht und nicht mehr betrachtet
	- danach wird aus verbleibenden Elementen neuer Max-Heap erstellt und das größte Element wird immer wieder aus dem Heap entfernt
	- läuft solange ab, bis das Array letztendlich sortiert vorliegt

## Was ist ein Heap?
ein binärer Baum (jeder Knoten bis zu zwei Kindknoten)

## Aus was wird ein Heap gebildet?
aus einem Array, dass es zu sortieren gilt

## Was versteht man unter einem Max-Heap?
- Elternknoten sind stets größer als Kindknoten
- größte Element stellt somit Wurzel der Baumstruktur dar
	- und in Array das erste Element

## Was versteht man unter einem Min-Heap?
- Elternknoten stets kleiner als Kindknoten
- kleinste Element stellt Wurzel in Baumstruktur dar
	- und ist in Array das erste Element

## Wie stellt man einen Max-Heap für die zweite Phase des Heapsort-Algorithmus dar?
durch den Heapify Prozess

## Was versteht man grundlegend hinter dem Heapify Prozess?
der Prozess der Erstellung einer Heap-Datenstruktur aus einem Binärbaum, der durch ein Array dargestellt wird

## Für was wird Heapify verwendet?
um einen Min-Heap oder Max-Heap zu erstellen

## Wie wird der Heapify Prozess umgesetzt?
indem die Heapify-Methode mehrmals aufgerufen wird

## Wie lautet die Heapify-Bedingung, wenn man einen Max-Heap erstellen will?
ausgehend vom unterstem Elternknoten wird überprüft, ob der Elternknoten größer als die Kindknoten sind

## Wie stellt man eine Heapify-Bedingung wieder her?
das größere Kindelement wird mit dem Elternknoten vertauscht

## Was ist die Grundlage des Heapsort-Algorithmus?
die Heapify-Bedingung

## Wie lässt sich der Vorgang umsetzen?
iterativ und rekursiv

