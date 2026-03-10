# The 15 Puzzle
### [Play the 15 Puzzle online](https://avendesta.github.io/15-puzzle/)

A classic 15-tile sliding puzzle game, playable in the browser. Built as a single `index.html` file and deployed via GitHub Pages.

## How to Play

Tiles numbered 1–15 are arranged in a 4×4 grid with one empty space. Click any tile adjacent to the empty space to slide it in. The goal is to arrange all tiles in order from 1 to 15, with the empty space in the bottom-right corner.

```
 1  2  3  4
 5  6  7  8
 9 10 11 12
13 14 15  _
```

## Features

- Move counter and timer
- Best score tracking across sessions
- New Game button to shuffle the board
- Responsive layout for desktop and mobile

## Project Status

This project is being built in phases:

- [x] Phase 1 — UI & layout
- [ ] Phase 2 — Core game logic (tile movement, shuffle, win detection)
- [ ] Phase 3 — Polish & animations
- [ ] Phase 4 — Advanced features (best score, difficulty)
- [ ] Phase 5 — GitHub Pages deployment

## Running Locally

No build tools or dependencies required. Just open `index.html` in your browser:

```bash
git clone https://github.com/your-username/15-puzzle.git
cd 15-puzzle
open index.html
```

## Deployment

This project is deployed via GitHub Pages. To deploy your own fork:

1. Push the repo to GitHub
2. Go to **Settings → Pages**
3. Set the source to the `main` branch, `/ (root)` folder
4. Your game will be live at `https://your-username.github.io/15-puzzle`

## License

MIT
