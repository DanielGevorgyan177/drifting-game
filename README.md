# Drift free roam

A single-page, top-down drifting game that runs in the browser and works offline. Drive around an open town with winding roads, buildings, and two plazas: one open space for drifting and one with cones for practice.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Steer | Arrow keys or A / D | On-screen ◀ ▶ |
| Gas / brake | Up / Down or W / S | On-screen ▲ ▼ |
| Drift (handbrake) | Space or Shift | Drift button |
| Drift assist on/off | T | "Drift assist" chip |

Tap or click the minimap to enlarge it.

## Put it on GitHub Pages

1. Create a new repository on GitHub.
2. Upload all of these files to the top level of the repository (Add file, then Upload files): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`.
3. Go to Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the game is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Add to home screen and play offline

Open the live link once while online and let it load. Then:

- **iPhone (Safari):** Share button, then Add to Home Screen.
- **Android (Chrome):** menu, then Install app (or Add to Home screen).

After that it opens like an app and works with no connection. If you update the files on GitHub, open the game online once and then once more to get the new version.

Offline mode needs the https link from GitHub Pages, so it will not work if you open `index.html` straight from your files.
