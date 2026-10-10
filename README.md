# StudyOS — IITM + GATE DA Planner

## Local saving — no daily export/import
The planner automatically saves edits, task completion, and progress in the browser’s `localStorage`. You do **not** need to export/import every day. Export/Import is optional backup or manual transfer only.

Important limits of GitHub Pages: this is a static website, so local data is tied to the same browser profile and device. It survives refreshes and browser restarts, but it does not sync between devices/browsers and clearing site data can erase it. Use Export backup occasionally if you want a safety copy.

## Host on GitHub Pages
1. Create a GitHub repository (for example, `studyos-planner`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Open the published Pages URL. Use the same URL and browser profile to keep accessing the same local saved data.

Official guide: https://docs.github.com/en/pages

## Run locally
Open `index.html`, or from this folder run `python3 -m http.server 8000` and visit http://localhost:8000. Note that `localhost` and your GitHub Pages URL have separate browser storage origins, so their saved data is separate.

## Reminders
The site can request browser notification permission. Notifications only work when browser/platform conditions permit; they are not dependable alarms if the browser is closed or the device sleeps. Keep important exams/deadlines in a reliable calendar/reminder app too.

## Accuracy notes
Dates below reflect the schedules supplied by the user, not live course-portal data. TDS dates were marked tentative in the source image; verify them in the official portal. The exact course-to-time-window allocation for the Jan 10, 2027 end-term date was not supplied.

- **MLT + DLGenAI weekly GA deadlines:** W1 Oct 11; W2 Oct 18; W3 Oct 25; W4 Nov 1; W5 Nov 11; W6 Nov 18; W7 Nov 25; W8 Nov 29; W9 Dec 6; W10 Dec 13; W11 and W12 Dec 23, 2026.
- **TDS:** GA0 Oct 11; GA1+GA2 Oct 18; GA3 Oct 25; GA4 Nov 8; GA5 Nov 18; GA6 Nov 23; GA7 Nov 30; GA8 Dec 7; Project 1 Nov 9; Project 2 Dec 13; Remote Online Exam Nov 29, 1:00–1:45 PM; end-term Jan 10, 2027. No TDS Quiz 1/2 events.
- **MLP:** Milestones Oct 11, 18, 25, Nov 1, 8; cutoff Nov 15; both vivas by Dec 6. Submission is counted only after the response-copy email is received.
- **DLGenAI:** Form 1/M0 Oct 20; M2 Oct 28; M3 Nov 4; M4 Nov 11; project cutoff Nov 15; M5 Nov 18 (kept separate); report/deployment link and viva deadline Nov 30.
- **Quizzes:** MLT + DLGenAI Quiz 1 Nov 15, 2–6 PM; Quiz 2 Dec 5, 2–6 PM.
- **GATE DA syllabus:** Probability and Statistics; Linear Algebra; Calculus and Optimization; Programming, Data Structures and Algorithms; Database Management and Warehousing; Machine Learning; Artificial Intelligence. General Aptitude is tracked separately.

## Schedule note
Daily study blocks are editable. The site automatically selects the actual local date when opened and lets you move between dates. Progress percentages update from the checked-off events. A planner cannot fetch your live course portal or verify submissions automatically; edit dates/status when official information changes.
