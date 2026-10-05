# AR Gestures

Real-time hand-tracking demo that maps five gestures to elemental visual effects, rendered on a canvas overlay anchored to the palm.

Built with MediaPipe Hands and Canvas 2D, and runs in the browser.

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
| Point Up (index) | Lightning |
| Pinch | Ice |
| Peace sign | Fire |

Hold a gesture briefly to activate its effect. The effect follows your hand as you move.

## Stack

- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands): landmark detection
- Canvas 2D: particle rendering
- No build step, no dependencies to install
