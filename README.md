# GraphsAreFun

Was ist eine Adjazenzmatrix?
Eine Adjazenzmatrix (manchmal auch Nachbarschaftsmatrix) eines Graphen ist eine Matrix, die speichert,
welche Knoten des Graphen durch eine Kante verbunden sind. 
Sie besitzt für jeden Knoten eine Zeile und eine Spalte, woraus sich für n Knoten eine n x n-Matrix ergibt. 
Ein Eintrag in der i-ten Zeile und j-ten Spalte gibt hierbei an, ob eine Kante von dem i-ten zu dem j-ten Knoten führt. 
Steht an dieser Stelle eine 0, ist keine Kante vorhanden – eine 1 gibt an, dass eine Kante existiert.

Was ist eine Pfadmatrix?
Während die Adjazenzmatrix angibt welche Knoten <direkt> über eine Kante miteinander verbunden sind,
stellt die Pfadmatrix alle mit Knoten A verbundenen Knoten dar. Ist Knoten A über B mit D verbunden,
so sind die Felder [A,D] und [D,A] in der Pfadmatrix 1. Nicht vorhandene Verbindungen werden mit einer 0 dargestellt.

Was ist eine Distanzmatrix?
Die Distanzmatrix ist in der Mathematik eine quadratische Matrix, die die Abstände zwischen Punkten einer Menge angibt.
In der Chemie zeigt sie die Anzahl der Bindungen zwischen den Atomen eines Moleküls an.

Wie benutze ich GraphsAreFun?
Zunächst muss man die Anzahl der Knoten / die Größe der Adjazenzmatrix wählen. Dann sollte man, sich einen Graphen aufzeichnen.
Das heißt, 2-10 Punkte/Knoten auf ein Blatt Papier zeichnen und diese beliebig verbinden. Dabei kann ein Knoten mit mehreren anderen 
Knoten verbunden sein. Als nächstes beschriftet man die Knoten mit Buchstaben von A-J beginnend mit A. Der letzte Schritt besteht darin,
die Adjazenzmatrix des Graphen in das Programm einzugeben. Ist Knoten A mit Knoten C verbunden, so sind die Felder [A,C] und [C,A] = 1.

Welche Features hat GraphsAreFun?
-Erstellen einer .dat des aktuellen Graphen
-Laden einer .dat Datei
-Symmetrisch gegenüberliegende Buttons werden bei Knopfdruck ebenfalls "abgefeuert"
-Rückgängig machen eines Klicks
-Wiederherstellen eines rückgängig gemachten Klicks
-Diverse Shortcuts
-Anzeigen der Kanten/Verbindungen in der unteren Sektion des Programms
-Berechnung von Pfad und Distanzmatrix
