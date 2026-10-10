# Tic Tac Toe (Unbeatable AI)

A browser-based Tic Tac Toe game built with vanilla JavaScript where the computer plays unbeatable moves using the **Minimax algorithm**.

## Features

- Human vs AI gameplay
- Unbeatable AI (`X`) powered by Minimax
- Win/lose/tie detection with board highlights
- Replay button to instantly start a new game
- Simple and lightweight (HTML, CSS, JavaScript only)

## How to Run

1. Clone or download this repository.
2. Open `/home/runner/work/Tic_Tac_Toe_unbeatable/Tic_Tac_Toe_unbeatable/index.html` in your browser.

No build step or dependencies are required.

## Gameplay

- You play as **`O`**.
- The AI plays as **`X`**.
- Click any empty cell to make your move.
- The game ends when either side wins or when all cells are filled (tie).

## Project Structure

- `index.html` – game layout and board markup
- `style.css` – visual styling
- `app.js` – game logic and Minimax AI implementation

## Algorithm

The AI uses Minimax to evaluate all possible game outcomes and always choose the optimal move, which makes it impossible to beat.
