# Tic-Tac-Toe Game Documentation

## Overview
This Python program implements a simple two-player Tic-Tac-Toe game. Players take turns marking spaces on a 3x3 grid, with one player using "X" and the other using "O". The game ends when one player achieves three marks in a row (horizontally, vertically, or diagonally) or when the board is full, resulting in a tie.

---

## How to Play
1. **Starting the Game**: Run the script to start the game. The board will be displayed, and Player "X" will be prompted to make the first move.
2. **Making a Move**: On your turn, enter the row and column numbers (0, 1, or 2) where you want to place your mark ("X" or "O").
3. **Winning the Game**: The game checks for a winner after each move. If a player gets three of their marks in a row, column, or diagonal, they win, and the game ends.
4. **Tie Game**: If the board is full and no player has won, the game ends in a tie.

---

## Functions

### `print_board(board)`
- **Description**: Prints the current state of the Tic-Tac-Toe board.
- **Parameters**:
  - `board`: A 3x3 list representing the game board.
- **Output**: Displays the board in the console with rows and columns separated by lines.

### `check_winner(board, player)`
- **Description**: Checks if the specified player has won the game.
- **Parameters**:
  - `board`: A 3x3 list representing the game board.
  - `player`: A string ("X" or "O") representing the player to check.
- **Returns**: `True` if the player has won, otherwise `False`.

### `is_board_full(board)`
- **Description**: Checks if the board is full (i.e., no empty spaces left).
- **Parameters**:
  - `board`: A 3x3 list representing the game board.
- **Returns**: `True` if the board is full, otherwise `False`.

### `tic_tac_toe()`
- **Description**: The main function that runs the Tic-Tac-Toe game.
- **Steps**:
  1. Initializes an empty 3x3 board.
  2. Alternates turns between Player "X" and Player "O".
  3. Prompts the current player to enter their move.
  4. Validates the move and updates the board.
  5. Checks for a winner or a tie after each move.
  6. Ends the game and announces the result when a player wins or the board is full.

---
## Running the Game
1. Save the code to a file, e.g., `tic_tac_toe.py`.
2. Run the script using Python:
   ```bash
   python tic_tac_toe.py