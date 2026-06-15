# Water-logger

# Water Tracker

A mobile-friendly, installable web app for tracking daily water intake.

## Features
- Adjustable daily goal (glasses)
- Adjustable glass size in mL or fl oz, with volume totals
- Tap-to-log button
- 7-day history showing which days hit your goal
- In-app reminder banner based on time of day
- Installable as an app (PWA) — works offline
- Data stored locally on your device (localStorage)

## How to host this on GitHub Pages

1. Create a new repository on GitHub (e.g. `water-tracker`).
2. Upload all the files in this folder to the repo root:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
3. Go to your repo's **Settings → Pages**.
4. Under "Source", select the `main` branch and `/ (root)` folder, then save.
5. Wait a minute, then visit `https://<your-username>.github.io/water-tracker/`.

## Installing on your phone

- **iPhone (Safari):** open the link, tap the Share icon, then "Add to Home Screen".
- **Android (Chrome):** open the link, tap the three-dot menu, then "Install app" or "Add to Home Screen".

Once installed, it opens full-screen like a native app and works offline.

## Notes
- Data is stored only on the device/browser you use — it won't sync across devices.
- Notifications are limited to an in-app reminder banner shown when you open the app (browsers don't allow scheduled background notifications from a simple static site without a push server).
