# Agile Kanban Board // Task & Sprint Manager

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?logo=github)](https://RLKO31.github.io/agile-kanban-board/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Privacy: Client-Side Only](https://img.shields.io/badge/Privacy-100%25%20Client--Side-blue)](#-privacy--legal-compliance)
[![Tech: Vanilla JS](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-orange)](#-architecture--features)

A modern, responsive, and privacy-first **Agile Kanban Board** developed as part of an academic portfolio project. Designed for managing agile development sprints, thesis workflows, and personal tasks with zero server dependencies.

**Live Demo:** [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

---

## Features

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

## Architecture & Technology

- **Frontend Core**: Pure Semantic HTML5, CSS3 Custom Properties (Dark Mode Theme), and Vanilla JavaScript (ES6+).
- **Zero Third-Party Dependencies**: No external frameworks (React/Vue/Angular), no heavyweight CDNs, no tracking pixels.
- **Local-First Architecture**: Uses browser `window.localStorage` to ensure instant load times and data confidentiality.

---

## Getting Started

### Option 1: Live Web App
Open the GitHub Pages URL in any modern web browser:
> [https://RLKO31.github.io/agile-kanban-board/](https://RLKO31.github.io/agile-kanban-board/)

### Option 2: Run Locally
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

## Legal & Privacy Compliance

### Privacy by Design (DSGVO / GDPR)
- **100% Client-Side Execution**: All tasks, updates, and interactions stay strictly inside your local browser storage.
- **Zero Tracking**: No telemetry, analytics, cookies, or external server communications.

### Impressum (German Telemedia Act - § 5 DDG & § 18 Abs. 2 MStV)
- **Operator**: Ralf Oppel (Academic Portfolio Project, THWS)
- **Contact**: `ralf.oppel@study.thws.de`
- **Location**: Germany
- Full Impressum and legal disclosures are accessible directly in the app via the **"Impressum & Datenschutz"** modal in the footer.

---

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
