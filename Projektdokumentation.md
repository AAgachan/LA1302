# Projekt-Dokumentation



Agachan Atputharasa, Alberto Manser, Manuel Greub, Samuel Lucena

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 10.11.23 | 0.0.1 | Wir haben das Projekt begonnen (User Stories, Testfälle etc.). |
| 17.11.23 | 0.0.2 | Entwicklung der Grundfunktionen. |
| 24.11.23 | 0.0.3 | Verbesserung der Funktionen. |
| 01.12.23 | 0.0.4 | Benutzererfahrungsoptimierung. |
| 08.12.23 | 0.0.5 | Abschluss der Hauptfunktionen. |
| 15.12.23 | 0.0.6 | Letzte Feinschfliff. |
| 22.12.23 | 0.1.0 | Fertigstellung des Programms. |
| 12.01.24 | 1.0.0 | Fertigstellung des Dokumentation und Portfolios.| 

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
| 7.1  | Spieler im Quiz mit Fragen     | Klick auf 'Hilfe'-Button | Anzeige eines Hilfe-Dialogs mit Anweisungen zum Quiz |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 22.12.23 | Agachan | Entwurf der Multiple-Choice-Fragen und Antwortoptionen | 60 Min |
| 1.B | 22.12.23 | Alberto | Implementierung der Frage-Anzeige im Frontend | 60 Min |
| 2.A | 22.12.23 | Manuel | Entwicklung der Texteingabe-Funktion für offene Fragen | 60 Min |
| 3.A | 22.12.23 | Samuel | Entwurf eines Editors zur Fragebearbeitung | 60 Min |
| 4.A | 22.12.23 | Agachan | Design und Implementierung des Feedback-Systems | 60 Min |
| 5.A | 22.12.23 | Alberto | Integration von Schwierigkeitsstufen in das Quiz-System | 60 Min |
| 6.A | 22.12.23 | Manuel | Entwicklung eines benutzerfreundlichen Interface-Designs | 60 Min |
| 7.A | 22.12.23 | Samuel | Erstellung einer interaktiven Hilfe-Funktion | 60 Min |
|Total: 8 Stunden| 

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A | 22.12.23 | Agachan | Entwurf der Multiple-Choice-Fragen und Antwortoptionen | 60 Min | 30 Min |
| 1.B | 22.12.23 | Alberto | Implementierung der Frage-Anzeige im Frontend | 60 Min | 30 Min |
| 2.A | 22.12.23 | Manuel | Entwicklung der Texteingabe-Funktion für offene Fragen | 60 Min | 60 Min |
| 3.A | 22.12.23 | Samuel | Entwurf eines Editors zur Fragebearbeitung | 60 Min | 45 Min |
| 4.A | 22.12.23 | Agachan | Design und Implementierung des Feedback-Systems | 60 Min | 60 Min |
| 5.A | 22.12.23 | Alberto | Integration von Schwierigkeitsstufen in das Quiz-System | 60 Min | 60 Min |
| 6.A | 22.12.23 | Manuel | Entwicklung eines benutzerfreundlichen Interface-Designs | 60 Min | 30 Min  |
| 7.A | 22.12.23 | Samuel | Erstellung einer interaktiven Hilfe-Funktion | 60 Min | 45 Min |



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 12.01.24      |  OK        | Agachan       |
| 1.2  | 12.01.24      |  OK        | Agachan       |
| 2.1  | 12.01.24      |  OK        | Alberto       |
| 3.1  | 12.01.24      |  OK        | Alberto       |
| 4.1  | 12.01.24      |  OK        | Manuel        |
| 5.1  | 12.01.24      |  OK        | Manuel        |
| 6.1  | 12.01.24      |  OK        | Samuel        |
| 7.1  | 12.01.24      |  OK        | Samuel        |

Es gab keine Probleme und alles wurde richtig implementiert.


## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
