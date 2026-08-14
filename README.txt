TRIGGER V1
==========
Files:
- index.html       Main application
- questions.json   Question bank
- manifest.json    PWA metadata
- sw.js            Offline cache/service worker

Quick local test:
1. Open a terminal in this folder.
2. Run: python3 -m http.server 8000
3. Open http://localhost:8000

To use on iPad:
Host this folder on any static web host, open the URL in Safari, then use Share > Add to Home Screen.

Notes:
- This is a prototype.
- Scoring is local and resets when a new game starts.
- Accounting scenarios should be reviewed carefully before corporate training use.
