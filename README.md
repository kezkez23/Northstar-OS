# Northstar V3

A free, iPhone-friendly personal tracker that runs as a static website/PWA.

## Files
- `index.html` — complete app
- `manifest.json` — Home Screen app metadata
- `sw.js` — offline app shell cache
- `icon.svg` — app icon
- Includes body measurements, editable daily tasks, set-by-set gym history, previous-session comparisons, strength chart, timer, meals/photos/macros, water, boxing, running, sleep, calendar, GCSE study, goals, spending, reports and backup/restore.

## Publish on GitHub Pages
1. Create a public repository.
2. Upload the four files directly into the repository root (do not upload only the ZIP).
3. In Settings → Pages, choose Deploy from a branch, `main`, and `/(root)`.
4. Open the published HTTPS site in Safari → Share → Add to Home Screen.

## Storage and limitations
Data is saved in browser localStorage on the device/browser. Export backups in Reports regularly. Browser storage can be lost if website data is cleared. This app does not sync across devices.
Food-photo macro recognition is not included: enter macros from food labels or a nutrition database. Photos are stored locally in browser storage and may use significant space.
The app is provided as a local-first personal tracker, not a medical or training prescription.
