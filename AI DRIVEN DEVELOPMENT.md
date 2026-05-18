# AI-DRIVEN-DEVELOPMENT

# Product Requirements Document (PRD)

## Product Name  
Zufalls-Entscheider

---

## Overview  
Der Zufalls-Entscheider ist eine einfache App, die Nutzern hilft, schnelle Entscheidungen zu treffen, indem sie aus einer Liste von Optionen zufällig eine auswählt. Die App soll besonders bei alltäglichen „kleinen Entscheidungen“ helfen und Spaß in den Entscheidungsprozess bringen.

---

## Problem  
Menschen verlieren oft Zeit oder Energie bei einfachen Entscheidungen wie:
- Was essen?
- Was unternehmen?
- Welche Aufgabe zuerst erledigen?

Das führt zu Entscheidungsstress oder unnötigem Aufschieben.

---

## Solution  
Eine minimalistische App, in die der Nutzer mehrere Optionen eingibt. Mit einem Klick wird zufällig eine Option ausgewählt und hervorgehoben.

---

## Target Users  
- Schüler und Studenten  
- Personen mit Entscheidungsproblemen im Alltag  
- Gruppen (z. B. Freunde, die sich nicht einigen können)  
- Nutzer, die einfache, schnelle Tools mögen  

---

## Core Features  
- Optionen hinzufügen (Textliste)  
- Optionen löschen oder bearbeiten  
- Button „Zufällig auswählen“  
- Anzeige der ausgewählten Option  
- Reset der Liste  
- Optional: Verlauf der letzten Entscheidungen  

---

## Non-Goals  
- Keine komplexe AI-Logik  
- Keine Benutzerkonten oder Login-System  
- Keine Cloud-Synchronisation  
- Keine komplexen Datenanalysen  

---

## Success Criteria  
- Nutzer kann in unter 10 Sekunden eine Entscheidung treffen  
- App funktioniert stabil ohne Fehler bei der Auswahl  
- Minimalistische und verständliche Benutzeroberfläche  
- Nutzer versteht die App ohne Anleitung  

---

## Suggested Tech Stack  
**Frontend:**  
- HTML / CSS / JavaScript (für einfache Web-App)  
  oder  
- React (wenn etwas moderner gebaut werden soll)

**Optional Backend (falls erweitert):**  
- Node.js + Express (nur für Speicherung oder Statistiken)

**Storage:**  
- LocalStorage (für einfache Version)  
  oder  
- SQLite (wenn lokal gespeichert werden soll)

**Deployment:**  
- Vercel oder Netlify (für Web-App)


# User Stories & Tasks

## 🔹 Epic 1: Optionen verwalten

### User Stories

* Als Nutzer möchte ich Optionen hinzufügen, damit ich zwischen mehreren Möglichkeiten wählen kann.
* Als Nutzer möchte ich Optionen wieder löschen können, falls ich mich umentscheide.
* Als Nutzer möchte ich meine eingegebenen Optionen sehen können.

### Aufgaben (Tasks)

* Input-Feld für neue Option erstellen
* Button „Hinzufügen“ implementieren
* Liste im UI anzeigen
* Funktion zum Löschen eines Listeneintrags bauen
* Daten in einem Array speichern

---

## 🔹 Epic 2: Zufällige Entscheidung

### User Stories

* Als Nutzer möchte ich per Knopfdruck eine zufällige Option auswählen lassen.
* Als Nutzer möchte ich klar sehen, welche Option ausgewählt wurde.

### Aufgaben (Tasks)

* Button „Zufällig auswählen“ erstellen
* Zufallsfunktion (`Math.random`) implementieren
* Ergebnis optisch hervorheben (z. B. fett / farbig)
* Sicherstellen, dass nur aus vorhandenen Optionen gewählt wird

---

## 🔹 Epic 3: Reset & Kontrolle

### User Stories

* Als Nutzer möchte ich alle Optionen zurücksetzen können.
* Als Nutzer möchte ich neu starten können, ohne die Seite neu zu laden.

### Aufgaben (Tasks)

* Button „Zurücksetzen“ erstellen
* Array der Optionen leeren
* UI-Liste neu rendern
* Auswahl-Display zurücksetzen

---

## 🔹 Epic 4 (Optional): Verbesserungen

### User Stories

* Als Nutzer möchte ich nicht doppelte Optionen eingeben.
* Als Nutzer möchte ich die App einfach und schnell bedienen können.

### Aufgaben (Tasks)

* Prüfen
