# UMoffPen2Player

UMoffPen2Player is a browser-based viewer for UMoffPen2 save strings.
Paste a `UMSD[...]` save string from UMoffPen2, render the canvas locally in the browser, and export a 1920x1080 PNG or MP4/H.264 timelapse video.

## Use

Open `index.html` in a browser, or use the GitHub Pages site after deployment.
All rendering runs in the browser. The save string is not uploaded to a server by this static app.

## Features

- Render UMoffPen2 `UMSD` save data to a 1920x1080 canvas.
- Load a `.txt` save file.
- Export PNG.
- Export 30 fps MP4/H.264 timelapse video at 1/1, 1/2, or 1/4 resolution when the browser supports MP4/H.264 `MediaRecorder`.
- Video encoding uses the browser's built-in encoder. This project does not bundle an H.264 encoder.

## Development

This repository is intentionally dependency-free. The site is a static HTML application, so local testing can be done by opening `index.html` directly or by serving the folder with any static file server.

## GitHub Pages

The included workflow deploys the repository root to GitHub Pages on pushes to `main`.
In the repository settings, set Pages source to GitHub Actions if it is not selected automatically.

## License

UMoffPen2Player is not open source software.

Use is permitted only through the official public page provided by the rights holder. Redistribution, re-hosting, publishing modified versions, and incorporation into other products or services are prohibited without prior written permission.

Rights holder: はい (`hy` in English contexts)

See [LICENSE](LICENSE) for the full terms. This license applies only to UMoffPen2Player and does not license UMoffPen2, UMoffPen2 assets, manuals, packages, prefabs, user save data, or other related materials.
