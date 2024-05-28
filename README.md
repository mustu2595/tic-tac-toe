# tic-tac-toe
# Tic-Tac-Toe Game

This project is a classic two-player Tic-Tac-Toe game implemented using HTML, CSS, and JavaScript. The game allows two players to take turns marking cells in a 3x3 grid, with the objective of getting three of their marks in a row, column, or diagonal.

## Features

- **Two-player functionality:** Players take turns to mark 'X' or 'O' in the cells.
- **Win detection:** The game detects when a player has won by getting three marks in a row, column, or diagonal.
- **Draw detection:** The game detects when all cells are filled without a winner, resulting in a draw.
- **Responsive design:** The game is responsive and works well on both desktop and mobile devices.
- **Reset button:** Players can reset the game to start a new round.

## Getting Started

To get started with the Tic-Tac-Toe game, follow these steps:

1. **download the ZIP file:**
    download and extract the ZIP file.

Open index.html in your web browser:
You can open the index.html file directly in any modern web browser to start playing the game.
Project Structure
The project consists of the following files:

index.html - The HTML file containing the structure of the game.
style.css - The CSS file for styling the game.
script.js - The JavaScript file containing the game logic.
README.md - This README file.
Game Rules
The game board consists of a 3x3 grid.
Players take turns to click on empty cells to place their mark ('X' or 'O').
The first player to get three marks in a row (horizontally, vertically, or diagonally) wins the game.
If all cells are filled without a winner, the game ends in a draw.
Use the "Reset Game" button to start a new round.
Code Explanation
HTML (index.html)
The HTML file sets up the structure of the game, including the game board and display elements.

CSS (style.css)
The CSS file styles the game board, cells, and display elements to make the game visually appealing and responsive.

JavaScript (script.js)
The JavaScript file contains the logic for handling player turns, checking for win or draw conditions, and updating the game status.

Functions in script.js
handleCellPlayed(clickedCell, clickedCellIndex): Updates the game state and the UI when a cell is clicked.
handlePlayerChange(): Switches the current player.
handleResultValidation(): Checks if the game has been won or if it ended in a draw.
handleCellClick(clickedCellEvent): Handles the click event on a cell.
handleRestartGame(): Resets the game state and UI for a new round.
License
This project is open-source and available under the MIT License.


Enjoy playing the Tic-Tac-Toe game!
