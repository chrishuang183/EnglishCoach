# English Coach PWA deployment

Upload these files directly to the ROOT of `chrishuang183/EnglishCoach` on branch `main`:
- index.html
- styles.css
- app.js
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

On GitHub: Add file -> Upload files -> select all seven files -> Commit changes.
Do not upload the ZIP itself and do not put the files in a subfolder.

Then repository Settings -> Pages -> Build and deployment:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)
- Save

Expected URL: https://chrishuang183.github.io/EnglishCoach/

Open the URL in Chrome on Android. Use Chrome menu -> Install app or Add to Home screen.

Privacy/limits: no backend or API key. Progress is saved only in this browser's localStorage. Speech recognition depends on the browser/device speech service, may require internet, and may process audio through that service. The displayed word-match percentage is a rough text comparison, not pronunciation scoring. GitHub Pages is public hosting; do not commit private information.
