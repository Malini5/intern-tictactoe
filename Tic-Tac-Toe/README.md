Project Description
The Tic-Tac-Toe Game is a two-player web-based game built using HTML, CSS, and JavaScript. The game consists of a 3x3 grid where two players (X and O) take turns placing their marks. The game ends when one player gets three marks in a row, column, or diagonal, or when all cells are filled without a winner (tie). The project helps practice front-end web development skills by focusing on user interaction, game logic, and responsive design.

Features
User-Friendly Interface: A simple and easy-to-navigate 3x3 grid layout where two players can click to place their marks (X and O).
Real-Time Game Status: Displays the current player's turn and declares the winner or tie when the game ends.
Game Reset: A reset button allows players to start a new game.
Win and Tie Conditions: The game correctly identifies win conditions (three in a row, column, or diagonal) and ties when all cells are filled without a winner.
Responsive Design: The game works on both desktop and mobile devices with responsive CSS for various screen sizes.
Project Objectives
Interactive Gameplay: Players take turns by clicking on empty cells, alternating between X and O.
Game Logic in JavaScript: Implements logic to determine the winner or tie and update the game state after each move.
Responsive Layout: Ensures the game board adjusts to different screen sizes for mobile and desktop.
Error Prevention: Prevents further moves after the game has ended, ensuring that no additional moves are made once a player has won or the game ends in a tie.
File Structure

The project includes the following files:

index.html: Defines the structure of the Tic-Tac-Toe game board and the display area for the current game status.
style.css: Contains the styles for the game board, buttons, and responsive layout, ensuring the game looks visually appealing across devices.
script.js: Implements the game logic, including handling player moves, checking for wins or ties, and resetting the game.
How to Play
Start the Game: Open the game in a browser. A 3x3 grid will appear, and player X starts the game.
Player Turns: Players take turns clicking on an empty cell to place their mark (X or O).
Winning the Game: The first player to align three of their marks in a row, column, or diagonal wins the game.
Tie Game: If all cells are filled without a winner, the game ends in a tie.
New Game: Click the "Reset" button to start a new round.


HTML (index.html):
Defines the structure of the 3x3 grid, with each cell being clickable.
A display area shows the current player's turn and the result of the game.
CSS (style.css):
Provides styling for the grid, buttons, and layout.
Uses CSS media queries to make the game responsive for mobile devices.
JavaScript (script.js):
Handles the game logic for alternating player turns.
Checks for winning combinations (rows, columns, and diagonals).
Detects ties when all cells are filled.
Resets the game when the "Reset" button is clicked.
Example Game Flow
Initial Setup: Player X is prompted to make their move.
Player Move: Player X clicks on an empty cell to place their mark (X).
Turn Alternation: After Player X’s move, Player O is prompted to take their turn.
Winning Condition: If Player O gets three in a row, the game declares Player O as the winner.
Game Reset: The "Reset" button allows for a new round after the game ends.
Error Handling
Invalid Moves: If a player attempts to click on an already filled cell, the move is ignored.
Game Over: Once a winner is determined or a tie occurs, no further moves can be made until the game is reset.
Challenges and Future Enhancements
AI Player (Optional): Implement an AI player to allow a single-player mode.
Game History: Keep track of the number of games won by each player.
Difficulty Levels: Add different difficulty levels for the AI player (easy, medium, hard).
Technologies Used
HTML5: Structure of the game grid and UI elements.
CSS3: Styling for the grid layout, display area, and responsive design.
JavaScript (ES6): Game logic for player interaction, win detection, and game state management.
Responsive Design
The Tic-Tac-Toe game is built with responsive design principles in mind, ensuring that the game works well on devices with various screen sizes, including desktops, tablets, and smartphones.











