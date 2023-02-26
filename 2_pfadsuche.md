# Pfadsuche

## Welchen Nutzen schaffen Algorithmen zur Pfadsuche?
Knoten in einem Graphen zu suchen bzw. letztendlich zu finden

## Mit welchen Algorithmen lassen sich Pfade eines Graphen durchsuchen?
- Tiefensuche
- Dijkstra-Algorithmus
- A*-Algorithmus
- Breitensuche
- Heuristik

## Was versteht man hinter der Tiefensuche?
- hat ein Knoten, den man besucht, noch unentdeckte Nachbarn, so geht man zum ersten solchen Nachbarn, den man findet 
- von dort aus wird wieder in die "Tiefe" gesucht, falls es noch einen unentdeckten Nachbarn des Nachbarn gibt

## Was versteht man dahingegen unter der Breitensuche?
- einen Algorithmus, der die kürzesten Wege von einem gegebene Startknoten zu allen anderen Knoten, in Bezug auf die in den Pfaden enthaltenen Kanten, findet
- zuerst werden alle Kindknoten des aktuellen Knotens durchlaufen, bevor weiter in die Tiefe gegangen wird

## Wobei hilft der Dijkstra-Algorithmus?
den kürzesten bzw. kostengünstigsten Weg in einem Graphen zu berechnen

## Welche Voraussetzungen bringt der Dijsktra-Algorithmus mit sich?
- gerichteter Graph
- gewichteter Graph
- Kantengewichte des Graphen nicht negativ

## Wie funktioniert der Dijkstra-Algorithmus?
- Tabelle als Hilfe zur Durchführung des Algorithmus anlegen
- Warteschlange erstellen, in denen zu besuchende Knoten warten
- im allgemeinen Knoten aus Warteschlange mit geringsten Kosten nehmen
- von diesem Knoten direkte Nachfolger betrachten und je nachdem Tabelle mit Kosten und Vorgänger aktualisieren
- solange durchführen bis Warteschlange leer

## Was versteht man hinter dem A*-Algorithmus?
eine Verallgemeinerung und Erweiterung des Dijkstra-Algorithmus

## Wie funktioniert der A*-Algorithmus?
- Grundprinzip analog zu Dijsktra-Algorithmus
- zusätzlich dazu Auswahl des nächsten Knotens, der am vielversprechendsten scheint
