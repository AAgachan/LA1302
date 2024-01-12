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
| 1    | Muss            | Funktional | Als Spieler möchte ich auf den "Start Quiz"-Knopf klicken können, um das Quiz zu beginnen, damit ich sofort mit dem Spielen beginnen kann. |
| 2    | Muss            | Funktional | Als Spieler möchte ich eine Frage mit vier Multiple-Choice-Antworten sehen, damit ich mein Wissen über Geografie testen kann. |
| 3    | Muss            | Qualität  | Als Spieler möchte ich eine Zeitanzeige für jede Frage haben, damit ich den Zeitdruck und die Dynamik des Spiels spüren kann. |
| 4    | Kann            | Funktional | Als Spieler möchte ich eine "Nächste"-Taste, um zur nächsten Frage zu springen, damit ich das Quiz kontinuierlich durchlaufen kann. |
| 5    | Muss            | Qualität  | Als Spieler möchte ich am Ende des Quiz meine Punktzahl sehen, um meine Leistung bewerten zu können. |
| 6    | Kann            | Funktional | Als Spieler möchte ich die Möglichkeit haben, das Quiz erneut zu starten, um meine Leistung zu verbessern oder andere Fragen zu erleben. |
| 7    | Kann            | Funktional | Als Spieler möchte ich detaillierte Feedbacks zu meinen Antworten sehen, einschliesslich der richtigen Antwort, wenn ich falsch liege, um mein Wissen zu verbessern. |



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ----- | ------------ | ------- | ----------------- |
| 1.1  | Startseite des Quiz geladen | Klick auf "Start Quiz" Knopf | Quiz beginnt und die erste Frage wird angezeigt |
| 1.2  | Quiz begonnen, auf Frage-Seite | Keine Eingabe (Beobachtung) | Sichtbarkeit des "Start Quiz" Knopfs sollte verschwinden |
| 2.1  | Frage im Quiz angezeigt | Keine Eingabe (Beobachtung) | Anzeige einer Frage mit vier Multiple-Choice-Antworten |
| 2.2  | Multiple-Choice-Frage angezeigt | Auswahl einer Antwort | Markierung der gewählten Antwort |
| 3.1  | Frage im Quiz angezeigt | Keine Eingabe (Beobachtung) | Sichtbare Zeitanzeige mit Countdown |
| 3.2  | Countdown läuft | Warten bis Zeit abgelaufen | Automatisches Fortfahren zur nächsten Frage oder Ergebnisanzeige bei Quizende |
| 4.1  | Frage im Quiz beantwortet | Klick auf "Nächste"-Taste | Anzeige der nächsten Frage im Quiz |
| 4.2  | Letzte Frage im Quiz beantwortet | Klick auf "Nächste"-Taste | Anzeige des Quiz-Ergebnisses |
| 5.1  | Ende des Quiz | Keine Eingabe (Beobachtung) | Anzeige der erreichten Punktzahl |
| 5.2  | Erreichte Punktzahl angezeigt | Keine Eingabe (Beobachtung) | Möglichkeit, das Ergebnis zu überprüfen oder das Quiz erneut zu machen |
| 6.1  | Quiz-Ergebnisseite | Klick auf "Quiz erneut starten" | Neustart des Quiz mit neuen oder gemischten Fragen |
| 6.2  | Quiz neu gestartet | Keine Eingabe (Beobachtung) | Verifizierung, dass neue oder zufällige Fragen angezeigt werden |
| 7.1  | Falsche Antwort gegeben | Keine Eingabe (Beobachtung) | Anzeige detaillierter Feedbacks zu der Antwort |




### 1.4 Diagramme

![image](https://github.com/AAgachan/LA1302/assets/110893260/d5164c85-006d-4f4d-bda7-0d96726eebaf)



## 2 Planen

# Arbeitspakete

| AP-№ | Frist | Zuständig | Beschreibung | Geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 22.12.23 | Agachan | Entwurf der Multiple-Choice-Fragen, um eine Auswahl an Fragen für das Quiz zu haben | 60 Min |
| 2.A  | 22.12.23 | Alberto | Implementierung der Anzeige von Multiple-Choice-Fragen im Quiz | 60 Min |
| 3.A  | 22.12.23 | Manuel  | Entwicklung einer Zeitanzeige für jede Frage, um Zeitdruck und Dynamik zu erzeugen | 60 Min |
| 4.A  | 22.12.23 | Samuel  | Implementierung einer "Nächste"-Taste, um zwischen Fragen zu navigieren | 60 Min |
| 5.A  | 22.12.23 | Agachan | Entwicklung eines Systems zur Punkteanzeige am Quizende zur Leistungsbewertung | 60 Min |
| 6.A  | 22.12.23 | Alberto | Entwicklung einer Funktion zum Neustarten des Quiz für verbesserte Leistung oder neue Fragen | 60 Min |
| 7.A  | 22.12.23 | Manuel  | Erstellung von detaillierten Feedbacks zu den Antworten, um das Wissen zu verbessern | 60 Min |
|Total: 7 Stunden| | | | |



## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A | 22.12.23 | Agachan |  60 Min | 30 Min |
| 2.A | 22.12.23 | Alberto |  60 Min | 30 Min |
| 3.A | 22.12.23 | Manuel |  60 Min | 60 Min |
| 4.A | 22.12.23 | Samuel |  60 Min | 45 Min |
| 5.A | 22.12.23 | Agachan | 60 Min | 60 Min |
| 6.A | 22.12.23 | Alberto | 60 Min | 60 Min |
| 7.A | 22.12.23 | Manuel |  60 Min | 30 Min  |




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
