# Forge — gym workout tracker

A small single-page web app I built to log my gym workouts and see how I progress.

**Live demo:** https://forgiati.netlify.app/

## Features
- Log a workout: pick an exercise and muscle group, record weight and reps, save the session.
- Edit your plan: name the training days, set each day's focus, add, rename, recolour or delete exercises and muscle groups.
- History of saved workouts, with per-exercise chronology.
- Statistics (charts): max weight per exercise, progress against the start, last-week totals, 4-week average, week-by-week detail, and per muscle group.
- Data backup and restore, plus a "reset exercises" option.

All data stays in the browser (`localStorage`); there is no server and no account.

## Tech
Plain HTML, CSS and JavaScript in a single file ([`index.html`](index.html)), with Chart.js for the charts. The interface is in Italian.

## Run it
Open `index.html` in a browser. No build step.
