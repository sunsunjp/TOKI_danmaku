# TOKI Danmaku Game

A minimalist, frame-rate–independent bullet-dodging game that runs in modern browsers (Chrome/Firefox). Pure static site—no build tools required.

---

## Overview

- **Player:** green circle hitbox, loaded from `player.png`
- **Movement:** keyboard (WASD / Arrow keys) and **drag-follow** (mouse/touch) with a capped speed
- **Bullets:** circular shots with **ring**, **spiral**, and **aimed** patterns
- **HUD:** **Game Over** overlay shows your survival time
- **QoL:** `P` to pause, `R` to restart
- **Difficulty:** time-based scaling

**Project structure**
/ (repo root)
├─ index.html      # Game code (HTML + JS)
└─ player.png      # Player sprite (any PNG/JPG)

**GitHub Pages**
* Repo → **Settings → Pages**
* Source: **Deploy from a branch**
* Branch: `main` / **/(root)**
* Publish URL: `https://<your-username>.github.io/<your-repo>/`

---

## How to Play
* **Goal:** Survive as long as possible while dodging bullets.
* **Move:** `WASD` or `↑ ↓ ← →`
* **Drag-follow:** Hold/touch on the canvas; the player moves toward the pointer each frame (with a speed cap to avoid teleporting through bullets).
* **Pause:** `P`
* **Restart:** `R`

---

## License

