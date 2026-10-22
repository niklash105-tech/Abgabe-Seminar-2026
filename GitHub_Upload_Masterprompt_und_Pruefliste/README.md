# Masterprompt und Prüfliste zur LLM-gestützten Fragebogenerstellung

Begleitmaterial zur Seminararbeit

> **Leitlinien für große Sprachmodelle zur automatisierten Fragebogenerstellung: Ein Design-Science-Ansatz am Beispiel der KI-Readiness von Krankenhauspersonal**
>
> Niklas Hähnlein · Hochschule Wismar · Master CMP · Praxisseminar 2026
> Betreuer: Dr. Johannes Wichmann · Modulverantwortlicher: Prof. Dr. H. Sturm

## Worum es geht

Die Arbeit entwickelt nach dem Design-Science-Research-Prozess (Peffers et al., 2007) Leitlinien, mit denen ein großes Sprachmodell aus Beispielfragebögen und kontextspezifischen Fachquellen einen theoretisch fundierten und praxisnahen Fragebogen erstellt. Umgesetzt sind die Leitlinien als **Masterprompt für NotebookLM** (Stand Oktober 2026). Demonstriert und evaluiert wurden sie am Beispiel der KI-Readiness von Krankenhauspersonal vor der Einführung von KI.

Die Evaluation zeigte vier wiederkehrende Schwächen der Modellausgabe. Daraus entstand eine kurze **Prüfliste**, mit der ein Mensch das Ergebnis abschließend kontrolliert. Masterprompt und Prüfliste gehören zusammen.

## Inhalt

| Ordner | Inhalt | Anhang der Arbeit |
|---|---|---|
| [`01_Masterprompt`](01_Masterprompt/) | Finaler Masterprompt in zwei Teilen, auch als Textdateien zum Kopieren | A.1 |
| [`02_Pruefliste`](02_Pruefliste/) | Prüfliste für die abschließende Prüfung durch einen Menschen | A.2 |
| [`03_Iterationsprotokoll`](03_Iterationsprotokoll/) | Wissensbasis je Iteration, Nachrichtenverlauf, Bewertungsmaßstab und vollständiger Chatverlauf der Entwicklung | B.1–B.3, D |
| [`04_Finale_Durchlaeufe`](04_Finale_Durchlaeufe/) | Chatverläufe der beiden finalen Durchläufe | C.1, C.2 |
| [`05_Wissensbasis`](05_Wissensbasis/) | Quellenliste, mit der sich die Wissensbasis nachbauen lässt | B.1 |

## Nachbau in NotebookLM

1. Ein **neues** Notebook anlegen. Der Prompt muss ohne Vorgeschichte laufen. In einem Notebook mit bisherigem Dialog überarbeitete NotebookLM den Prompt, statt ihn auszuführen.
2. Die Quellen aus der [Quellenliste](05_Wissensbasis/Quellenliste.md) hochladen.
3. [Teil 1](01_Masterprompt/Masterprompt_Teil1.txt) senden, danach [Teil 2](01_Masterprompt/Masterprompt_Teil2.txt). NotebookLM nahm den vollständigen Prompt nicht in einer Nachricht an.
4. Die Antwort nach Teil 2 auswerten. Sie enthält Modellauswahl, Konstrukttabelle, Fragebogen und Prüfprotokoll.
5. Das Ergebnis mit der [Prüfliste](02_Pruefliste/Pruefliste.md) kontrollieren. Das Prüfprotokoll von NotebookLM ersetzt diese Kontrolle nicht.

**Übertragung auf andere Themen:** Es genügt nicht, Messgegenstand, Zielgruppe und Zeitpunkt zu ändern. Auch themenspezifische Regeln, etwa zur Zielgruppe oder zur KI-Vorerfahrung, müssen angepasst werden. Die Wissensbasis muss zum neuen Thema passen.

## Die acht Leitlinien in Kürze

| Nr. | Leitlinie | Herkunft |
|---|---|---|
| L1 | Den Auftrag präzise festlegen: Messgegenstand, Zielgruppe und Befragungszeitpunkt sowie die Abgrenzung zu verwandten Konstrukten wie Akzeptanz | Iterationen 1–3 |
| L2 | Die Theoriewahl dem LLM überlassen, sie aber an die hinterlegten Quellen binden | Iterationen 1–3 |
| L3 | Gewählte Theorien mit allen Dimensionen und ohne Dopplungen abbilden | Iteration 2 |
| L4 | Beispielfragebögen nur als Bauplan nutzen, nicht als Fragenvorrat | Iteration 0 |
| L5 | Formulierungsregeln vorgeben und ihre Prüfung ans Ende stellen | Iterationen 0–2 |
| L6 | Ein einheitliches Antwortformat mit überschneidungsfreien Kategorien festlegen | Iterationen 0 und 2 |
| L7 | Eine nachvollziehbare Ausgabe mit Modellbegründung, Konstrukttabelle und Prüfprotokoll verlangen | Iteration 3 |
| L8 | Den Prompt ohne Vorgeschichte ausführen und das Ergebnis mit der Prüfliste kontrollieren | Iteration 3 und Evaluation |

## Grenzen

Die Evaluation erfolgte artifiziell und durch eine Person, die die Leitlinien selbst entwickelt hat. Sie beruht auf zwei Durchläufen mit einem Werkzeug und einem Anwendungsfall. Reale Befragte, kognitive Pretests und eine psychometrische Prüfung fehlen. Der erzeugte Fragebogen ist daher ein geprüfter Entwurf, kein validiertes Messinstrument.

## Hinweise zu Quellen und Urheberrecht

Das NotebookLM-Notebook selbst ist nicht öffentlich, da es urheberrechtlich geschützte Quellen enthält. Aus demselben Grund liegen hier keine Volltexte. Der Datensatz mit den fünf Beispielfragebögen wurde im Seminar bereitgestellt und ist ebenfalls nicht enthalten. Die zugehörigen Studien sind in der Quellenliste aufgeführt.

## Transparenz zur KI-Nutzung

- **NotebookLM** (Google) ist Gegenstand der Untersuchung. Alle Eingaben und Ausgaben sind in den Chatverläufen dokumentiert.
- **Claude** (Anthropic) diente als Sparringspartner. Damit wurden einzelne Nachrichten an NotebookLM (Nachrichten 11, 13 und 21 im Chatverlauf der Entwicklung) und Teile der Bewertung vorbereitet. Auch dieses Repository wurde mit Unterstützung von Claude aufbereitet.

## Zitation

Hähnlein, N. (2026). *Leitlinien für große Sprachmodelle zur automatisierten Fragebogenerstellung: Ein Design-Science-Ansatz am Beispiel der KI-Readiness von Krankenhauspersonal* [Seminararbeit]. Hochschule Wismar.
