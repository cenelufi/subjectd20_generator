# Art Quest — Drawing RPG

A responsive drawing prompt RPG for desktop and mobile.

## Included
- `index.html` — main app, Simple/Complex subject generator, D20, XP and quest journal
- `manifest.webmanifest` — installable PWA configuration
- `sw.js` — offline caching
- `icon.svg` — app icon

## Deploy with GitHub Pages
1. Extract this ZIP.
2. Upload the **contents** of this folder to the root of your GitHub repository (not the ZIP itself).
3. In GitHub, open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Open `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

The app is configured to use relative paths so it can work from a GitHub Pages project subpath.

## Features
- Simple and Complex subject generation
- D20 random challenge modifiers
- Difficulty tiers, XP, ranks, and quest journal
- Customizable Spin the Wheel randomizer
- Customizable three-reel Slot Machine randomizer
- Send slot-machine combinations to the main quest
- Browser-local saving for app progress and randomizer options
- Responsive layout and basic offline caching

## Install on mobile
After deployment, open the site in a supported mobile browser and use its browser menu's **Add to Home Screen** / **Install app** option. PWA installation and offline behavior require HTTPS, which GitHub Pages provides.
