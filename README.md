# Merry Morel Arcade

The launcher page for the games at https://merrymorel.github.io/ — Dino Island, Big Cat Island, Moto Stadium and Wild Shot.

This repo must be named `merrymorel.github.io`; GitHub Pages publishes it from `main` automatically. Add the page to the Home Screen and every game is one tap away.

## Files
- `index.html` — the arcade: Merry Morel sign, four wooden game cards with pixel-art badges
- `logo-anim.webp` / `logo-anim.gif` — the animated banner at native resolution (248×125, 20 frames, 2.6 s). WebP is served first (40 KB); the GIF (261 KB) is the fallback. Both are pixel-identical to the 1240×625 source, which was an exact 5× nearest-neighbour upscale — the browser does that scaling instead.
- `logo.png` — the still banner, shown when the device asks for reduced motion
- `icon-192/512.png`, `apple-touch-icon.png` — the gold **M** badge from the sign, on forest dark
- `spores.png` — tiling gold-dust overlay
- `sw.js` — service worker: network-first for the page, cached for offline. Bump `CACHE` after any change.
