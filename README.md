# LifeLedger v1

A lightweight, mobile-friendly personal finance tracker for Singapore (SGD).

## Run locally
- Extract the ZIP.
- Open `index.html` in a modern browser.
- Your records are saved in that browser on that device using localStorage.

## Install on iPhone as a home-screen app
For the installable PWA experience, host the contents of this folder on an HTTPS website (for example, GitHub Pages or another static host).
1. Open the hosted URL in Safari on your iPhone.
2. Tap Share.
3. Choose **Add to Home Screen**.

Opening the HTML file directly is useful for testing, but service-worker/offline installation requires HTTPS (or localhost).

## Data and privacy
- Data stays in the browser's local storage; there is no server or bank connection.
- Export a JSON backup regularly. CSV export is available for transactions.
- Import a JSON backup to restore it on another device.
- This prototype does not encrypt local records. Avoid using it on a shared device.
- CPF, debt, savings and BTO figures are manually entered estimates. This is not financial advice.

## Files
- `index.html` — complete app
- `manifest.webmanifest` — install metadata
- `sw.js` — offline cache
- `icon.svg` — app icon
