# JoyRideCalc — GitHub-ready installable app

This is the **PWA version** of JoyRideCalc. It is not an Android Studio project and does not require compiling an APK.

## Upload to GitHub
1. Create a new GitHub repository.
2. Extract this ZIP.
3. Upload **all files and folders inside this folder** to the repository root (so `index.html`, `manifest.json`, and `sw.js` are at the root).
4. Open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then Save.
7. Wait for GitHub Pages to publish your site.

## Install on Android
1. Open the published GitHub Pages URL using **Chrome** on Android.
2. Open Chrome's menu (⋮).
3. Tap **Install app** or **Add to Home screen**.
4. Confirm. JoyRideCalc will appear as an app icon and open in standalone mode.

## Included
- `index.html` — the original JoyRideCalc calculator, with PWA setup added
- `manifest.json` — app name, display mode, and launcher icons
- `sw.js` — offline caching
- `icons/` — JoyRide-inspired calculator app icons

The calculator's fare logic and interface are kept from the supplied HTML. Saved trips and settings continue to use the browser's local storage on the device.
