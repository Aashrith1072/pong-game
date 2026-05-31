# 🏓 Pong Game

A classic two-player Pong game built with **Python** and the **Turtle** graphics library.

---

## 🎮 Gameplay

Two players compete by bouncing a ball back and forth. If you miss the ball, your opponent scores a point. The ball speeds up with every successful paddle hit!

---

## 🕹️ Controls

| Player | Move Up | Move Down |
|--------|---------|-----------|
| Left (Player 1) | `W` | `S` |
| Right (Player 2) | `↑` | `↓` |

---

## 📁 Project Structure

```
pong-game/
│
├── main.py          # Game loop and screen setup
├── paddle.py        # Paddle class
├── ball.py          # Ball class with movement and bounce logic
├── scoreboard.py    # Scoreboard class to track and display scores
└── README.md
```

---

## 🚀 How to Run

### Prerequisites
- Python 3.x installed — [Download here](https://www.python.org/downloads/)
- No external libraries needed (`turtle` is built into Python)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/pong-game.git

# 2. Navigate into the folder
cd pong-game

# 3. Run the game
python main.py
```

---

## ✨ Features

- Smooth real-time ball movement
- Ball speeds up on every paddle hit
- Score resets ball to center after each miss
- Live scoreboard displayed throughout the game

---

## 🛠️ Built With

- [Python 3](https://www.python.org/)
- [Turtle Graphics](https://docs.python.org/3/library/turtle.html) — standard library

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
