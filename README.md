# Tic Tac Toe Bot (3x3)

This is an intelligent Tic Tac Toe (3x3) bot built using the **Monte Carlo Tree Search (MCTS)** algorithm. It plays against a human interactively in the terminal, and learns optimal moves by simulating game outcomes from various states.

---

## Algorithm

- **Monte Carlo Tree Search (MCTS)** is used to simulate thousands of randomized games from the current state.
- The bot selects moves that maximize expected win probability using a balance of **exploration vs. exploitation** (UCB1).
- The game tree is built incrementally as the bot plays, making it adaptive.

---

## How to Run

```bash
python ttt.py
