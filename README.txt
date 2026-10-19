BIKE TRACKER 27 — PWA PACKAGE

Contents
- index.html: Bike Tracker 27, with PWA metadata and service-worker registration added.
- manifest.webmanifest: installable app settings.
- sw.js: caches the same-origin app shell for repeat/offline loading.
- icon-192.png and icon-512.png: app icons.

INSTALL / HOST
1. Extract this ZIP.
2. Upload all five files to the same folder in a GitHub repository.
3. In GitHub, open Settings > Pages and publish the branch/folder containing these files.
4. Open the published HTTPS URL on your phone. In the browser menu, choose Install app / Add to Home Screen.
5. Open Bike Tracker from its home-screen icon.

NOTES
- Installable PWA and service workers require HTTPS (GitHub Pages provides HTTPS) or localhost.
- The app uses an external SheetJS/XLSX CDN for spreadsheet export and Google Fonts for typography; those features/fonts may require internet access.
- The service worker caches the same-origin app shell. It does not guarantee every external resource works offline.
- A PWA does not guarantee continuous GPS/trip tracking while the screen is off; mobile OS battery and background limits still apply.
- Existing app code and features are retained; this package adds PWA support around the supplied HTML.
