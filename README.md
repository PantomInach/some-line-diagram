# some-line-diagram

Dieses kleine Projekt wurde in Zusammenarbeit mit [johnzoki](https://github.com/johnzoki) designet.
Hier wird ein Diagramm erzeugt, welches auf artistischen Weise Datenwerte als Linien auf verschiedenen Punkte darstellt.

## How to use 
Es werden drei Dateien gebraucht, die alle Daten enthalten.
1. `s-h.xlsx`: Enthält eine Distanz in Metern in der dritten Spalte und eine Höhe in der vierten. Damit wird der Basisgraph (schwarz) erstellt.
2. `Acc.csv`: Die erste Spalte sollte einn Zeit in Sekunden enthalten. In der fünften Spalte sind die Werte, auf denen die Steigung der Linien basiert.
3. `gps.xls`: Hier wird `Acc.csv` und `s-h.xlsx` verknüpft. Dafür sollte in der ersten Spalte die Zeit und in der achten Spalte die Distanz stehen.
Es ist nicht nötig, dass die Werte alle genau übereinstimmen bei der Zeit und Distanz, da nächstliegenden Werte genommen werden.

Anschließend sollte das Notebook evaluiert werden.

## Acknowledgements
Die Daten `s-h.xlsx`, `Acc.csv`, `gps.xls` wurden von [johnzoki](https://github.com/johnzoki) zur Verfügung gestellt. Darüber hinaus war [johnzoki](https://github.com/johnzoki) für das Design verantwortlich. Währendessen [PantomInach](https://github.com/PantomInach) für die Umsetzung in Mathematica zuständig war.
