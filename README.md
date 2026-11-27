# Divine Wedding — Captured Reference Project

This folder contains a cleaned copy of the WebScrapBook capture you uploaded. The original captured HTML and its relative resource filenames have been preserved at the project root so that existing references are less likely to break.

## Important notes

- This is a browser-captured reference, not the original editable source repository.
- Some scripts/resources may still depend on the original website, browser context, cookies, APIs, or network access.
- The archive includes WordPress/commerce/analytics resources in addition to invitation assets. They have been preserved in this reference package because removing dependencies without testing could break behavior.
- `index_1.html` was an empty `about:blank` capture and was omitted.
- No wedding details have been replaced with dummy data.
- The captured page contains inconsistent dates/venues across sections. Treat the captured HTML as source material and verify before publishing.
- Use only assets you are permitted to reuse in a public website.

## How to inspect

1. Extract this ZIP to a folder.
2. Open `index.html` in Chrome to inspect the capture.
3. If local JavaScript modules or browser security restrictions prevent parts from working, try a simple local static server or use the original live page for comparison. No Node.js build process is required for the project itself.
4. Open Chrome DevTools (`F12`) and check Console/Network for missing resources.

## Captured content detected

- Couple names: Kapil Sharma and Sapna Sharma
- Couple portraits: `groom.png`, `bride.png`
- Gallery images: `gallery-1.png` through `gallery-6.png`
- Videos: `divine-wedding1.mp4`, `ganesha.mp4`
- Decorative assets: floral corner, Ganesha image, rangoli, elephants, venue/event images, SVG ornaments
- Interaction scripts: `animations.js`, `cover-video.js`, `hero-video.js`, `scratch-card.js`, `gallery-lightbox.js`, `gallery-coverflow.js`, `fireworks.js`, and `music-toggle.js`

## File structure

The resources remain at the root in this first pass to preserve existing relative references. They can be moved into `css/`, `js/`, and `assets/` after dependency paths are audited and the page is tested.
