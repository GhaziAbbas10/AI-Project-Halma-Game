# Halma Game

This is a Python implementation of the classic **Halma** board game. It supports both two-player and player-versus-AI modes, with the AI using the Minimax algorithm for decision making.

## 🎯 Objective

Halma is a strategy board game where the goal is to move all your pieces from your corner to the opposite corner before your opponent does. Players can move pieces one step at a time or hop over other pieces for faster progress.

---

## 🗂️ Project Structure

```
HalmaGame-main/
├── main.py                     # Main script to start the game
├── Project Proposal.docx       # Project description and planning
├── __init__.py
├── halma/
│   ├── board.py                # Manages the game board and positions
│   ├── constants.py            # Defines game settings like colors and board size
│   ├── game.py                 # Main game loop and rules
│   ├── piece.py                # Handles individual piece behavior
│   └── __init__.py
└── minimax/
    ├── algorithm.py           # Minimax algorithm implementation for AI
    └── __init__.py
```

---

## 🧠 AI: Minimax Algorithm

The `minimax/algorithm.py` implements the Minimax algorithm with a limited depth search. The AI evaluates all possible moves and chooses the best one based on a scoring function. This ensures that the AI offers a competitive challenge to the human player.

---

## ▶️ How to Run the Game

### Prerequisites

- Python 3.7 or higher

### Steps

1. Download or clone this repository.
2. Open a terminal and navigate to the project folder.
3. Run the game using:

```bash
python main.py
```

> No external dependencies are required, so it should work on any Python installation out of the box.

---

## 🧱 Game Components

- **Board (`board.py`)**: Handles grid layout and position logic.
- **Piece (`piece.py`)**: Manages individual piece behavior and movement.
- **Game (`game.py`)**: Core gameplay loop, win checking, turn management.
- **Constants (`constants.py`)**: All tunable settings like board size, colors, player turn flags.
- **AI (`algorithm.py`)**: The Minimax decision-making logic.

---

## 📄 Project Proposal

The `Project Proposal.docx` document outlines the initial plan, objectives, and technical breakdown of the project.

---

## 🙌 Contributors

- This project was created as part of an academic or personal learning experience. If you'd like to contribute or improve it, feel free to fork and submit a pull request!

---

## 📌 License

This project is open-source and free to use for educational and non-commercial purposes.
