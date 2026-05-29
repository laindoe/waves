# WAVES App — GitHub Pages Setup

## Files in this project
- `index.html` — the full app
- `manifest.json` — PWA manifest (makes it installable)
- `sw.js` — service worker (enables offline use)
- `icon-192.png` — app icon 192x192 (add your own)
- `icon-512.png` — app icon 512x512 (add your own)

## Deploy to GitHub Pages

1. Create a new repo on github.com (e.g. `waves-app`)
2. In terminal inside your project folder:
```
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOURUSERNAME/waves-app.git
git push -u origin main
```
3. On GitHub: go to repo → Settings → Pages
4. Source: Deploy from branch → main → / (root) → Save
5. Your app will be live at: https://laindoe.github.io/waves

## Add to Home Screen (iPhone)
1. Open your GitHub Pages URL in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"
4. Tap Add — WAVES icon appears on your home screen

## Add app icons
Replace icon-192.png and icon-512.png with your actual WAVES logo
exported at those sizes. Without them the PWA still works but
uses a default browser icon.
