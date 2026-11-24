# Udaan Gyaan Yoddha

A static learner quiz app with a 30-day challenge, now covering Aptitude, Data Structures & Algorithms, Python, Web Development, and SQL. Each daily round contains 50 questions, balanced at 10 per topic, with the same 100-point scoring format.

## Run and install

Serve this folder from a static web host over HTTPS (or from `localhost` for local development). Open it once while online so the service worker can cache the app shell and artwork. Learners can then reopen the installed app offline; challenge progress is saved in that browser on that device.

Use the **ADD TO PHONE** button where supported, or the browser's install / Add to Home Screen option. Service workers and PWA installation require HTTPS except on localhost.

## Files

- `index.html` — app, question bank, and interface
- `manifest.webmanifest` — install metadata and app icons
- `sw.js` — app-shell cache and offline navigation fallback
- `assets/` — local artwork and icons cached for offline use