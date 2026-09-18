PRANI EXPENSE TRACKER — PWA

Files:
- index.html
- manifest.webmanifest
- sw.js
- icons/icon-192.png
- icons/icon-512.png

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to install.
Opening index.html directly with file:// will not provide normal PWA installation.

For Android Chrome:
1. Upload this folder to an HTTPS web host.
2. Open the HTTPS address in Chrome.
3. Use the browser's "Install app" / "Add to Home screen" option.
4. The app opens in standalone mode.

The existing expense tracker UI/data logic is preserved; this package adds the PWA manifest,
service worker, install prompt, and app icons.
