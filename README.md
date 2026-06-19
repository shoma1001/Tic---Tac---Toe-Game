# Tic Tac Toe Game

## Overview

This project is a simple implementation of the classic Tic Tac Toe game using Python. It is a two-player, console-based application where players take turns placing their marks (X and O) on a 3×3 grid. The game automatically checks for a winner or a draw after each move.

## Features

* Two-player gameplay (Player X and Player O)
* Turn-based system
* Interactive 3×3 board display
* Win detection for rows, columns, and diagonals
* Draw detection when the board is full
* Input validation to prevent invalid or occupied positions
* Simple and user-friendly console interface

## Technologies Used

* Python 3

## Project Structure

```text
tic-tac-toe/
│
├── game.py        # Main game file
└── README.md      # Project documentation
```

## How to Run

### Prerequisites

* Python 3 or higher installed on your system.

### Steps

1. Clone or download this repository.
2. Open a terminal or command prompt in the project directory.
3. Run the following command:

```bash
python game.py
```

## How to Play

The game is played on a 3×3 grid.

* Player X starts first.
* Players alternate turns and enter a number from 1 to 9 corresponding to a position on the board.

Board positions:

```text
1 | 2 | 3
--+---+--
4 | 5 | 6
--+---+--
7 | 8 | 9
```

## Winning Conditions

A player wins by placing three of their marks in:

* A horizontal row
* A vertical column
* A diagonal line

If all nine positions are filled and no player has won, the game ends in a draw.

## Example Gameplay

```text
 X | O | X
---+---+---
 O | X | O
---+---+---
 X |   |
```

Player X wins diagonally.

## Future Improvements

* Graphical User Interface (GUI) using Tkinter or Pygame
* Single-player mode with an AI opponent
* Score tracking system
* Restart and replay functionality
* Multiplayer mode

## Contribution

Contributions are welcome. If you would like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is open-source and available under the MIT License.

