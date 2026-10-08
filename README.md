# Tic-Tac-Toe

A command-line Tic-Tac-Toe game in Python. Play two players on the same keyboard, or against a computer that uses minimax.

## Requirements

- Python 3

## How to run

```bash
python Tictactoe.py
```

## Game modes

1. **Two players** — X and O take turns on the same computer.
2. **Vs computer** — you choose X (goes first) or O. The computer plays the other mark.

Squares are numbered **1–9**, left to right, top to bottom:

```
1 | 2 | 3
--+---+--
4 | 5 | 6
--+---+--
7 | 8 | 9
```

After each game you can play again or quit.

## Computer opponent

The computer uses **minimax** over the full game tree, so it always plays an optimal move (win if possible, otherwise draw).
