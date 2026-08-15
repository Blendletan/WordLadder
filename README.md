# Word Ladder — Daily Puzzle

A clean, Wordle-inspired daily **word ladder** game.

## How it works

- You are given a start word and an end word (both 5 letters).
- Fill in the intermediate words so that **each consecutive pair differs by exactly one letter**.
- Every word must be a valid English word from the curated list.
- Each day’s puzzle has **exactly one shortest solution** of the given length (usually 7 steps).

## Play

Open `index.html` in a browser, or host the folder on GitHub Pages.

After solving you get a **Share** button that copies a Wordle-style result (green squares + puzzle number) to your clipboard — perfect for posting on X, Discord, etc.

## Technical notes

- Pure static site (HTML + CSS + JS). No backend.
- Daily puzzle is selected deterministically from the current UTC date.
- Word list ≈ 2,300 common 5-letter words (Wordle answer set).
- All puzzles were pre-computed to have a unique shortest path.

## Files

- `index.html` — the complete game
- `data.js` — puzzle list + word set

Enjoy climbing the ladder!
