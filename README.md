# NextClass

Know what class you are in, what is next, and exactly how long until it starts.

**Live demo:** https://kanishksaini-007.github.io/NextClass/

## What it does

- A hero panel that always answers one question: **what class is next?**
  - During a class it shows the subject, room and a progress bar with minutes left.
  - Between classes it shows the next class with a live countdown.
  - After the last class of the day it rolls over to the next day that has one.
- Day tabs (Mon-Sun) to browse and edit the whole week; today is marked.
- Classes are edited inline: start time, end time, subject, room. Invalid times (missing or end before start) are ignored by the schedule and highlighted.
- A sample week button to try it out, and a clear button to start over.

## Why

I kept checking my timetable image in my gallery between lectures. This replaces that: one page that just says where I need to be and when.

## Tech

Plain HTML, CSS and JavaScript in a single file. No frameworks, no build step, no account. The timetable is stored in your browser's localStorage only.

## Run it

Open `index.html` in any browser, or visit the live demo above.

## Note

Learning project - I am a first-year student figuring out front-end development, and this is me practising DOM rendering, timers and localStorage.
