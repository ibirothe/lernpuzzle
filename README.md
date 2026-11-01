# Das Pferdehof-Puzzle 🐴

Ein kindgerechtes Lernpuzzle mit den Modi **Rechnen** und **Lesen**. Mit jeder richtigen Lösung wird ein Teil eines Pferdebildes sichtbar.

## Entwicklungsstand auf `dev`

- **Modusauswahl:** Nach dem Start kann man zwischen **Rechnen** und **Lesen** wählen.
- **Rechnen:** Das bisherige Spiel mit allen Einstellungen (8/16/30 Teile, Leicht/Mittel/Schwer, Plus/Minus/Beides, drei Pferdebildern) bleibt vollständig erhalten.
- **Lesen:** Eigener Bereich und Navigation sind vorbereitet. **Die Leseaufgaben sind noch nicht implementiert.** Wortmaterial und Aufgabenmechanik werden als Nächstes gemeinsam festgelegt.
- **Deployment:** Die Entwicklung findet auf `dev` statt. GitHub Pages auf `main` bleibt bis zum Merge unverändert.

## So wird gespielt

1. Zunächst **Rechnen** auswählen; anschließend vier Einstellungen wählen:
   - **Puzzleteile:** 8, 16 oder 30
   - **Schwierigkeit:** Leicht, Mittel oder Schwer
   - **Rechenarten:** Plus, Minus oder beides (bei „Beides“ möglichst gleich viele Aufgaben jeder Art)
   - **Bild:** Pferdehof, Ponywiese oder Reitausflug
2. **„Puzzle starten!“** drücken.
3. Ein Puzzleteil mit einer Rechenaufgabe antippen.
4. Die Antwort über die großen Zahlentasten von **0 bis 12** auswählen.
5. **Richtig:** Das Puzzleteil dreht sich automatisch um und zeigt mehr vom Bild. **Falsch:** Die gleiche Aufgabe darf beliebig oft versucht werden.
6. Nach dem letzten Teil erscheint die Erfolgsmeldung. Mit **„Nochmal spielen“** gibt es mit denselben Einstellungen eine neue Runde; mit **„Anderes Puzzle wählen“** geht es zurück zur Auswahl. Auch während des Spiels führt **„Auswahl“** zurück.

## Schwierigkeitsstufen

- **Leicht:** Aufgaben mit Zahlen und Ergebnissen bis **6**
- **Mittel:** Aufgaben mit Zahlen und Ergebnissen bis **10**
- **Schwer:** Aufgaben mit Zahlen und Ergebnissen bis **12**

Alle Rechnungen verwenden ganze Zahlen; Minusaufgaben haben **keine negativen Ergebnisse**. Jede Aufgabe hat ein Ergebnis von 0 bis 12. Plus und Minus sind auf alle drei Schwierigkeitsstufen begrenzt. Das ursprüngliche Spielprinzip – rechnen, automatisch umdrehen, bei Fehler erneut versuchen – bleibt erhalten.

## Starten

`index.html` herunterladen und lokal in einem aktuellen Browser öffnen. Das Spiel ist auch **offline** spielbar: HTML, CSS, JavaScript und alle drei SVG-Bilder sind in derselben Datei enthalten. Es benötigt keine Anmeldung und keine externen Bibliotheken.

Touch, Maus und Tastatur werden unterstützt. Animationen beachten die Systemeinstellung „Bewegung reduzieren“.

Entstanden nach der Idee einer sechsjährigen Spiele-Erfinderin.
