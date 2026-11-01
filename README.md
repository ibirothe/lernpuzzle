# Das Pferde-Puzzle 🐴

Ein kinderfreundliches Lernpuzzle mit zwei Modi: **Rechnen** und **Lesen**. Jede richtig beantwortete Aufgabe deckt ein Teil eines ausgewählten Pferdebildes auf.

## Spielstart

Beim Öffnen zuerst **Rechnen** oder **Lesen** wählen. Beide Modi besitzen eigene Einstellungen für **8, 16 oder 30 Puzzleteile**, **Leicht / Mittel / Schwer** und eines von drei Bildern: **Pferdehof**, **Ponywiese**, **Reitausflug**.

### Rechnen

Die bestehende Rechenlogik und die Plus-/Minus-Auswahl bleiben unverändert:

- **Leicht:** Zahlen bis 6
- **Mittel:** Zahlen bis 10
- **Schwer:** Zahlen bis 12
- Rechenarten: **Plus**, **Minus** oder **beides**.
- Antippen eines Puzzleteils öffnet die Aufgabe. Eine der Antwortzahlen 0–12 ist richtig, Fehler können wiederholt werden.

### Lesen

Jedes Puzzleteil zeigt ein **Wort**. Beim Antippen erscheint das Wort groß und eine Auswahl mit **12 verschiedenen Emojis**. Genau eines davon passt zum Wort; seine Position ist pro Aufgabe zufällig.

- **Leicht:** ausschließlich **Kategorie 0**, maximal fünf Buchstaben, **nur Großbuchstaben** (z. B. `HASE`).
- **Mittel:** ausschließlich **Kategorie 0**, maximal sieben Buchstaben, normale Groß- und Kleinschreibung (z. B. `Blume`).
- **Schwer:** Wörter aus beiden Kategorien, normale Groß- und Kleinschreibung, maximal neun Buchstaben; ungefähr **75 % Kategorie 1** (z. B. `Schaf`, `Biene`, `Maus`).
- **Kategorie 0:** ohne besondere Buchstabenkombinationen; **Kategorie 1:** u. a. `sch`, `ch`, `ei`, `ie`, `au`, `eu`, Umlaute, `pf`, `ck`, `tz`, auffällige Doppelkonsonanten.
- Der Wortkatalog umfasst **146 fest zugeordnete Emoji-Wort-Paare** (76 in Kategorie 0, 70 in Kategorie 1).
- Die Auswahl ist bei jeder Aufgabe neu gemischt und enthält die passende Antwort **genau einmal**.
- Falsche Antworten können beliebig oft erneut versucht werden. Richtige Antworten decken automatisch das betreffende Puzzleteil auf.

### Nach einer Runde

Mit **„Nochmal spielen“** wird eine neue Runde im selben Modus und mit denselben Einstellungen gestartet. **„Anderes Puzzle wählen“** oder **„Auswahl“** führen zur Einstellung des aktuellen Modus zurück. Von dort kann man auch zwischen Rechnen und Lesen wechseln.

## Start und Deployment

`index.html` lokal im Browser öffnen. Alle Spiellogik, alle drei SVG-Bilder und der Wortschatz befinden sich in der Datei; das Spiel ist **offline** nutzbar. Es unterstützt Maus, Touch und Tastatur. Reduzierte Bewegung wird berücksichtigt.

- Entwicklung: Branch **`dev`**
- GitHub Pages / öffentliche Version: Branch **`main`** (wird durch diese Entwicklung **nicht** verändert)
- Veröffentlichung des Lesemodus erst nach Review und Merge von `dev` nach `main`

Entstanden nach der Idee einer sechsjährigen Spiele-Erfinderin.
