# The Lucky 7 Legacy — installable web app

This version is built to run in modern desktop and mobile browsers. It can be published on GitHub Pages, added to the home screen/desktop where supported, and loaded offline after its first successful visit. It does **not** need a BAT launcher or server backend.

## Publish to GitHub Pages
1. Create or open your GitHub repository.
2. Upload the contents of this folder to the repository root: `index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, and this README.
3. In the repository, open **Settings → Pages** and select **Deploy from a branch**, your branch (usually `main`), and **/(root)**. Save.
4. Open the published HTTPS URL once while online. Wait for it to finish loading. The service worker then caches the app shell for offline use.

## Install on devices
- **Android (Chrome/Edge):** open the HTTPS site → browser menu → **Install app** or **Add to Home screen**.
- **Windows/macOS/Linux (supported browsers):** open the HTTPS site → use the install icon in the address bar, or browser menu → **Install app** / **Create shortcut**.
- **iPhone/iPad (Safari):** open the HTTPS site → Share → **Add to Home Screen**. iOS installation/offline behavior depends on the installed iOS version.

## Progress and device syncing
Project progress is stored locally in the browser. It does **not automatically sync** between devices or browsers. Use the app's export/import backup controls to transfer progress. Automatic multi-device sync requires a configured cloud backend and sign-in.

## Offline limits
The app must be opened online at least once to cache its files. Browser storage can be cleared by the user or operating system; export backups regularly. Some browser features require HTTPS, which GitHub Pages provides.

## Privacy
This package does not add analytics or send your project data to a server. Anyone who can use the same browser profile may be able to see locally saved progress. Do not save passwords or secret tokens in project notes.
