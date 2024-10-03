# Tic-Tac-Toe Game

This project implements a simple command-line Tic-Tac-Toe game in Java. The game is played between a human user and the computer.

## Table of Contents

- [Features](#features)
- [How to Play](#how-to-play)
- [Game Flow](#game-flow)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Contributing](#contributing)
- [License](#license)

## Features

- A 3x3 grid for classic Tic-Tac-Toe.
- Human vs. Computer gameplay.
- Randomized computer moves.
- Winning combinations include rows, columns, and diagonals.
- Outputs the game result: Win, Lose, or Draw.

## How to Play

1. Run the game in a Java environment.
2. Enter a position from 1 to 9 to mark your move.
   - The positions correspond to the grid as follows:

     ```
     1 | 2 | 3
     ---------
     4 | 5 | 6
     ---------
     7 | 8 | 9
     ```

3. The computer randomly picks a position after your move.
4. Continue taking turns until one player wins or the board is full (resulting in a draw).

## Game Flow

- The human player plays with 'X'.
- The computer plays with 'O'.
- After every move, the game checks if either player has won or if it's a draw.

### Win Conditions

A player wins if they successfully mark three consecutive positions in any row, column, or diagonal.

- Rows: (1, 2, 3), (4, 5, 6), (7, 8, 9)
- Columns: (1, 4, 7), (2, 5, 8), (3, 6, 9)
- Diagonals: (1, 5, 9), (3, 5, 7)

### Result Messages
- **"Flawless Victory!"**: Human wins.
- **"Crushed!"**: Computer wins.
- **"A Perfect Balance!"**: It's a draw.

## Technologies Used

- **Java**: The core programming language used to develop this game.
- **Scanner**: Used for user input.
- **HashSet**: Tracks the positions taken by both the player and the computer.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Kalavathi18/tic-tac-toe-game.git
