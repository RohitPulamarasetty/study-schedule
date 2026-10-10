# StudyOS — IITM + GATE DA Planner

A simple planner I made to keep my IITM coursework, project milestones, exams and GATE DA prep in one place. I can tick things off, edit dates, add my own tasks and see the progress update as I go.

## What’s inside

- **Overview:** today’s plan, upcoming priorities and weekly view.
- **Timeline + deadlines:** assignments, releases, project milestones and exams in date order.
- **Editable events:** click a task to change its title, date, notes, category or status. Add and delete events too.
- **Progress tracking:** completion percentages update when tasks are checked off.
- **GATE DA tracker:** syllabus topics and daily practice blocks.
- **Reminders:** optional browser notifications for deadlines and timed tasks.
- **Local saving:** changes save in this browser automatically.

## Use it

### Open it on your Mac

You can open `index.html` directly. If you prefer to run it through a local server, open Terminal in the project folder and run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

### Put it on GitHub Pages

1. Create a GitHub repository for the planner.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then save.
6. Open the URL GitHub Pages gives you.

GitHub’s guide: <https://docs.github.com/en/pages>

## Saving your data

I don’t need to export and import every day. The planner saves edits and completion status automatically in the browser’s `localStorage`.

A few things to keep in mind:

- Data stays in the same browser profile on the same device.
- It does **not** sync between my Mac, phone, different browsers or the local-server and GitHub Pages versions.
- Clearing the browser’s site data can erase the planner’s saved data.
- **Export backup** downloads a JSON backup. I’ll use it occasionally or before resetting/moving the planner; **Import backup** restores one.

## Dates currently added

These are based on the schedule details I entered. They are reminders, not a live connection to the course portal.

### MLT + DLGenAI weekly assignments

| Week | Content release | Deadline / note |
|---|---|---|
| 1 | Fri, Oct 2, 2026 | Sun, Oct 11 |
| 2 | Fri, Oct 9 | Sun, Oct 18 |
| 3 | Fri, Oct 16 | Sun, Oct 25 |
| 4 | Fri, Oct 23 | Sun, Nov 1 — OPPE 1 eligibility closes |
| 5 | Fri, Oct 30 | Wed, Nov 11 |
| 6 | Fri, Nov 6 | Wed, Nov 18 |
| 7 | Fri, Nov 13 | Wed, Nov 25 — end-term eligibility closes |
| 8 | Fri, Nov 20 | Sun, Nov 29 — OPPE 2 eligibility closes |
| 9 | Fri, Nov 27 | Sun, Dec 6 |
| 10 | Fri, Dec 4 | Sun, Dec 13 — GAA calculation closes |
| 11 | Fri, Dec 11 | Wed, Dec 23 |
| 12 | Fri, Dec 11 | Wed, Dec 23 |

### TDS

| Item | Release | Submission / exam |
|---|---|---|
| GA0 Bootcamp | Wed, Sep 16, 2026 | Sun, Oct 11 |
| GA1 + GA2 | Wed, Oct 7 | Sun, Oct 18 |
| Project 1 | Fri, Oct 9 | Mon, Nov 9 |
| GA3 | Wed, Oct 14 | Sun, Oct 25 |
| GA4 | Wed, Oct 21 | Sun, Nov 8 |
| GA5 | Wed, Nov 4 | Wed, Nov 18 |
| Project 2 | Fri, Nov 6 | Sun, Dec 13 |
| GA6 | Wed, Nov 11 | Mon, Nov 23 |
| GA7 | Wed, Nov 18 | Mon, Nov 30 |
| GA8 | Wed, Nov 25 | Mon, Dec 7 |
| Remote Online Exam | Sun, Nov 29, 1:00 PM | Sun, Nov 29, 1:45 PM |
| Final in-person exam | — | Sun, Jan 10, 2027 |

TDS graded assignments use the **best 7 of 9** rule and carry 20% overall. Project 1, Project 2, the Remote Online Exam and the final exam are listed as 20% each in the schedule I received. Check the course portal for any updates.

### MLP project

- Milestone 1 — Sunday, Oct 11
- Milestone 2 — Sunday, Oct 18
- Milestone 3 — Sunday, Oct 25
- Milestone 4 — Sunday, Nov 1
- Milestone 5 — Sunday, Nov 8
- Cross-cutoff deadline — Sunday, Nov 15
- Complete both vivas by — Sunday, Dec 6

**Important:** a milestone counts as submitted only after the response-copy email arrives.

### DLGenAI project

- **Oct 20:** Registration Form 1 and Milestone 0 (orientation, accounts and setup)
- **Oct 21:** Milestone 1 — computer vision basics and defect exploration
- **Oct 28:** Milestone 2 — segmentation pipeline and baseline model
- **Nov 4:** Milestone 3 — transfer learning and stronger models
- **Nov 11:** Milestone 4 — training improvements and optimization
- **Nov 15:** cross-cutoff deadline
- **Nov 18:** Milestone 5 and final Kaggle submission
- **Nov 30:** report submission, deployment link and both vivas deadline

The report-submission form and deployment-link form were listed as due on Nov 30; the deployment form link was not available in the details I had.

### Quizzes, MAD2 and end-terms

- **MAD2 project viva preparation target:** Oct 25.
- **MLT + DLGenAI Quiz 1:** Sunday, Nov 15, 2–6 PM, in person at centres.
- **MLT + DLGenAI Quiz 2:** Saturday, Dec 5, 2–6 PM, in person at centres.
- **End-term date:** Sunday, Jan 10, 2027. The supplied schedule lists 9 AM–12 PM and 2–5 PM in-person windows, but doesn’t specify the assigned slot for each course. I’ll check the official timetable/hall ticket.

## Reminders: what they can and can’t do

The page can ask permission to show browser notifications. Keep the page open for timed reminders; notifications are not guaranteed when the browser is closed or the device is asleep. For exams, I’ll also keep the important dates in a proper calendar/reminder app.

## One last note

The planner doesn’t fetch course updates or verify submissions automatically. If a deadline changes, I can edit the event in the page. The GATE DA syllabus is grouped into Probability and Statistics, Linear Algebra, Calculus and Optimization, Programming and Data Structures, Database Management and Warehousing, Machine Learning, Artificial Intelligence, plus separate General Aptitude practice.
