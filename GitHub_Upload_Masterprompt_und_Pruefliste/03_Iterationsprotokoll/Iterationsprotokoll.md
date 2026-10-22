# Iterationsprotokoll (Anhang B und D)

Die Leitlinien entstanden in vier Iterationen nach dem Design-Science-Research-Prozess (Peffers et al., 2007). Jede Iteration durchlief Design und Entwicklung, Demonstration sowie Evaluation. Bewertet wurde stets an denselben sechs Zielen.

## B.1 Wissensbasis

| Iteration | Inhalt des Notebooks |
|---|---|
| 0 | Datensatz mit fünf Beispielfragebögen |
| 1 bis 3 | Zusätzlich: Studien zu den fünf Beispielfragebögen; Theoriequellen: Karaca et al. (2021), Parasuraman & Colby (2015), Venkatesh et al. (2003), Wichmann, Gesk, et al. (2024); Quellen zum Krankenhauskontext: Antweiler et al. (2024), Antweiler et al. (2026), Jussupow et al. (2021), Lambert et al. (2023), Maassen et al. (2021), Sommer et al. (2024), Weinert et al. (2022); Methodenquelle: MacKenzie et al. (2011) |
| Durchläufe 1 und 2 | Je ein neues Notebook mit derselben Wissensbasis wie in den Iterationen 1 bis 3 |

Vollständige Angaben: [Quellenliste](../05_Wissensbasis/Quellenliste.md)

## B.2 Nachrichtenverlauf

| Nachricht | Iteration | Eingabe der steuernden Person | Ergebnis |
|---|---|---|---|
| 1 bis 2 | 0 | „Erstelle einen Fragebogen zur Messung der KI-Readiness von Krankenhauspersonal“ | 6 Dimensionen, 15 Fragen, siebenstufige Skala; keine Theorie, keine Quellen |
| 3 bis 4 | 0 | Ausgabe als PDF | Einzelne Formulierungen im PDF verändert |
| 5 bis 6 | 1 | Frage nach geeigneter Theorie mit Begründung und Quellen | Empfehlung einer Synthese aus MAIRS-MS und Akzeptanzmodellen |
| 7 bis 8 | 1 | Frage nach Konstrukten mit Quellen | 11 Konstrukte angekündigt, 12 geliefert |
| 9 bis 10 | 1 | Drei Fragen je Konstrukt, keine Übernahme aus den Beispielen | 36 Fragen, siebenstufige Skala |
| 11 bis 12 | 2 | Hinweis auf Akzeptanzkonstrukte und Befragungszeitpunkt; Frage nach Modell für die allgemeine Haltung zu Technik | TRI 2.0 vorgeschlagen; Vision fehlt, Unsicherheit doppelt, Technology Acceptance Model mit Originalquelle zitiert |
| 13 bis 14 | 2 | Dimensionen vollständig und je einmal übernehmen; nur Quellen aus dem Notebook | Messmodell aus 8 Dimensionen |
| 15 bis 16 | 2 | Drei Fragen je Konstrukt auf Basis der Originalskalen | 24 Fragen |
| 17 bis 18 | 2 | Kritische Prüfung der Fragen | Keine Mehrfachaussagen mehr, teils durch Streichen statt Aufteilen |
| 19 bis 20 | 2 | Vereinfachung für Pflegekraft ohne KI-Vorwissen; fünfstufige Skala, Einleitung, Angaben zur Person | 12 von 24 Fragen wieder mit Mehrfachaussagen |
| 21 bis 22 | 3 | Auftrag zum Masterprompt mit Liste aller Mängel | Erster Entwurf mit fest vorgegebener Theorie und organisatorischer Bereitschaft |
| 23 bis 28 | 3 | Drei Korrekturrunden | Theoriewahl durch das Modell, keine fertigen Antwortkategorien und Beispielfragen zum Thema, Ausgabe mit Begründung, Tabelle und Prüfprotokoll |
| 29 bis 34 | 3 | Finaler Prompt mit Präzisierungen von Hand, in zwei Teilen eingegeben | Modell überarbeitete den Prompt, statt ihn auszuführen |
| 35 bis 38 | 3 | Ausführung im Entwicklungsnotebook | Wegen bekannter Vorgeschichte nicht gewertet |

## B.3 Vollständiger Chatverlauf des Entwicklungsnotebooks

Datei: [`Anhang_B3_Chatverlauf_Entwicklung.docx`](Anhang_B3_Chatverlauf_Entwicklung.docx) (Iterationen 0 bis 3, Nachrichten 1 bis 38)

