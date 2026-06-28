# JH Task Tracker

A single-file productivity app built around my own workflow.

Plan your day, manage projects, track focus sessions, generate weekly reports, and optionally use Claude AI to streamline your workflow.

**No frameworks. No build steps. No server.**
Just open `jh_task_tracker.html` in your browser and start working.

---

## Philosophy

JH Task Tracker is intentionally simple.

* No installation
* No account
* No cloud sync
* No backend

Everything runs locally in your browser, so your data stays on your own machine.

---

## Features

### Productivity

**Daily List**
Plan your day, organize tasks by project, star priorities, and easily carry unfinished tasks forward.

**Backlog & Blockers**
Maintain a running backlog alongside your daily work. Track blockers with status and notes, then move them into your daily list when they're ready.

**Pomodoro Timer**
Built-in Pomodoro timer with automatic session logging. Export focus history to Excel by project and date range.

---

### Project Management

**Projects / Kanban**
Manage projects with a Kanban board (To Do → In Progress → Done) or a sortable list view. Track due dates, priorities, and total focus time.

**Weekly Report**
Generate a visual summary of your week's work, including focus time, completed tasks, a heatmap, and per-project breakdowns.

---

### AI Features *(Optional)*

**Meeting Assistant**
Capture meeting notes in a rich-text sidebar with optional AI-powered transcription and summaries.

**Weekly Standup Generator**
Generate standup updates from your actual work history.

Includes:

* Completed, in-progress, and in-review tasks
* Pomodoro focus logs
* Time spent by project
* Day-by-day activity breakdown
* Active blockers

Copy the generated summary and send it directly to your team.

**AI Assistant**

Bring your own Claude API key to enable AI-powered features such as:

* Weekly standup generation
* Drafting emails
* English translation
* Meeting summaries

---

## Getting Started

1. Download `jh_task_tracker.html`
2. Open it in any modern browser
3. Start working

All data is stored locally using your browser's `localStorage`.

No installation.
No account.
No data leaves your machine.

> **Optional:** Add your own Claude API key in **Settings** to enable AI features.

---

## Tech

* Vanilla JavaScript
* Single HTML application
* No frameworks
* No build tools
* Browser `localStorage`
* Excel export via `xlsx-js-style`
* Tabler Icons (CDN)

---

## License

Released under the **MIT License**.
