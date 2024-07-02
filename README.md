# Tic-Tac-Toe Game

This is a simple console-based Tic-Tac-Toe game implemented in C++. Two players can play against each other by taking turns to place their marks (X or O) on a 3x3 grid. The game checks for wins and draws and displays the game board after each move.

## Features

- 3x3 game board
- Two players (X and O)
- Display the current state of the board
- Prompt the current player to enter their move
- Update the game board with the player's move
- Check for win conditions
- Check for draw conditions
- Alternate turns between players
- Display the result of the game (win, draw, or ongoing)
- Option to play another game after the current game ends

## How to Play

1. Run the program.
2. The game will prompt the current player (X or O) to enter their move in the format: `row column`.
3. The game will update the board and check for a win or draw.
4. The game will alternate turns between the players.
5. When the game ends (win or draw), the result will be displayed.
6. The game will ask if the players want to play another game. Enter `y` to play again or `n` to exit.

## Code Explanation

- The `printBoard` function displays the current state of the board.
- The `checkWin` function checks if the current player has won.
- The `checkDraw` function checks if the game is a draw.
- The `playerMove` function prompts the current player to enter their move and updates the board.
- The `playGame` function runs a single game session.
- The `main` function runs the game and asks if the players want to play another game after each session.

