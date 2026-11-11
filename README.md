# Speakly

Speakly is a mobile-first German-learning web app for Russian speakers. The current version is a static web app with local progress storage and an installable/offline shell.

## Implemented

- Responsive interface designed for phones first
- Six beginner chapters with multiple-choice, reverse-translation and typed-answer exercises
- German vocabulary collection with search, favorites and spaced review scheduling
- Grammar reference with concise explanations and examples
- XP, levels, daily goals, streaks, weekly activity and achievements
- Cosmetic shop, coin balance, purchases, inventory and equipping items
- Guest profile, editable display name, settings and progress export/reset
- Local persistence in the browser
- PWA manifest and service worker for caching the app shell

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

For offline/PWA behavior, serve the folder over HTTPS or localhost. Service workers do not run from ordinary `file://` URLs.

## Current limitations — stated honestly

- Progress is stored in this browser on this device. It does not sync between devices.
- There is no real email/password account system or server database yet.
- Clubs, multiplayer challenges, moderation and global leaderboards are not active.
- The reminder setting is a saved preference only; scheduled push notifications are not implemented.
- The course currently contains the first six German A1 chapters and a starter grammar guide.

The GitHub Pages workflow is included in `.github/workflows/pages.yml`. To publish, enable **Settings → Pages → Source: GitHub Actions** in the repository if Pages is not already enabled. After the workflow succeeds, GitHub will show the public site URL in the Pages settings.
