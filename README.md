# Group Field Service Report

A static Progressive Web App (PWA) prepared for GitHub Pages.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `group-field-service-report`.
2. Upload the contents of this folder to the repository root. Keep `index.html`, `manifest.webmanifest`, `service-worker.js`, and the `assets` folder together.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. Open the published HTTPS address on your phone.

## Install on Android

1. Open the published site in Chrome.
2. Open the browser menu.
3. Choose **Install app** or **Add to Home screen**.
4. Confirm the installation.

## Data storage

Reports and archives are stored in the browser on the device using local storage. They are not synchronized between devices. Export backups regularly. Clearing browser storage or uninstalling the app may remove locally stored records.

## Offline use

The service worker caches the app shell after the first successful online visit. Open the app once while connected to the internet before using it offline.
