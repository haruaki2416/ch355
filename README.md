# CH355

A client-side chess playground designed for static hosting.

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static web server.

## Deploy

No build command is required. Set the static site publish/root directory to the repository root and deploy `index.html`.

## Current foundation

- Interactive legal chess moves powered by chess.js
- Human vs computer and local two-player modes
- Browser-side minimax opponent with selectable difficulty presets
- Move history, undo, board flip, hints and position material evaluation
- Board color themes and piece display styles
- Local rating and game statistics stored in localStorage

## Notes

CH355 has no application server or database. The chess rules library is loaded from esm.sh, so the first load requires an internet connection. The current built-in opponent is a lightweight minimax engine, not Stockfish. Elo presets are approximate difficulty labels, and the local rating is a game-progress score rather than an official online rating.

## Roadmap

- Stockfish WebAssembly integration and analysis panel
- Additional board and piece themes
- Game review, opening explorer and PGN import/export
- Puzzle mode and daily challenges
- Local profile, rating graph and achievements
