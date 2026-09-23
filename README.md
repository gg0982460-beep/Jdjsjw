# Casa Music — PWA Offline Player

## What changed
- Installable as a PWA on Android.
- App shell is cached by a service worker.
- Works without internet after installation.
- Songs are still stored locally in IndexedDB, so imported audio can play offline.
- Added an install button when the browser exposes the PWA install prompt.

## Important
The PWA itself must be opened from HTTPS (or localhost) for service workers to work.
Uploading this folder to GitHub Pages, Netlify, Vercel, or another HTTPS host will work.

On Android Chrome:
1. Open the hosted app.
2. Tap the install button in Casa, or Chrome menu → Install app / Add to Home screen.
3. Add your MP3/WAV/M4A/FLAC/OGG files inside Casa.
4. Once imported, they remain in the browser's local IndexedDB storage and can be played offline.

Do not clear the browser/site data, because that can remove the locally stored songs.
