# Little Roads

A small road-building puzzle game. Everything runs from `index.html`; the other files
let it install as an app and play offline.

## Put it online with GitHub Pages

1. Sign in at github.com and create a new public repository, for example `little-roads`.
2. Choose "uploading an existing file", drag in every file from this folder, and commit.
3. Open the repository's Settings, then Pages. Under "Build and deployment", pick
   "Deploy from a branch", choose the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two your game is at `https://YOUR-NAME.github.io/little-roads/`.

## Add it to an iPad home screen

Open the link in Safari, tap Share, then Add to Home Screen. It opens full screen and
keeps working offline after the first visit. Saves, scores and settings stay on that device.

## Updating

Replace `index.html` with the new version and change `little-roads-v1` in `sw.js` to
`little-roads-v2` (and so on), so devices that already have the game pick up the update.
