# Cadence — study companion

A standalone study app. Paper-and-ink look that re-colours itself to the song you're playing.

## Features
- Focus: exam countdown, stopwatch + Pomodoro (25/5, 50/10, 90/15) that auto-logs focus blocks, subject tagging,
  daily goal ring + streak, today's plan, spaced-revision queue, generated soundscapes
- Music: link Spotify, browse playlists / liked / recent / search, play, queue, mini player on every screen
- App colour: Match song (album-art colours), Custom (any colour), or Classic — Settings → App colour
- Syllabus: chapters by subject, "topic left", confidence, auto revision (1, 3, 7, 21, 45 days)
- Calendar: heat-map month, per-day entries, last-7-days chart, time by subject
- Mocks: Physics / Chemistry / Biology marks out of 720, trend chart, weakest-subject callout
- Glance: full-screen desk board (timer, countdown, today, syllabus)

## Spotify setup (one time)
1. developer.spotify.com/dashboard → your app (Client ID 599e9eb44fcf4a729e8ad3d5afdd7f10) → Settings → Redirect URIs
2. Add your hosted Cadence URL exactly as shown in Cadence → Music → "Connect Spotify" (e.g. https://yourname.github.io/cadence/)
3. If the app is in development mode, add your Spotify account under User management
4. Open Cadence → Music → Connect Spotify. Spotify Premium is needed to play.
Cadence plays music inside the browser first (Spotify Web Playback SDK, Premium). The Music screen shows whether the browser player is ready, or why it can’t start. If the browser blocks it (Spotify doesn’t officially support iPad browsers), Cadence falls back to controlling the Spotify app.

## Host (GitHub Pages)
Upload everything in this folder to a repo root (keep icons/) and enable Pages.
The home-screen icon is embedded inside index.html, so it works even if icons/ is missing.
iPad: Safari → Share → Add to Home Screen (delete any old Cadence icon first).

## Files
index.html, manifest.webmanifest, sw.js (offline), icons/
