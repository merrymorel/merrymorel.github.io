# Merry Morel Arcade

The launcher page for the games at https://merrymorel.github.io/ — Dino Island, Big Cat Island, Moto Stadium and Wild Shot.

This repo must be named `merrymorel.github.io`; GitHub Pages publishes it from `main` automatically. Add the page to the Home Screen and every game is one tap away.

## Files
- `index.html` — the arcade: Merry Morel sign, four wooden game cards with pixel-art badges
- `logo.png` — the Merry Morel banner at native resolution (248×125); the browser scales it with `image-rendering: pixelated`, so it stays crisp at any size
- `icon-192/512.png`, `apple-touch-icon.png` — the gold **M** badge from the sign, on forest dark
- `spores.png` — tiling gold-dust overlay
- `sw.js` — service worker: network-first for the page, cached for offline. Bump `CACHE` after any change.
