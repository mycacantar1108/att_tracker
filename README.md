# Attendance Tracker v12 — Installable PWA

This package is the static PWA build of the supplied Attendance Tracker HTML.

## GitHub Pages
1. Create a public GitHub repository.
2. Upload `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, and `icon-512.png` to the repository root.
3. In Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Open the published HTTPS URL.
5. In Chrome on Android, choose **Install app** or **Add to Home screen**.

The service worker caches the app shell for offline reopening after the first successful visit.

## Important
App data is still browser-local. GitHub Pages hosts the app but does not automatically synchronize attendance/profile/checklist data between devices.
