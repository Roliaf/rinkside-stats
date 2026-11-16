# Rinkside Stats

A tablet app for tracking shots, hits, turnovers, faceoffs, goals, assists, penalties and goalie stats from the stands, with a game report after every period and a weekly season report.

- Everything is stored on the tablet. Nothing is sent anywhere unless you share a report.
- Works offline after it has been opened once with a connection.
- Back up from Settings → Save backup file.

## Build 2
Play-by-play editing, strength calculated from penalties, faceoffs, goal popup, turnovers, end game at any time, light/dark game screen, team color picker, new game report layout with goalie maps, season report, badger app icon.

## Updating
Replace the changed files in this repository, then change `VERSION` in `sw.js` (for example `rinkside-v3`).
The tablet picks up the new version the next time the app is opened with a connection.
