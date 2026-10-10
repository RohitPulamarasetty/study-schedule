# StudyOS — IITM Coursework & GATE DA Planner

I made StudyOS to keep my IITM coursework, project milestones, exams, and GATE DA preparation in one place. I can edit events, tick off completed work, and see the progress update automatically.

## What’s inside

- **Overview:** today’s plan, the next deadlines, progress, and a weekly view.
- **Timeline:** move through the calendar by day or week.
- **Deadlines:** assignment submissions, project milestones, exams, and eligibility dates.
- **GATE DA:** syllabus topics, daily revision blocks, timed PYQs, and an error-log routine.
- **All events:** search, filter, add, edit, delete, and mark items complete.
- **Reminders:** optional browser notifications for deadlines and timed events.
- **Local saving:** changes are saved automatically in this browser. Export/import is only for backups or moving data manually.

## Schedule currently entered

All dates below are from the schedules I supplied. They are not live-synced with the IITM course portal, so I’ll check official announcements if anything changes.

### MLT + DLGenAI weekly assignments

| Week | Content release | Assignment deadline | Notes |
|---|---|---|---|
| 1 | Fri, Oct 2, 2026 | Sun, Oct 11, 2026 | |
| 2 | Fri, Oct 9, 2026 | Sun, Oct 18, 2026 | |
| 3 | Fri, Oct 16, 2026 | Sun, Oct 25, 2026 | |
| 4 | Fri, Oct 23, 2026 | Sun, Nov 1, 2026 | OPPE 1 eligibility closes |
| 5 | Fri, Oct 30, 2026 | Wed, Nov 11, 2026 | |
| 6 | Fri, Nov 6, 2026 | Wed, Nov 18, 2026 | |
| 7 | Fri, Nov 13, 2026 | Wed, Nov 25, 2026 | End-term eligibility closes |
| 8 | Fri, Nov 20, 2026 | Sun, Nov 29, 2026 | OPPE 2 eligibility closes |
| 9 | Fri, Nov 27, 2026 | Sun, Dec 6, 2026 | |
| 10 | Fri, Dec 4, 2026 | Sun, Dec 13, 2026 | GAA calculation closes |
| 11 | Fri, Dec 11, 2026 | Wed, Dec 23, 2026 | |
| 12 | Fri, Dec 11, 2026 | Wed, Dec 23, 2026 | Same release and deadline as shown in the supplied schedule |

### TDS

| Item | Release date | Submission / exam date |
|---|---|---|
| GA0 Bootcamp | Wed, Sep 16, 2026 | Sun, Oct 11, 2026 |
| GA1 | Wed, Oct 7, 2026 | Sun, Oct 18, 2026 |
| GA2 | Wed, Oct 7, 2026 | Sun, Oct 18, 2026 |
| Project 1 | Fri, Oct 9, 2026 | Mon, Nov 9, 2026 |
| GA3 | Wed, Oct 14, 2026 | Sun, Oct 25, 2026 |
| GA4 | Wed, Oct 21, 2026 | Sun, Nov 8, 2026 |
| GA5 | Wed, Nov 4, 2026 | Wed, Nov 18, 2026 |
| Project 2 | Fri, Nov 6, 2026 | Sun, Dec 13, 2026 |
| GA6 | Wed, Nov 11, 2026 | Mon, Nov 23, 2026 |
| GA7 | Wed, Nov 18, 2026 | Mon, Nov 30, 2026 |
| GA8 | Wed, Nov 25, 2026 | Mon, Dec 7, 2026 |
| Remote Online Exam | Sun, Nov 29, 2026, 1:00 PM | Sun, Nov 29, 2026, 1:45 PM |
| Final end-term (in person) | — | Sun, Jan 10, 2027 |

