TAMBULI SCHOOL PUBLICATION PWA — STARTER PROJECT

Included:
- index.html: responsive website, Home, Feature Stories, Editorial Cartooning, Admin CMS
- assets/tambuli-logo.png: supplied TAMBULI logo
- manifest.webmanifest and sw.js: installable PWA starter files

HOW TO USE
1. Extract the ZIP folder.
2. Open index.html in a modern browser to preview. The website and local CMS work in the browser.
3. For installable PWA/offline caching, serve the folder from HTTPS or localhost (service workers do not run from file://). Example with Python installed: run `python -m http.server 8000` inside this folder and open http://localhost:8000.
4. Choose Admin CMS to add, edit, or delete sample stories and cartoons. Changes are saved in that browser's local storage.
5. Use “Export content JSON” to back up content.

IMPORTANT LIMITATION
This is a front-end demo CMS, not a secure multi-user publishing system. Content is only stored in the current browser and is not automatically shared with readers on other devices. Before real public deployment, connect a backend/database, add secure administrator authentication and authorization, configure image storage, backups, and school approval/privacy workflows. Use only authorized photos and verified stories of learners.

All sample articles, dates, and captions are placeholders. Replace them with approved school content before public use.
