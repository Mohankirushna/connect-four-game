# 🎮 Connect 4 Game (Pygame Edition)

This is a **2-player** version of the classic **Connect 4 game** built with **Python** and **Pygame**.  
Drop your colored discs into the board and be the first to get **4 in a row** — horizontally, vertically, or diagonally!

---

## 🧩 Game Features

- 🧠 **Smart logic** for win detection
- 🎨 **Beautiful UI** with animated disc drops
- 🖱️ Interactive mouse controls
- 👥 Supports **2 players locally**
- 🧱 Real-time visual feedback as you hover over columns

---

## 🎮 How to Play

1. **Run the game**:
```bash
python connect4.py
```
Player 1 (🔴 Red) starts the game.
Hover over a column and click to drop your disc.
Players take turns.
First player to connect 4 pieces wins!
🎉 A winning message is shown, and the game pauses for a few seconds.

📦 Requirements
Python 3.x
Pygame (Install it using pip)
pip install pygame

🧠 Game Logic
Uses a NumPy matrix to represent the game board
Disc placements and checks for:
✅ Horizontal win
✅ Vertical win
✅ Diagonal win (both directions)
Real-time drawing using pygame.draw

draw

🔧 Code Structure
create_board() – Initializes the board matrix
drop_piece() – Places the disc
winning_move() – Checks for winning condition
draw_board() – Draws the board and discs

📄 License
This project is open-source under the MIT License.



