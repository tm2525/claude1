# Stoke

Calorie in / out ledger. Log food (type, pick from your saved foods, or photograph a nutrition label), and set daily burn from Oura, Garmin or Apple Watch.

Single-file app, no build step. Open `index.html` or install from GitHub Pages as a home-screen app.

- **Burn sources**: manual entry per day, Oura API sync (personal access token), Garmin Connect CSV, Apple Health `export.xml` or Shortcuts CSV.
- **Label reader**: add an Anthropic API key under *Set*; photos go straight from your phone to `api.anthropic.com`.
- **Data** lives in the browser only. Copy a backup JSON from *Set* now and then.
