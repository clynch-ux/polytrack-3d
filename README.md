# Lowpoly Lap

A small browser-based 3D low-poly time-trial racer inspired by the genre of arcade track racers. It uses Three.js from a CDN and needs no build step.

## Play locally

Open `index.html` in a modern browser with an internet connection. If your browser blocks ES modules from `file://`, run a local static server from this folder, for example:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

- **W / Up:** accelerate
- **S / Down:** brake
- **A, D / Left, Right:** steer
- **Space:** handbrake
- **R:** restart countdown / run

The game includes a procedural 3D road, a blocky player car, checkpoints, a countdown, a lap timer, and a best-time record stored in your browser.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. Once the Pages deployment finishes, the game will be available at `https://clynch-ux.github.io/polytrack-3d/`.
