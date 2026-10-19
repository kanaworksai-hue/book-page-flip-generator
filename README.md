# Book Page Flip Generator

A free, browser-based tool that renders a realistic hardcover book with cinematic page-flip animation on a 1920×1080 canvas — and exports it as video or a PNG sequence. Single HTML file, no install, no server.

**Live demo → https://kanaworksai-hue.github.io/book-page-flip-generator/**

![](https://img.shields.io/badge/three.js-r128-blue) ![](https://img.shields.io/badge/license-MIT-green)

## Features

- Realistic round-spine hardcover: paper thickness, soft page bending, gutter shadow, crease shading (all adjustable with sliders)
- Up to 18 scenes; each spread shows one 16:9 image/video across both pages, or separate left/right media
- Video pages: play once at custom speed, freeze on the last frame; adjustable flip timing
- Full camera control: drag to orbit, Shift+drag to rotate the book, wheel to dolly, plus precise sliders
- Timeline: closed book → open → sequential flips → ending, with a skip-intro option
- UI in 中文 / 日本語 / English (switch with one click), built-in user guide (? button)
- Export 1080p video (MP4/WebM, Chrome) or a lossless 30fps PNG sequence

## Usage

Open `index.html` in Chrome or Edge (required for video/PNG export), or use the live demo above. Click the **?** button in the top bar for the full user guide.

## Notes

- Everything runs locally in your browser — media files are never uploaded anywhere.
- `vendor/three.min.js` (Three.js r128, MIT) is bundled; if missing, it is loaded from cdnjs automatically.

## License

MIT © 東京AI映像合同会社
