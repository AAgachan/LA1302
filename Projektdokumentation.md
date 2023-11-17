# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

Agachan Atputharasa, Alberto Manser, Manuel Greub, Samuel Lucena

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 11.11.2023      | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Wir haben uns vorgenommen, als Projekt eines der vorgeschlagenen Projekte für Modul 294 umzusetzen. Wir wollen mithilfe von JavaScript ein Quiz erstellen, welches mit Multiple Choice und Texteingaben den Spieler abfragt. Ausserdem soll es die Möglichkeit geben, die Fragen zu bearbeiten.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Funktional      | Muss     | Als Spieler möchte ich eine Auswahl an Multiple-Choice-Fragen sehen, damit ich mein Wissen testen kann. |
| 2    | Muss            | Funktional | Als Spieler möchte ich meine Antworten über Texteingaben eingeben können, damit ich offene Fragen beantworten kann. |
| 3    | Kann            | Funktional | Als Benutzer möchte ich die Möglichkeit haben, die Fragen zu bearbeiten, damit das Quiz personalisiert werden kann. |
| 4    | Muss            | Qualität  | Als Spieler möchte ich ein klares Feedback über richtige und falsche Antworten, damit ich meinen Lernfortschritt verfolgen kann. |
| 5    | Muss            | Funktional | Als Benutzer möchte ich verschiedene Schwierigkeitsstufen im Quiz auswählen können, damit das Quiz für verschiedene Kenntnisstände geeignet ist. |
| 6    | Muss            | Qualität  | Als Benutzer möchte ich eine benutzerfreundliche Oberfläche haben, damit das Quiz einfach zu navigieren ist. |
| 7    | Kann            | Qualität  | Als Benutzer möchte ich eine Hilfe-Funktion im Quiz, um Unterstützung bei der Bedienung zu bekommen. |

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Quiz-Seite geladen                  | Auswahl einer Multiple-Choice-Frage      | Anzeige der Frage und der Antwortmöglichkeiten     |
| 1.2  | Frage angezeigt                     | Auswahl einer Antwort, Bestätigen        | Feedback zur Antwort (richtig/falsch)              |
| 2.1  | Quiz-Seite mit Texteingabefeldern   | Eingabe einer Antwort in Textform        | Anzeige der eingegebenen Antwort im Textfeld       |
| 2.2  | Textfrage gestellt                  | Eingabe einer korrekten Antwort, Bestätigen | Feedback, dass die Antwort korrekt ist            |
| 3.1  | Admin-Bereich für Fragebearbeitung  | Bearbeiten einer bestehenden Frage       | Aktualisierte Frage wird im Quiz angezeigt         |
| 4.1  | Antwort auf eine Frage gegeben      | Überprüfen der Antwort                   | Deutliches Feedback, ob die Antwort richtig oder falsch war |
| 5.1  | Auswahl der Schwierigkeitsstufe     | Auswahl einer Schwierigkeitsstufe        | Anzeige von Fragen entsprechend der gewählten Stufe |
| 6.1  | Zugriff auf das Quiz                | Navigieren durch das Quiz                | Einfache und intuitive Navigation durch das Quiz   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
