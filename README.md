# JH Task Tracker

A lightweight, single-file productivity app built around my own workflow.

Plan your day, manage projects, track focus sessions, generate weekly reports, and optionally use Claude AI to streamline your workflow.

> **No frameworks. No build steps. No server.**
> Just open `jh_task_tracker.html` and start working.

## 📸 Screenshots

<p align="center">
  <img width="48%" alt="Dashboard" src="https://github.com/user-attachments/assets/5b6a5b38-38d2-4047-b379-7e60660a581c" />
  <img width="48%" alt="Projects" src="https://github.com/user-attachments/assets/062a4c90-009c-4636-a0d0-dd359b3fd037" />
</p>
<p align="center">
  <img width="48%" alt="Daily List" src="https://github.com/user-attachments/assets/014e98f3-fe94-48f3-925e-c4d112673bfa" />
  <img width="48%" alt="Pomodoro" src="https://github.com/user-attachments/assets/f32919a3-f775-4a7c-b873-21d92b48a552" />
</p>
<p align="center">
  <img width="48%" alt="Weekly Report" src="https://github.com/user-attachments/assets/88c06544-2b2b-4764-a6a9-3b3c9639ab68" />
  <img width="48%" alt="AI Assistant" src="https://github.com/user-attachments/assets/6365a4df-c6d5-4af3-9088-9a995f42c6b5" />
</p>

## ✨ Philosophy

JH Task Tracker is intentionally simple.

* ✅ No installation
* ✅ No account
* ✅ No cloud sync
* ✅ No backend

Everything runs locally in your browser, so your data stays on your own machine.

## 🚀 Features

### 📝 Productivity

#### Daily List

Plan your day, organize tasks by project, prioritize important work, and easily carry unfinished tasks forward.

#### Backlog & Blockers

Keep a running backlog alongside your daily work. Track blockers with status and notes, then move them into your daily list when you're ready.

#### Pomodoro Timer

Stay focused with a built-in Pomodoro timer and automatic session logging.

Export focus history to Excel by project and date range.


### 📋 Project Management

#### Projects / Kanban

Manage projects with either:

* Kanban Board (To Do → In Progress → In Review → Done)
* Sortable List View

Track due dates, priorities, and total focus time for every project.

#### Weekly Report

Generate a visual summary of your week's work, including:

* Focus time
* Completed tasks
* Weekly heatmap
* Per-project breakdown


### 🤖 AI Features *(Optional)*

#### Meeting Assistant

Capture meeting notes with a rich-text sidebar and optionally generate AI-powered transcriptions and summaries.

#### Weekly Standup Generator

Generate standup updates directly from your work history, including:

* Completed tasks
* In-progress work
* In-review tasks
* Pomodoro focus logs
* Time by project
* Daily activity summary
* Active blockers

Copy the generated summary and send it directly to your team.

#### AI Assistant

Bring your own Claude API key to enable:

* Email drafting
* English translation
* Meeting summaries
* Weekly standups
* Freeform chat


## 🚀 Getting Started

1. Download `jh_task_tracker.html`
2. Open it in any modern browser
3. Start working

Everything is stored locally using your browser's `localStorage`.

No installation.
No account.
No data leaves your machine.

> **Optional:** Add your Claude API key in **Settings** to enable AI features.


## 🛠 Tech Stack

* Vanilla JavaScript
* Single HTML file
* No frameworks
* No build tools
* Browser `localStorage`
* `xlsx-js-style`
* Tabler Icons


## 📄 License

Released under the **MIT License**.
