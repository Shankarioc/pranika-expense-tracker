# Pranika Expense Tracker — Mobile App

## Recommended deployment
Host this folder on an HTTPS web host (for example GitHub Pages). Open the URL on Android Chrome and choose:
Menu -> Add to Home screen / Install app.

## Automatic code updates
The service worker uses a network-first strategy. When you publish a new index.html,
the installed PWA fetches the new code when online and updates its cache. The next
load uses the latest published version.

For a stronger release workflow, change APP_VERSION in sw.js for each release:
APP_VERSION = "pranika-v2", "pranika-v3", etc.

## Important
Google Sheets/Drive synchronization still uses the Google Apps Script Web App URL
already configured in the HTML. Keep that backend deployed and accessible.

## Data safety
Keep Google Sheets as the cloud data source and Google Drive as backup. Do not rely
only on browser storage.
