# English Coach — Teacher-Guided Lessons v3

This update replaces the previous lesson content with 10 new practice sentences based on the three teacher PDFs uploaded by the user.

## Deploy to GitHub Pages (phone-friendly)
1. Download and unzip this package on your phone.
2. Open https://github.com/chrishuang183/EnglishCoach
3. Tap **Add file** → **Upload files**.
4. Select all files inside this folder and upload them to the repository root (not the folder itself).
5. Allow GitHub to replace files with the same names, then tap **Commit changes**.
6. Wait for GitHub Pages to finish updating. Open https://chrishuang183.github.io/EnglishCoach/ in Chrome and refresh.
7. If the old lesson list remains, close the installed PWA and reopen it; the service-worker cache has been bumped to v3.

Files to upload: index.html, styles.css, app.js, lessons.json, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.

## What's new
- 10 lessons: 5 workplace English, 3 teacher-guided weakness drills, 2 daily-life sentences.
- Prioritizes shorter spoken chunks, pauses instead of repeated and/so, it/them pronoun swaps, natural transitions, presentation language and Q&A.
- Keeps Listen ×3, Speak ×3 tracking, Chinese translations, notes, examples and local progress.

Speech recognition depends on Chrome/device services. Word match is only a rough text comparison, not a pronunciation score. Progress remains in browser localStorage. Do not upload private teacher PDFs or confidential company information to the public repository.
