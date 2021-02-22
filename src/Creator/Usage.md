# Anleitung
## Installation
Herunterladen und in einen Ordner verschieben.
## Nutzung
![](/docs/Creator.PNG)

Die 5x5 Checkboxen stellen die Matrix da. 
In dieser werden die LEDs ausgewählt.
Danach kann mit dem Button die Matrix exportiert werden.
Diese Befehlszeile, wie diese
`pos.push([[0,0],[3,0],[0,1],[3,1],[0,2],[3,2],[0,3],[3,3],[1,4],[2,4]])`
muss in die Datei custom.ts zu den anderen Zeilen hinzugefügt werden und das gegensätzliche Zeichen (Funktionsinput) muss in `e` hinzugefügt werden (z.B. `e.push("U");`). Einfügbar ab [52](https://github.com/RaphaelKlug/demonstrationInformatik/blob/520e7b2f991df09d9fc8df745832a00dcf19ad2b/src/roh/custom.ts#L52) bis [124](https://github.com/RaphaelKlug/demonstrationInformatik/blob/520e7b2f991df09d9fc8df745832a00dcf19ad2b/src/roh/custom.ts#L124) der Roh Datei (bei jedem einfügen erhöht sich die 124). Am besten noch das Zeichen wenn möglich als Kommentar hinter `pos.push(...);`
## Weiterführende Links
Genaueres in der [custom.ts](/src/roh/custom.ts) Datei
