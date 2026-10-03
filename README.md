# Nick's Life Dashboard

A mobile-first, installable Progressive Web App built from the Nick's Life Dashboard spreadsheet.

## What is included
- Today: 1 Must + 2 Should + 1 Want + bonuses
- Automatic points and +2 PITA bonus
- Daily point goal, streak, and point bank
- One-button Close Day: logs points and resets task checkboxes
- Quick Capture Inbox
- Backlog with promote-to-Today
- Project tracker with next actions and progress
- Routines
- Admin / don't-forget list
- Rewards shop
- Stats/history
- Local backup export/import
- Offline PWA support and custom app icon

## Data storage
Version 1 is intentionally local-first. Data is stored in the browser's localStorage on the device where the app is used. Use Export Backup periodically. A later version can add Supabase login/sync without changing the core UX.

## Run locally
Serve this folder with any static web server. Service workers/PWA install require http://localhost or HTTPS.

Example:
```bash
python -m http.server 8000
```
Then open http://localhost:8000.

## GitHub Pages
Upload the files to the root of a GitHub repository, enable GitHub Pages for the main branch/root, then open the Pages URL in Chrome on Android and choose **Add to Home screen / Install app**.
