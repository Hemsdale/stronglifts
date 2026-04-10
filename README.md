# 5×5 StrongLifts Tracker — PWA Setup

## Deploy to GitHub Pages (2 minutes)

1. Go to https://github.com/new and create a repo named `stronglifts`
2. Upload all 5 files from this zip (index.html, manifest.json, sw.js, icon-192.png, icon-512.png)
3. Go to repo Settings → Pages → Source: "Deploy from a branch" → Branch: main → Save
4. Wait ~60 seconds, then visit: `https://YOUR-USERNAME.github.io/stronglifts/`
5. Chrome will show "Install app" in the address bar or menu — tap it

## That's it

The app installs to your home screen with its own icon. Runs fullscreen, no browser chrome.
Works completely offline after first load. All data saved in localStorage on your device.

## Files

- `index.html` — the full app (vanilla JS, zero dependencies)
- `manifest.json` — tells Chrome this is an installable app
- `sw.js` — service worker for offline caching
- `icon-192.png` — app icon (home screen)
- `icon-512.png` — app icon (splash screen)
