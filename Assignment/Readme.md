Ziel des Projekts:
Ziel des Projekts ist es, einen Blick hinter die Zahlen und Statistiken im Fussball zu werfen. 
Dafür habe ich mir zwei Datensätze aus der Englischen Premier League der Saison 23/24 herangezogen.
Ich wollte herausfinden, welche versteckten Erkenntnisse in den Zahlen stecken bzw. ob man 
interessante Dinge herauslesen kann.

Verwendete Pakete:
Verwendet habe ich für die Analysen:
- Pandas
- Numpy
- Path
- Plotly
- Seaborn
- matplotlib

Datensatz Beschreibung:
Datensatz 1 (matches.csv) - Dies ist eine CSV Datei, die alle Spiele der Saison 23/24 enthalten hat. Die Spalten inkludierten Informationen wie: Spieltag, Uhrzeit, Heimmannschaft, Auswärtsmannschaft, Tore , erwartete Tore uvm. Dies bildete eine gute Grundlage, um einen Blick auf die Spiele zu werfen und Analysen durchzuführen wie z.B. Wer hatte die beste Chancenverwertung? Welches Team hätte eigentlich besser performen sollen etc. 
Datensatz 2: (premier-player-23-24.csv) - diese Datei enhält alle Spieler und deren individuelle Statistiken. (dies umfasst z.B. Tore, Vorlagen, Karten, Spielminuten uvw.) Somit hatte ich am Ende zwei zusammengehörige Datensätze aus zwei Perspektiven, die ich in einem Case auch miteinander mergen konnte. Das gab mir die Möglichkeit, die Saison genauer zu analysieren.


Verarbeitungsschritte:
- Nach dem reinladen habe ich mit dem Bearbeitung der Datensätze begonnen. Bei "matches.csv" musste ich einige Schritte vornehmen: unter anderem musste ich Duplikate entfernen (da jedes Spiel doppelt im Datensatz enthalten war), Team-Namen auf einen gemeinsamen Nenner bringen und aber auch irrelevante Spalten entfernen. 
- Beim zweiten Datensatz ("premier-player-23-24.csv") musste ich weniger Bereinigungen durchführen. Hier musste ich die Spalte "Nation" ausbessern, da in dieser das Land doppelt enthalten war. Außerdem musste ich auch Duplikate entfernen, da einige Spieler doppelt enthalten waren - das betraf vor allem Spieler, die während der Saison innerhalb der Premier League gewechselt sind.


