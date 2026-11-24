JOYRIDECALC — ANDROID INSTALLABLE WEB APP
by XioMarley

FILES
- index.html: the original JoyRide fare calculator, prepared for installation
- manifest.webmanifest: Android app name, icon and standalone display settings
- sw.js: service worker for app-shell/offline caching
- icon-192.png and icon-512.png: app icons

PUBLISH TO GITHUB PAGES
1. Create a GitHub repository (for example: joyridecalc).
2. Upload ALL files in this folder to the repository root.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish the site. Open the published HTTPS URL on your Android phone.

INSTALL ON ANDROID
1. Open the published link using Google Chrome.
2. Tap the three-dot menu (⋮).
3. Choose Install app or Add to Home screen.
4. Confirm. JoyRideCalc will appear on your home screen and open in standalone app mode.

OFFLINE
Open the app once while connected to the internet so the app shell and external design resources can be cached. The calculator can then open offline; external fonts/design resources may depend on what was cached on the first visit.

NOTE
This is an installable PWA, not a signed APK. It does not require Play Store installation. Saved trips continue to use the browser's localStorage on that device/browser profile.
