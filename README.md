# Agile Kanban Board // Task & Sprint Manager

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?logo=github)](https://RLKO31.github.io/agile-kanban-board/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Privacy: Client-Side Only](https://img.shields.io/badge/Privacy-100%25%20Client--Side-blue)](#legal--privacy-compliance)
[![Tech: Vanilla JS](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-orange)](#architecture--technology)

[English](#english-version) | [Deutsch](#deutsche-version)

---

## English Version

A modern, responsive, and privacy-first **Agile Kanban Board** developed as part of an academic portfolio project. Designed for managing agile development sprints, thesis workflows, and personal tasks with zero server dependencies.

**Live Demo:** [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

---

### Features

- **5 Agile Workflow Stages**:
  - `Backlog` (Idea inbox & unscheduled items)
  - `To Do` (Sprint backlog ready to be tackled)
  - `Doing` (In-progress tasks with strict Work-in-Progress (WIP) limit indicator of 4)
  - `Testing` (QA, code review, verification)
  - `Done` (Completed items)
- **Interactive Sprint Progress Bar**: Dynamic completion percentage tracking in real time.
- **Search & Multi-Category Filtering**:
  - Filter instantly across categories: *Preparation Work*, *Writing Text*, *Writing Code*, *Testing & Validation*, *Project Management*.
  - Live full-text search across titles, descriptions, and notes.
- **Task Management Modal**:
  - Create, view, edit, and delete tasks.
  - Set custom target deadlines and sprint week labels.
- **Quick Shift Controls**: Move tasks across columns with single-click arrow buttons or edit their status directly.
- **Data Persistence (`localStorage`)**:
  - All changes are saved directly in your browser session.
  - No database required, completely offline-capable.
- **Export & Clipboard Tools**:
  - Download full board status as `.csv`.
  - One-click copy of task data to clipboard for easy pasting into spreadsheets or reports.
- **Preset Helpers**:
  - "Load Demo Tasks" to explore functionality instantly.
  - "Clear Board" to start fresh.

---

### Architecture & Technology

- **Frontend Core**: Pure Semantic HTML5, CSS3 Custom Properties (Dark Mode Theme), and Vanilla JavaScript (ES6+).
- **Zero Third-Party Dependencies**: No external frameworks (React/Vue/Angular), no heavyweight CDNs, no tracking pixels.
- **Local-First Architecture**: Uses browser `window.localStorage` to ensure instant load times and data confidentiality.

---

### Getting Started

#### Option 1: Live Web App
Open the GitHub Pages URL in any modern web browser:
> [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

#### Option 2: Run Locally
Clone the repository and open `index.html` directly:
```bash
git clone https://github.com/RLKO31/agile-kanban-board.git
cd agile-kanban-board
# Open index.html in your default browser (Windows)
start index.html
```
Or start a local web server:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000`.

---

### Legal & Privacy Compliance

#### Privacy by Design (DSGVO / GDPR)
- **100% Client-Side Execution**: All tasks, updates, and interactions stay strictly inside your local browser storage.
- **Zero Tracking**: No telemetry, analytics, cookies, or external server communications.

#### Impressum (German Telemedia Act - § 5 DDG & § 18 Abs. 2 MStV)
- **Operator**: Ralf Oppel (Academic Portfolio Project, THWS)
- **Contact**: `ralf.oppel@study.thws.de`
- **Location**: Germany
- Full Impressum and legal disclosures are accessible directly in the app via the **"Impressum & Datenschutz"** modal in the footer.

---

### License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.

---

## Deutsche Version

Ein modernes, responsives und datenschutzfreundliches **Agiles Kanban Board**, entwickelt als akademisches Portfolio-Projekt. Konzipiert für die Organisation agiler Sprints, Abschlussarbeiten und persönlicher Aufgaben ohne jegliche Server-Abhängigkeiten.

**Live-Webseite:** [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

---

### Funktionen

- **5 Agile Workflow-Phasen**:
  - `Backlog` (Ideenspeicher & ungeplante Aufgaben)
  - `To Do` (Sprint-Backlog, bereit zur Bearbeitung)
  - `Doing` (Aufgaben in Bearbeitung mit strikter Work-in-Progress-(WIP)-Begrenzung auf 4)
  - `Testing` (Qualitätssicherung, Code-Review, Prüfung)
  - `Done` (Abgeschlossene Aufgaben)
- **Interaktiver Sprint-Fortschrittsbalken**: Dynamische prozentuale Erledigungsanzeige in Echtzeit.
- **Suche & Mehrkategorieller Filter**:
  - Sofortiges Filtern nach Kategorien: *Vorbereitung*, *Texterstellung*, *Programmierung*, *Testing & Validierung*, *Projektmanagement*.
  - Live-Volltextsuche über Titel, Beschreibungen und Notizen.
- **Aufgaben-Verwaltungs-Modal**:
  - Erstellen, Anzeigen, Bearbeiten und Löschen von Tasks.
  - Festlegen individueller Deadlines und Sprint-Wochen-Labels.
- **Schnellverschiebung (Quick Shift)**: Verschieben von Aufgaben zwischen den Spalten per Klick oder Statuswechsel.
- **Datenpersistenz (`localStorage`)**:
  - Alle Änderungen werden direkt in der lokalen Browser-Sitzung gespeichert.
  - Keine Datenbank erforderlich, vollständig offline-fähig.
- **Export- & Zwischenablage-Tools**:
  - Download des gesamten Board-Zustands als `.csv`.
  - 1-Klick-Kopieren aller Aufgabendaten in die Zwischenablage für Tabellenkalkulationen und Berichte.
- **Hilfsfunktionen**:
  - "Demo-Tasks laden" zum schnellen Kennenlernen der Funktionen.
  - "Board leeren" für einen sauberen Neustart.

---

### Architektur & Technologie

- **Frontend-Kern**: Reines semantisches HTML5, CSS3 Custom Properties (Dark-Mode-Design) und Vanilla JavaScript (ES6+).
- **Keine Drittanbieter-Abhängigkeiten**: Keine externen Frameworks (React/Vue/Angular), keine schweren CDNs, keine Tracking-Pixel.
- **Local-First-Architektur**: Nutzt browserseitiges `window.localStorage` für sofortige Ladezeiten und absolute Datensicherheit.

---

### Erste Schritte

#### Option 1: Live-Web-App
Öffne die GitHub Pages URL in einem modernen Browser:
> [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

#### Option 2: Lokal ausführen
Klone das Repository und öffne `index.html` direkt:
```bash
git clone https://github.com/RLKO31/agile-kanban-board.git
cd agile-kanban-board
# index.html im Standard-Browser öffnen (Windows)
start index.html
```
Oder starte einen lokalen Webserver:
```bash
# Python 3
python -m http.server 8000
```
Anschließend im Browser `http://localhost:8000` aufrufen.

---

### Rechtliche Hinweise & Datenschutz

#### Privacy by Design (DSGVO)
- **100% Client-Side Ausführung**: Alle Aufgaben, Aktualisierungen und Interaktionen verbleiben ausschließlich im lokalen Browserspeicher.
- **Kein Tracking**: Keine Telemetrie, keine Webanalyse, keine Cookies und keine externen Serveranfragen.

#### Impressum (§ 5 DDG & § 18 Abs. 2 MStV)
- **Betreiber**: Ralf Oppel (Akademisches Portfolio-Projekt, THWS)
- **Kontakt**: `ralf.oppel@study.thws.de`
- **Standort**: Deutschland
- Das vollständige Impressum und alle Pflichtangaben sind direkt in der App über den Link **"Impressum & Datenschutz"** in der Fußzeile erreichbar.

---

### Lizenz

Dieses Projekt ist unter der [MIT License](LICENSE) lizenziert - siehe die Datei [LICENSE](LICENSE) für Details.
