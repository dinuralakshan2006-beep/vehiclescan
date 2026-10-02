# TECH HUB LK — Version 1

## Files
- `index.html` — main app (search, notes, calculators, OBD-II code sample library, saved items)
- `manifest.json` — installable web app metadata
- `sw.js` — basic offline cache

## Publish with GitHub Pages using a phone
1. Open your repository: https://github.com/dinuralakshan2006-beep/vehiclescan
2. Tap **Add file** → **Upload files**.
3. Upload all three files from this folder: `index.html`, `manifest.json`, and `sw.js`.
4. Commit changes to the `main` branch.
5. Open Settings → Pages and ensure source is **Deploy from a branch**, branch `main`, folder `/(root)`.
6. Wait a few minutes and open: https://dinuralakshan2006-beep.github.io/vehiclescan/
7. On iPhone Safari, use Share → Add to Home Screen. On Android Chrome, use menu → Install app / Add to Home screen.

## Important limitations
- This is a starter prototype with a small sample learning library, not a complete technical encyclopedia.
- Saved items use browser local storage and stay on that device/browser.
- OBD-II descriptions are generic educational hints, not a definitive diagnosis. Always verify with the exact vehicle service manual.
- This app does not yet connect to a real ECU or read live OBD-II data.
- Offline use works after the app has loaded online once, and browser caching support may vary.