Die Datei ist kein technischer Export. NotebookLM hat sie auf Anfrage als Word-Dokument erzeugt und den Verlauf dabei nicht vollständig wortgetreu wiedergegeben. Im ersten Export fehlten Teile der Nachrichten 22, 24, 26, 28, 30 und 36. Ein zweiter Export enthielt diese Nachrichten vollständig, veränderte aber in den Nachrichten 11, 17, 19, 21, 23, 25 und 29 Zeichensetzung und einzelne Formulierungen. Die vorliegende Fassung wurde deshalb aus beiden Exporten zusammengeführt und an den abweichenden Stellen mit dem Verlauf im Notebook abgeglichen. Der Kasten mit dem Masterprompt am Anfang zeigt die Fassung aus Nachricht 34, also vor zwei Korrekturen von Hand. Die in den Durchläufen verwendete Fassung steht im Ordner [`01_Masterprompt`](../01_Masterprompt/).

## Bewertungsmaßstab (Anhang D)

### Ziele

| Ziel | Anforderung an die Leitlinien | Begründung |
|---|---|---|
| Z1 Theoriebezug | Das LLM schlägt eine oder mehrere Theorien aus den Quellen vor, begründet die Wahl und leitet die Fragen daraus ab. | Messinstrumente erfordern eine theoretisch fundierte Konstruktdefinition (MacKenzie et al., 2011). |
| Z2 Belegbare Quellen | Alle Aussagen stützen sich auf die hinterlegten Quellen und sind korrekt zitiert. | LLMs können Inhalte erfinden (Susarla et al., 2023). |
| Z3 Definierte Konstrukte | Jedes Konstrukt wird definiert und mit mindestens drei Fragen gemessen. Die Dimensionen gewählter Modelle sind vollständig und ohne Dopplungen enthalten. | Konstrukte sind eindeutig zu definieren (MacKenzie et al., 2011). |
| Z4 Korrekt formulierte Fragen | Jede Frage enthält nur eine Aussage und ist neutral und verständlich formuliert. | Fragen mit doppelter Aussage sind zu teilen oder zu streichen (MacKenzie et al., 2011). |
| Z5 Zielgruppe und Kontext | Die Fragen richten sich in Ich-Form an Klinikpersonal und passen zum Befragungszeitpunkt vor der Einführung von KI. Einleitung und Angaben zur Person passen zur Befragungssituation. | KI-Readiness betrifft Wissen, Fähigkeiten und Einstellungen des Personals (Karaca et al., 2021) und sollte vor der Einführung von KI bekannt sein (Antweiler et al., 2024). |
| Z6 Antwortformat | Alle Inhaltsfragen nutzen eine einheitlich beschriftete Skala. Die Antwortkategorien bei den Angaben zur Person überschneiden sich nicht. | Nur einheitliche, eindeutige und überschneidungsfreie Antwortmöglichkeiten machen die Antworten vergleichbar (Lenzner & Menold, 2015). |

### Bewertungsstufen

- **erfüllt:** Anforderung vollständig umgesetzt
- **weitgehend:** einzelne Abweichungen
- **teilweise:** deutliche Mängel
- **nicht erfüllt:** Anforderung nicht erkennbar umgesetzt

Für Z4 steht in Klammern die Anzahl der Fragen mit mehreren Aussagen oder wertenden Begriffen im Verhältnis zur Gesamtzahl. Als Mehrfachaussage zählt jede Frage, die zwei bewertbare Sachverhalte verbindet, etwa „schneller und einfacher“. Paarformeln wie „Kolleginnen und Kollegen“ zählen nicht.

### Zielerreichung über alle Iterationen

| Ziel | Iteration 0 | Iteration 1 | Iteration 2 | Iteration 3 |
|---|---|---|---|---|
| Z1 Theoriebezug | nicht erfüllt | teilweise | erfüllt¹ | erfüllt |
| Z2 Belegbare Quellen | nicht erfüllt | weitgehend | weitgehend | weitgehend |
| Z3 Definierte Konstrukte | teilweise | teilweise | weitgehend | erfüllt |
| Z4 Korrekt formulierte Fragen | nicht erfüllt (11/15) | teilweise (18/36) | teilweise (12/24) | weitgehend (0/24)² |
| Z5 Zielgruppe und Kontext | teilweise | teilweise | weitgehend³ | weitgehend³ |
| Z6 Antwortformat | teilweise | weitgehend | weitgehend | weitgehend |

¹ erst nach Hinweisen der steuernden Person

² keine Mehrfachaussagen, aber je eine sozial erwünschte Frage

³ Die Einleitung sagte vollständige Anonymität zu, obwohl Angaben zur Person erhoben wurden (Iteration 2: Anhang B.3, Nachricht 21; Iteration 3: Anhang C, Nachricht 4).

Für Iteration 3 fasst die Tabelle beide finalen Durchläufe zusammen.
