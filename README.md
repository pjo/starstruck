# ⭐ Starstruck

A tiny, fast arcade game in a single HTML file. Steer a comet with your mouse or
finger, catch stars to chain combos, dodge asteroids, and grab gold stars for a
shield — or something better.

**▶️ [Play it here](https://pjo.github.io/starstruck/)**

## How to play

- **Move** — mouse, touch, or arrow keys / `WASD`
- **Catch stars** — chain them within the combo window to score up to **×8**
- **Gold stars** — grant a shield, or trigger a **STARSTRUCK!** frenzy
- **Dodge asteroids** — a hit costs a life (or your shield)
- **Pause** — `P` or `Esc`

Your best score is saved locally in the browser.

## Tech

No build step, no dependencies. Everything — rendering (Canvas 2D), procedural
audio (Web Audio API), and game logic — lives in [`index.html`](index.html).
Just open the file in a browser to play.

## Development

```sh
# Serve locally (any static server works)
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Pushing to `main` automatically publishes to GitHub Pages via the workflow in
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml).

## License

[MIT](LICENSE)