GA links: [GA0](https://exam.sanand.workers.dev/tds-2026-09-ga0), [GA1](https://exam.sanand.workers.dev/tds-2026-09-ga1), [GA2](https://exam.sanand.workers.dev/tds-2026-09-ga2). The supplied TDS table did not specify the end-term time window.

### MLP project

| Requirement | Deadline |
|---|---|
| Milestone 1 | Sun, Oct 11, 2026 |
| Milestone 2 | Sun, Oct 18, 2026 |
| Milestone 3 | Sun, Oct 25, 2026 |
| Milestone 4 | Sun, Nov 1, 2026 |
| Milestone 5 | Sun, Nov 8, 2026 |
| Cross cutoff | Sun, Nov 15, 2026 |
| Complete both vivas | Sun, Dec 6, 2026 |

The milestone form counts as submitted only when the response-copy email arrives.

### DLGenAI project

| Requirement | Deadline |
|---|---|
| Form 1 registration + Milestone 0 setup | Tue, Oct 20, 2026 |
| Milestone 1 — CV foundations and defect exploration | Wed, Oct 21, 2026 |
| Milestone 2 — segmentation pipeline | Wed, Oct 28, 2026 |
| Milestone 3 — transfer learning | Wed, Nov 4, 2026 |
| Milestone 4 — training improvements | Wed, Nov 11, 2026 |
| Cross cutoff | Sun, Nov 15, 2026 |
| Milestone 5 — post-processing and final submission | Wed, Nov 18, 2026 |
| Report form, deployment link, and both vivas | Mon, Nov 30, 2026 |

Form links: [Registration form](https://forms.gle/XBVxgatjQtxVsfqS8). The report form link was not available in the supplied details. The milestone plan describes deployment as optional, while the separate form schedule gives a deployment-link deadline; I’ve kept that distinction in the event notes.

### Other dates

- **MAD2:** project viva preparation target — Sun, Oct 25, 2026.
- **Quiz 1:** Sun, Nov 15, 2026, 2:00–6:00 PM, in person at centres.
- **Quiz 2:** Sat, Dec 5, 2026, 2:00–6:00 PM, in person at centres.
- **End-term schedule supplied separately:** Sun, Jan 10, 2027, with sessions listed as 9:00 AM–12:00 PM and 2:00–5:00 PM. The supplied details do not map courses to sessions, so I’ve marked the course/session allocation for confirmation.

The course name for Quiz 1 and Quiz 2 was not explicit in the supplied table, so the planner labels them for confirmation instead of guessing.

## GATE DA tracker

The planner includes these syllabus areas:

1. Probability and Statistics
2. Linear Algebra
3. Calculus and Optimization
4. Programming, Data Structures and Algorithms
5. Database Management and Warehousing
6. Machine Learning
7. Artificial Intelligence
8. General Aptitude (tracked separately)

Daily blocks are editable placeholders, not official course requirements. Before the Jan 10 end-term date, the planner mixes coursework/project work with GATE concepts and timed PYQs. After that date, the generated plan shifts toward GATE revision and practice through Jan 31, 2027.

## Saving and backups

StudyOS uses the browser’s `localStorage`:

- Changes and completion status save automatically.
- You do not need to export/import every day.
- Data stays in the same browser profile on the same device and website origin.
- Clearing browser/site data can erase it. Export a backup occasionally if the progress matters.
- GitHub Pages does not sync the planner between devices or browsers.
- The updated version preserves saved events from the previous StudyOS storage version and adds new schedule items without overwriting existing completion status.

Browser notifications are best-effort, not guaranteed alarms. Permission is required, and browser/device settings may prevent notifications when the page is closed or the device is asleep.

## Publish on GitHub Pages

1. Put `index.html` and `README.md` in the root of the repository.
2. Open **Settings → Pages** in the repository.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)`, then save.
5. Open the published Pages URL and keep using that same URL and browser profile for the same saved data.

Official guide: [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Run locally

Open `index.html` directly, or run this from the project folder:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>. Localhost and the GitHub Pages URL use separate browser storage, so their saved data will not automatically match.
