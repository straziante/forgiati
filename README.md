# Forge — gym workout tracker

**Live demo:** https://forgiati.netlify.app/

## Overview
Forge is a small single-page web app I built for the gym, to log my workouts and see how I progress. It has no server and no account: everything is stored in the browser (`localStorage`), so it works offline once loaded.

The interface is in Italian.

## Features
- **Train:** choose the day of your plan, then the exercise and muscle group, record weight and reps for each set, and save the session.
- **History:** every saved workout, with the chronology of each exercise.
- **Statistics:** per-exercise charts (max weight, progress since the start), and per-muscle-group figures such as last week's total, the 4-week average, change against the previous week and a week-by-week breakdown.
- **Plan editor:** name the training days and set each day's focus. Add, rename, recolour or delete exercises and muscle groups.
- **Saves and backup:** export and import the data as a backup file, restore the default exercises, or wipe everything (kept in a "danger zone" so it is not hit by accident).

## Tech
Plain HTML, CSS and JavaScript in a single file ([`index.html`](index.html)). The charts are drawn as SVG by the app's own code, with no chart library. No build step.

## Run it locally
Open `index.html` in a browser.
