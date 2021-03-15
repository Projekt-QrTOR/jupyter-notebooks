# Projekt QrTOR

Dieses Repository enthält eine ausführliche Erläuterung des "Supersingular Isogeny Diffie Hellman" Protokolls und seiner mathematischen Grundlage.
Zudem wird die Algorithmik des SIDHforJ im Detail besprochen und erklärt.
Das Repository enthält dabei 4 Jupyter-Notebooks.
Diese können dabei heruntergeladen und lokal abgespielt werden oder direkt auf der Github-Seite betrachtet werden (Für letzteres klicken Sie bitte einfach auf den Dateinamen im obigen Menü. Eventuelle Ladefehler lassen sich oftmals durch ein Neuladen der Seite beheben).

Zum besten Verständnis sollten die Notebooks in folgender Reihenfolge gelesen werden:
- 1. Grundlagen: Dieses Notebook erklärt alle Grundlagen, die zum Verständnis des SIDH notwendig sind. So werden zum Beispiel elliptische Kurven, der projektive Raum und Montgomerykurven erläutert
- 2. Theorie_SIDH: Dieses Notebook erklärt die spezifische Mathematik hinter dem SIDH. Speziell wird hier auf Isogenien und deren Berechnung eingegangen
- 3. SIDHforJ: Dieses Notebook implementiert die gesammte Kernlogik des SIDHforJ und erklärt diese im Detail. Hier wird zudem auf die zahlreichen Optimierungen des SIDHforJ eingegangen
- 4. Shors-Algorithmus: Dieses Notebook erklärt den Shor's Quantenalgorithmus und zeigt wie sich dieser zum Brechen eines Kryptosystens einsetzen lässt

&copy; 2021, Linus Meierhöfer