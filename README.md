# Cadence

Full-screen Spotify vinyl player + built-in NEET study tracker.

## Files
- index.html — the whole app
- manifest.webmanifest — installable app (Add to Home Screen)
- icons/ — icon.svg, icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png

## Deploy (GitHub Pages)
Put all of these in the repo root, keeping the `icons/` folder, then enable Pages.
Your Spotify redirect URI stays the same as before if the URL doesn't change.

## Study tracker (button next to Library, or press T)
- Today: days left to exam (edit the date), live study timer, mock test countdowns, backup/restore
- Chapters: add by subject, tick off, optionally note a topic left
- Calendar: monthly view of minutes studied, streak, add/delete entries per day

Study data is stored in the browser (localStorage). Use Backup to move it between devices.
