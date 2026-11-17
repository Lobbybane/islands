# Floating Island

A stylized low-poly floating island in the sky, built as a single `index.html` with three.js r170. Every model, texture and sound is generated in code. There are no other assets.

Open `index.html` in a modern browser. It loads three.js from unpkg, so it needs an internet connection.

| Control | Key | What it does |
|---|---|---|
| Day / Night | `D` | 3-second transition. At night the windows glow, stars appear and fireflies come out |
| Weather | `W` | Cycles Clear → Rain → Snow, with matching particles, sky and wind |
| Grow | `G` | Plants a tree at a random free spot, with a growing animation |
| Explode | `E` | Splits the island into labelled floating layers. Press again to put it back together |
| Sound | `M` | Turns the generated ambient audio on or off |

Drag to orbit and scroll to zoom. The camera slowly auto-rotates when you leave it alone.
