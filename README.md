# 🎮 Tetris Game

A simple Tetris clone built using **vanilla JavaScript** and the **HTML5 Canvas API**. Includes keyboard controls, score tracking, block rotation, line clearing, and background music.

## 🚀 Features

- Classic Tetris gameplay with 7 unique pieces
- Keyboard controls for movement and rotation
- Gravity (automatic falling blocks)
- Line clearing and score system
- Game over detection
- Background music playback

## 🎮 Controls

| Key             | Action               |
|------------------|------------------------|
| ⬅️ Arrow Left      | Move piece left        |
| ➡️ Arrow Right     | Move piece right       |
| ⬇️ Arrow Down      | Move piece down faster |
| ⬆️ Arrow Up        | Rotate piece           |

## 🧱 How It Works

- The game is rendered on an HTML `<canvas>`, scaled with a fixed block size.
- Pieces fall automatically at a timed interval.
- Collision detection prevents pieces from overlapping.
- Completed rows are removed and the score is updated.
- A random piece is selected after each drop.
- Game ends when a new piece collides at the top.


## ▶️ Getting Started

   ```bash
   git clone https://github.com/your-username/tetris-js.git
   cd tetris-js
   npm install
   npm run dev
