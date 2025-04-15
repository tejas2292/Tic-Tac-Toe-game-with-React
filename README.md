# 🕹️ Tic Tac Toe Game – React

A simple and interactive **Tic Tac Toe** game built using **React**. The game allows two players to play turn-by-turn and provides live status updates, win/draw detection, and a reset feature.

---

## 🚀 Live Demo

> Coming soon...

---

## 📸 Screenshot

![screenshot](./screenshot.png) <!-- Replace with actual screenshot path if available -->

---

## 🧠 Features

- 3x3 grid interactive board
- Turn-based gameplay (X and O)
- Live game status updates:
  - `Next player: X`
  - `Next player: O`
  - `Winner: X` / `Winner: O`
  - `Tie`
- Winner detection for all directions (rows, columns, diagonals)
- Reset button to restart the game

---

## 🏗️ Project Structure

```

src/
├── components/
│ ├── Board.js # Game logic + layout
│ └── Square.js # Reusable square component
├── App.js # Main app container
├── App.css # Styling
└── index.js # React entry point

```

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/tejas2292/Tic-Tac-Toe-game-with-React.git
cd react-tic-tac-toe
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

Visit `http://localhost:3000` in your browser to start playing!

---

## 📋 How to Play

1. The game starts with the status: **Next player: X**
2. Click any square to make a move.
3. Players alternate turns (X → O → X).
4. The first to get 3 in a row (horizontally, vertically, or diagonally) wins.
5. If all squares are filled with no winner, the game ends in a **tie**.
6. Click the **Reset** button to start a new game.

---

## 🛠️ Tech Stack

- React (with hooks)
- HTML/CSS (custom styling)

---

## 🧪 Test Coverage (Basic)

✅ Status should be: `Next player: X` at game start  
✅ Status should alternate after each move  
✅ Game ends when a player wins or it's a tie  
✅ `.status` and `.square` class names for test selectors

---

## 🙌 Acknowledgements

Built as a learning project using React fundamentals and functional components. Inspired by classic Tic Tac Toe games from childhood 😊

---

## 👨‍💻 Author

**Tejas Patil**  
[Portfolio](https://tejaspatil.co.in) • [LinkedIn](https://www.linkedin.com/in/tejas2292/) • [GitHub](https://github.com/tejas2292)

---
