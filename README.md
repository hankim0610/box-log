# Box Log

A CrossFit-style training log that runs in the browser. No install or build step needed.

## What it tracks

- **Strength**: any lift as weight × reps, with an estimated 1RM (Epley formula), kg or lb
- **WODs**: 21 Girls and 10 Hero benchmarks (Fran, Grace, Cindy, Murph, DT…) or custom workouts, scored for time, rounds + reps, total reps or rounds, Rx or Scaled
- **Runs**: 400 m to marathon or a custom distance, with pace per km
- **HYROX**: finish time by division, with optional splits for all 8 runs and 8 stations
- **Skills**: max unbroken reps (pull-ups, muscle-ups, HSPU, double-unders…), handstand walk distance, timed holds

It also has:

- Personal records with PR badges
- A progress chart for any lift, WOD, distance, division or skill
- A percentage calculator (40–105% of your 1RM, rounded to loadable plates)
- Tap any record to edit it

## Run it

Open `index.html` in a browser, or use the GitHub Pages link for this repo.

## Where data is saved

When it runs as a Claude artifact, records sync to your Claude account.
Anywhere else (GitHub Pages, a local file), records are saved in that browser's local storage, so they stay on that device and browser only.

## Roadmap

- Body-weight log (for Linda and Lynne loads)
- Training-day builder
- Export to CSV
- Cloud sync outside Claude
- Native mobile app
