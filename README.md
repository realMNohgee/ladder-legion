# Ladder Legion 🪜

![License](https://img.shields.io/badge/license-MIT-blue.svg)

**A Donkey Kong-style arcade game** — climb the ladders, dodge the rolling barrels, and reach the top to clear each level.

A single-file browser game built from scratch on HTML5 canvas with vanilla JavaScript, in a retro pixel-art style.

## How to play

| Key | Action |
|---|---|
| ← → / A D | Move left / right |
| ↑ / W | Climb up a ladder |
| ↓ / S | Climb down a ladder |
| Space / J | Jump |
| Enter | Start / play again |

- **Goal:** reach the top platform (the "HELP!" goal) to clear the level and advance.
- **Barrels** roll down the platforms and ladders — touching one costs a life.
- **Hammer power-up (🔨):** grab it to smash barrels for ~5 seconds instead of getting hit.
- You start with **3 lives**. Each cleared level raises the difficulty.

## Tech stack

- Single-file **HTML5 `<canvas>`** + **vanilla JavaScript**.
- Retro pixel-art look (Press Start 2P font, `image-rendering: pixelated`), drawn entirely in code — no image assets.
- No build step, no dependencies — just open `index.html`.

## Run locally

```bash
git clone git@github.com:realMNohgee/ladder-legion.git
cd ladder-legion
open index.html
```

## License

MIT — see [LICENSE](LICENSE).
