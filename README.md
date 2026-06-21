# 🕹️ Arcade Vault

A collection of 4 classic browser games built from scratch with HTML5 Canvas and Vanilla JavaScript. No frameworks, no libraries, no installs — just open and play.

🔗 **[Play Live on GitHub Pages](https://Harshitmaheshwari10.github.io/arcade-vault)**

---

## 🎮 Games

| Game | Type | Controls |
|------|------|----------|
| 🐍 Snake | Classic | WASD / Arrow keys |
| 🚀 Space Shooter | Action | ← → Arrow keys + Space |
| ⭕ Tic Tac Toe | Strategy | Mouse click |
| 🏃 Endless Runner | Endless | Space / ↑ to jump |

---

## ✨ Features

- **Snake** — Grows with food, speed increases per level, high score tracking, directional eyes
- **Space Shooter** — Wave-based asteroids, lives system, triple-shot power-up, particle explosions
- **Tic Tac Toe** — Unbeatable AI (minimax algorithm) + 2-player local mode, score tracking
- **Endless Runner** — Double jump, speed ramps up over time, animated character with running legs

---

## 🚀 How to Run

### Option 1 — Just open in browser
```bash
git clone https://github.com/Harshitmaheshwari10/arcade-vault.git
cd arcade-vault
open index.html   # or double-click index.html
```

### Option 2 — Local server
```bash
cd arcade-vault
python -m http.server 8000
# Open http://localhost:8000
```

### Option 3 — GitHub Pages (live demo)
Push to GitHub and enable Pages from `Settings → Pages → main branch / root`.

---

## 📁 Project Structure

```
arcade-vault/
│
├── index.html          # Hub / landing page
├── snake.html          # Snake game
├── shooter.html        # Space Shooter game
├── tictactoe.html      # Tic Tac Toe game (vs AI + 2P)
├── runner.html         # Endless Runner game
├── .gitignore
└── README.md
```

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — game rendering
- **Vanilla JavaScript** — game logic, physics, AI
- **CSS3** — dark UI theme, animations
- **Google Fonts** — Press Start 2P (pixel font) + Inter

---

## 🧠 AI in Tic Tac Toe

The AI uses the **Minimax algorithm with Alpha-Beta pruning** — it plays perfectly and cannot be beaten, only drawn. Switch to 2-player mode to play against a friend instead.

---

## 🙋‍♂️ Author

**Harshit Maheshwari**  
B.Tech IT — Manipal University Jaipur  
[GitHub](https://github.com/Harshitmaheshwari10) · [LinkedIn](https://linkedin.com/in/harshitmaheshwari10)

---

## 📄 License

MIT License — feel free to fork and build on it.
