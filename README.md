# JH Task Tracker

A lightweight, single-file productivity app built around my own workflow.

Plan your day, manage projects, track focus sessions, generate weekly reports, and optionally use Claude AI to streamline your workflow.

> **No frameworks. No build steps. No server.**
> Just open `jh_task_tracker.html` and start working.

## 📸 Screenshots

<p align="center">
  <img width="48%" alt="Dashboard" src="https://github.com/user-attachments/assets/bb79a26c-0993-41e5-b053-48baebe3cafe" />
  <img width="48%" alt="Daily List" src="https://github.com/user-attachments/assets/70b5fdf6-d7cd-4f40-95b2-39eb6834fb3c" />
</p>
<p align="center">
  <img width="48%" alt="Projects" src="https://github.com/user-attachments/assets/fcd2fd19-8e39-49b9-aa82-3c59554d0f4d" />
  <img width="48%" alt="Pomodoro" src="https://github.com/user-attachments/assets/b4965646-036f-4b90-a995-208fbc357cc3" />
</p>
<p align="center">
  <img width="48%" alt="Timeline" src="https://github.com/user-attachments/assets/d24e817f-b30c-4f0e-8d83-69f54a7dc844" />
  <img width="48%" alt="Report" src="https://github.com/user-attachments/assets/aeba06ae-abe7-48e9-acde-ca0a74536217" />
</p>

## ✨ Philosophy

JH Task Tracker is intentionally simple.

* ✅ No installation
* ✅ No account
* ✅ No backend

Everything runs locally in your browser, so your data stays on your own machine.

## 🚀 Features

### 📝 Productivity

#### Daily List

Plan your day, organize tasks by project, prioritize important work, and easily carry unfinished tasks forward. Schedule items for Today or Tomorrow, log time manually against a task, and add time estimates that sync with the Pomodoro timer.

Set an editable daily focus goal and earn a "Rest earned" badge once you've logged enough focus time for the day.

#### Backlog & Blockers

Keep a running backlog alongside your daily work. Track blockers with status and notes, then move them into your daily list when you're ready.

#### Routines

Set up recurring tasks that auto-generate into your Daily List (with a Tomorrow group) so repeat work never needs re-typing.

#### Ideas & Feedback

Capture ideas and product feedback/bugs as draggable, starrable cards, kept separate from your day-to-day task lists.

#### Pomodoro Timer

Stay focused with a built-in Pomodoro timer and automatic session logging. Let a session continue past its estimate instead of stopping, edit a logged session's duration after the fact, and get a sound when a break ends.

Export focus history to Excel by project and date range, including a By Tag summary sheet and an AI-summarized Timesheet sheet.

#### Global Search

Press `Ctrl+K` to search across tasks, ideas, and log notes from anywhere in the app.


### 📋 Project Management

#### Projects / Kanban

Manage projects with either:

* Kanban Board (To Do → In Progress → In Review → Done)
* Sortable List View

Track due dates, priorities, tags, and total focus time for every project.

#### Weekly Report

Generate a visual summary of your week's work, including:

* Focus time
* Completed tasks
* Weekly heatmap
* Per-project breakdown

#### Timeline

A read-only view of how your focus time was distributed across the week, broken down by project.


### 🎨 Themes

Switch between a green and an orange theme from the sidebar.

### 🤖 AI Features *(Optional)*

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

#### Efficiency Review

Pick a date range and get an AI analysis of how the period actually went — weekday focus time and active workdays, time split by task, day-by-day fragmentation, planned vs. delivered tasks, weekend-work boundary check, and stalled work — followed by a short list of specific, actionable recommendations for the week ahead.

#### Meeting Assistant

Capture meeting notes with a rich-text sidebar and optionally generate AI-powered transcriptions and summaries.

### ☁️ Cloud Sync *(Optional)*

Sync your data between devices (e.g. Mac ↔ Windows) using your own private GitHub Gist. Bring your own GitHub token — it's kept in the browser only and never uploaded anywhere else.


## 🚀 Getting Started

1. Download `jh_task_tracker.html`
2. Open it in any modern browser
3. Start working

Everything is stored locally using your browser's `localStorage`.

No installation.
No account.
No data leaves your machine unless you enable AI features or Cloud Sync yourself.

> **Optional:** Add your Claude API key in **Settings** to enable AI features, or your GitHub token in **Sync** to enable Cloud Sync.


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
