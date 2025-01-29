# Tic-Tac-Toe-Console-Game

Welcome to the **Tic-Tac-Toe Console Game**! This is a simple implementation of the classic Tic-Tac-Toe game, designed to be played in the console. It supports two players, `X` and `O`, who take turns to mark spaces on a 3x3 grid. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game. If all nine squares are filled without a winner, the game ends in a draw.

---

## Features

- **Two-Player Game**: Play against a friend on the same device.
- **Interactive Console Interface**: The game board is displayed in the console, and players input their moves using row and column numbers.
- **Win Detection**: The game automatically detects when a player wins or if the game ends in a draw.
- **Input Validation**: Ensures that players enter valid moves and prevents overwriting existing moves.

---

## How to Play

1. **Start the Game**: Run the program in your C++ environment.
2. **Enter Moves**: Players take turns entering their moves by specifying the row and column numbers (0-2) where they want to place their mark (`X` or `O`).
3. **Win or Draw**: The game ends when a player wins by getting three of their marks in a row or when the board is full (resulting in a draw).
4. **Play Again**: Restart the program to play another round.

---

## Code Overview

The game is implemented in C++ and consists of the following components:

- **`drawBoard` Function**: Displays the current state of the Tic-Tac-Toe board in the console.
- **`checkWin` Function**: Checks if the current player has won the game by examining rows, columns, and diagonals.
- **Game Loop**: Manages the turns of the players, validates input, and updates the board.
- **Win/Draw Logic**: Determines the outcome of the game and displays the result.

---

## How to Run the Code

1. **Prerequisites**: Ensure you have a C++ compiler installed (e.g., GCC, Clang, or MSVC).
2. **Compile the Code**:
   - Save the code in a file named `tic_tac_toe.cpp`.
   - Open a terminal or command prompt and navigate to the directory containing the file.
   - Compile the code using the following command:
     ```bash
     g++ tic_tac_toe.cpp -o tic_tac_toe
     ```
3. **Run the Executable**:
   - After compiling, run the game using:
     ```bash
     ./tic_tac_toe
     ```
   - Follow the on-screen instructions to play the game.

---


Enjoy playing the **Tic-Tac-Toe Console Game**! If you have any questions or feedback, please open an issue on GitHub.

Happy coding! 🎮
