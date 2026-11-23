# [Orrery](https://orrery-c1v.pages.dev/)

**Live: [https://orrery-c1v.pages.dev/](https://orrery-c1v.pages.dev/)**

An interactive Keplerian solar system in your browser: shaded planets, twin-tailed comets and procedural sound. Pure canvas, one file, no dependencies.

## Features

- The eight planets and Pluto move on Kepler orbits: they fall toward the Sun and are fastest at perihelion. Switch **Kepler motion** off to compare with uniform circular motion.
- Asteroid belt, Kuiper belt, particle rings for Saturn and Uranus, and the Moon (visible when you zoom in).
- Comets with separate ion and dust tails. Summon a new one at any time.
- Four colour palettes with optional automatic switching.
- Procedural sound built with the Web Audio API: space drone, solar wind, orbit chimes and comet shimmer. Off by default.
- Four languages: English, Hungarian, Romanian and German.
- Photo export (PNG), shareable links and a hands-free projector mode.
- Works on phones and with the keyboard, and respects the reduced-motion setting.

## Controls

| Input | Action |
|---|---|
| Drag | Pan |
| Wheel or pinch | Zoom |
| Click or tap a body | Follow it and show its info |
| `1`–`8` | Follow a planet |
| `C` | Summon a comet |
| `Space` | Projector mode |
| `P` | Save a photo |
| `M` | Sound on/off |
| `F` | Fullscreen |
| `H` | Hide the UI |
| `Esc` | Release the followed body / leave projector mode |

## Share a view

The **Copy link** button (Visuals tab) stores the current view in the URL: seed, speed, tilt, zoom, toggles and palette. The `seed` makes the starfield, the planet positions and the first comets repeatable. Example: `?seed=42&pal=2&zoom=2` (palettes are numbered 0–3).

## Run locally

Open `index.html` in a browser. There is no build step: it is vanilla JavaScript with Canvas 2D and the Web Audio API.

## License

MIT, see [LICENSE](LICENSE).
