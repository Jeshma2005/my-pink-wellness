MY PINK DAILY ROUTINE — INSTALLABLE WEB APP

Files:
- index.html: your pink daily checklist
- manifest.webmanifest: app name, icon and install settings
- sw.js: offline cache
- icons/: app icons

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to install in Chrome.
Opening index.html directly from Downloads will NOT enable installation.

Simple publishing route:
1. On a computer, sign in to GitHub and create a new public repository.
2. Upload the CONTENTS of this folder (index.html, manifest.webmanifest, sw.js, and icons folder).
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
5. Wait for the published HTTPS Pages URL.
6. Open that URL in Chrome on your Android phone.
7. Tap Chrome's ⋮ menu > Install app (or Add to Home screen) > Install.

Your checklist ticks are stored in the browser on that device. Keep using the same installed app/browser profile so the saved ticks remain available.


WEIGHT TRACKER:
- A Monday weigh-in popup appears the first time you open the app on a Monday.
- You can also add/update a weight anytime using the tracker card.
- Entries are saved locally in this browser on this phone.
- The first comparison uses the starting reference weight of 73.95 kg.
- The app does not send an automatic notification while fully closed; the Monday popup appears when you open it.
