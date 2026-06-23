# 🦖 Dino Runner

A faithful recreation of the **Chrome offline T-Rex Runner** — the game that appears
when your browser loses its connection. Single HTML file, vanilla JavaScript, an HTML5
canvas, and zero dependencies. It works completely offline (fitting).

**▶️ Play it:** https://dino-go.vercel.app

## Controls

| Action | Keys |
| --- | --- |
| Jump | `Space` · `↑` · click · tap |
| Duck | `↓` |
| Restart | `Space` (after game over) |

## Features

- Pixel-art T-Rex with an animated running gait
- Cacti (singles + clusters) and pterodactyls that appear once you pick up speed
- Speed ramps up the longer you survive
- Persistent high score (saved in the browser via `localStorage`)
- Day → night mode flip as your score climbs

## Run locally

It's a static file — just open it:

```sh
open index.html          # macOS
# or serve it:
python3 -m http.server   # then visit http://localhost:8000
```

## License & provenance

This is an **original, clean-room implementation** — no Google sprites or source code are
used; the dinosaur and obstacles are drawn procedurally. It is an homage to Google Chrome's
T-Rex Runner, which ships as part of the [Chromium](https://www.chromium.org/) project.

Accordingly, this project is released under the **[BSD 3-Clause License](LICENSE)** — the same
license Chromium itself uses — so the lineage is clear to anyone reading the source.
