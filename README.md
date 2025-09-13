# Snake — 1‑Page Vanilla JS

A minimal, single‑file Snake game built with HTML5 Canvas and vanilla JavaScript. No build tools, no dependencies — just open `index.html` in a browser and play.

## Features

- Smooth, grid‑based snake movement
- Keyboard controls: Arrow keys or WASD
- Pause/Resume with Space, Restart with R
- Score + persistent High Score (localStorage)
- Subtle visuals with rounded segments and grid

## Play Locally

Option 1 — Double‑click `index.html` to open in your browser.

Option 2 — Serve locally (avoids any file‑URL restrictions):

```bash
cd snake-game
python3 -m http.server 8080
# open http://localhost:8080
```

## Controls

- Move: Arrow keys or WASD
- Pause/Resume: Space
- Restart: R

## Deploy to GitHub Pages

1. Create a GitHub repository (e.g., `snake-game`).
2. Push this folder’s contents to the repo’s `main` branch.
3. In the repository settings, enable GitHub Pages:
   - Build and deployment → Source: “Deploy from a branch”
   - Branch: `main` and folder: `/ (root)`
4. Your game will be live at `https://<your-username>.github.io/<repo-name>/`.

## Project Structure

```
snake-game/
├─ index.html    # Single page app (HTML/CSS/JS)
├─ README.md
├─ LICENSE
└─ .gitignore
```

## License

MIT — see `LICENSE` for details.

