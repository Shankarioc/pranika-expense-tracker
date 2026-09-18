PRANI EXPENSE TRACKER — PWA UPDATE

Files included:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-384.png
- icons/icon-512.png

This update fixes the PWA installation package:
1. Adds valid 192px/384px/512px PNG app icons.
2. Adds the icons to the web app manifest.
3. Adds scope and id to the manifest.
4. Fixes the service worker cache to use index.html.
5. Updates the service-worker cache version so GitHub Pages can refresh the old cache.

GitHub upload:
Upload all files/folders from this ZIP to the repository root and commit directly to main.
Then wait for GitHub Pages to redeploy.

After deployment on Android Chrome:
- Open the site.
- Refresh once.
- Open Chrome menu (⋮).
- Select "Install app" if shown.
- If the old "This app cannot be installed" message remains, close the old tab/site and reopen the deployed URL after the new GitHub Pages deployment finishes.
