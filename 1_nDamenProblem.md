# N-Damen Problem


## Was versteht man hinter dem Damenproblem?
eine schachmathematische Aufgabe


## Welche Aufgabe soll gelöst werden?
n Damen sollen auf einem nxn großen Schachbrett so aufgestellt werden, dass keine zwei Damen einander gemäß ihren in den Schachregeln definierten Zugmöglichkeiten schlagen können


## Was bedeutet dies konkret für die Aufstellung der Damen?
zwei Damen dürfen nicht auf derselben Reihe, Linie oder Diagonale stehen


## Welche Frage steht im Mittelpunkt beim Damenproblem?
die Frage nach der Anzahl der möglichen Lösungen


## Was versteht man hinter dem klassischen Damenproblem?
8 Damen auf ein 8X8-Brett anzuordnen


## Wie viele verschiedene Lösungen hat das klassische Damenproblem?
92


## Was versteht man hinter dem verallgemeinerten Damenproblem?
n Damen auf einem Brett von nxn Feldern zu positionieren, dass sie einander nicht diagonal, senkrecht und waagerecht gegenüber stehen


## Welche Algorithmen zur Lösungssuche existieren?
- naiver Brute-Force-Algorithmus
- effiziente Brute-Force-Algorithmus
- rekursives Backtracking

## Was versteht man hinter dem naiven Brute-Force-Algorithmus?
Durchprobieren aller möglichen Positionierungen der acht Damen und dabei alle Stellungen ausfiltern, in denen jeweils zwei Damen einander schlagen können

## Was versteht man hinter dem effizienteren Brute-Force-Algorithmus?
analog zu naiven Brute-Force-Algorithmus nur das beim effizienteren Brute-Force-Algorithmus nur eine Dame nacheinander in jeder Reihe platziert wird

## Was versteht man hinter dem rekursiven Backtracking?
# noch ergänzen

## Was versteht man generell hinter dem Begriff _Backtracking_?
das Zurückverfolgen im Rahmen einer baumartigen Lösungssuche von einer Sackgasse im Sinne der Problemlösung zu einer vorhergehenden Stelle im Lösungsbaum
von dieser vorhergehenden Stelle wir ein neuer Lösungsversuch gestartet