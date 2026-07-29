# AR Gestures

Real-time hand-tracking demo that maps five gestures to elemental visual effects, rendered on a canvas overlay anchored to the palm.

Built with MediaPipe Hands and Canvas 2D — no marker, no app install, runs in the browser.

## Run it

```bash
python -m http.server 8181
```

Then open `http://localhost:8181` and allow camera access.

## Gestures

| Gesture | Effect |
|---|---|
| Open palm | Wind |
| Fist | Earth |
| Point (index) | Lightning — anchors to fingertip |
| Pinch | Ice |
| Peace sign | Fire |

Hold each gesture for ~0.3s to activate. The effect follows your hand as you move.

## Stack

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands) — landmark detection
- Canvas 2D — particle rendering
- No build step, no dependencies to install
