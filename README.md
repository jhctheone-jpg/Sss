# SFS Mini — installable iPhone app

Spaceflight Simulator–style 2D orbit game. Add it to your iPhone home screen.

## Publish on GitHub Pages (free HTTPS)

1. Create a new GitHub repo (example name: `sfs-mini`).
2. Upload every file in this folder to the repo **root**:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `apple-touch-icon.png`
   - `.nojekyll`
3. Repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Save
4. Wait a minute. Your app URL will be:

   `https://YOUR_USERNAME.github.io/sfs-mini/`

## Install on iPhone

1. Open that URL in **Safari** (not Chrome).
2. Tap the **Share** button.
3. Tap **Add to Home Screen**.
4. Tap **Add**.
5. Open **SFS Mini** from the home screen.

It launches fullscreen like a normal app and works offline after the first visit.

## Play

- **Launch** starts the flight.
- Hold **IGNITE** for thrust (or W / Space).
- **◀ ▶** rotate (or A / D).
- Goal: periapsis above 80 km without hitting the ground too hard.
