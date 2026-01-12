# GalactaGest

Galacta game played with gestures.

A cyberpunk, hand‑controlled Galaga‑style shooter built with Three.js and MediaPipe Hands. Use your right hand to steer, pinch to fire, and pinch‑hold to pause.

## How to Play
- Move: right hand index finger left/right.
- Fire: quick pinch (thumb + index).
- Pause/Resume: hold a pinch.
- Restart: pinch after Game Over.
- Name entry: move to choose a letter, pinch to add, 2 fingers to delete, 5 fingers to confirm.

## Run Locally
```bash
python3 -m http.server
```
Then open: `http://localhost:8000/index.html`

## Notes
- Camera access requires HTTPS or `localhost`.
- MediaPipe + Three.js are loaded from CDN.

## Deploy
This is a static site. You can deploy to Netlify, Vercel, or GitHub Pages by uploading or connecting the repo.
