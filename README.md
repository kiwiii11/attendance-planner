# Attendance Planner (VibeCraft 2026)

A single-page web app for SRM Trichy students to plan attendance for Odd Semester 2026-27.

## Features
- Pick your section (13 timetables loaded) and enter your attendance % per subject
- Auto-detects today's date, with a future planning date
- Classes left in the semester, classes you must attend to stay out of the danger zone, and to reach 90%
- "Irreversible Detention" alert when recovery before November is impossible
- Charts for overall attendance health
- OD / Medical Leave simulator with instant recalculation
- Floating Attendance Advisor chatbot that answers questions like "If I take a 3-day sick leave starting tomorrow, will my Chemistry attendance drop below 75%?"
- Live updates, dark mode, and saved inputs

## Run
No build step. Open `index.html` in a browser.

## Deploy
Vercel: import this repo and deploy (framework: Other). Or enable GitHub Pages (Settings > Pages > main branch, root).

## Edit data
Semester dates, holidays, and timetables are in the `CFG` block at the top of the script in `index.html`.
