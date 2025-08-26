# Aquatic Plant Care Kiosk

This is a one-file web app designed for iPad kiosk use (tap plants → see care).

## Quick Deploy (no coding)

### A) Netlify Drop (drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag the entire `plant-kiosk` folder.
3. Netlify gives you a URL like `https://something.netlify.app`.

### B) GitHub Pages
1. Create a new public repo (e.g., `plant-kiosk`).
2. Upload all files/folders from this kit.
3. In repo Settings → Pages → Source: `Deploy from a branch`, Branch: `main` (root).
4. Your site will be `https://<username>.github.io/plant-kiosk/`.

### C) Vercel
1. Import the repo or drag this folder to https://vercel.com/new
2. Accept defaults; deploy. You’ll get a `vercel.app` URL.

## Install to iPad Home Screen
1. Open your site in Safari.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. (Optional) Lock it with Guided Access:
   - Settings → Accessibility → Guided Access → On → set a passcode
   - Open the app → triple‑click Side/Home button → Start
   - To exit, triple‑click → passcode → End

## Edit plant data
Open `index.html` and search for `const PLANTS = [...]`. Edit the array (names, ranges, notes).
Save and redeploy.

## Optional: QR Placard
Use the `placard.png` in this kit to print a simple 8.5x11 sign.
Replace the QR with your final URL using any QR generator (or ask me to regenerate it for you).
