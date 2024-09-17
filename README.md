# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using **HTML**, **CSS**, and **JavaScript**. The game features a 3×3 grid where players take turns placing “X” or “O” in the cells. The objective is to get three of the same marks in a row, column, or diagonal to win the game.

## Features
- **3×3 Tic-Tac-Toe Grid**: The board is composed of input fields arranged into a 3×3 layout, allowing players to interact by selecting cells to place their marks.
- **Turn-Based Gameplay**: Players alternate turns, with "X" going first. A flag is used to track and toggle the current player's turn.
- **Winning Logic**: The game checks for winning combinations after every move, highlighting the winning cells and displaying a message when a player wins.
- **Tie Game**: If all cells are filled without a winner, the game ends in a tie.
- **Reset Button**: Players can restart the game at any point using the reset button, which clears the board and allows for a new game.
- **Real-Time Feedback**: The interface updates dynamically to show the current player’s turn, disable played cells, and provide game status updates.

## How It Works
### HTML Structure
The board is represented by a series of input fields within a 3×3 grid, each acting as a clickable cell. A reset button is provided below the grid to restart the game.

### CSS Styling
The grid is styled to appear as a square, with additional styling for the header, instructions, and reset button. A hover effect and disabled state are applied to enhance user experience.

### JavaScript Logic
- **Player Moves**: Each cell is managed by a separate function (e.g., `myfunc_3`, `myfunc_4`, etc.), which handles updating the cell with either "X" or "O", depending on the current player's turn.
- **Turn Alternation**: A `flag` variable is used to toggle between Player X and Player O after each move.
- **Winning Logic**: The `myfunc()` function checks for any winning combinations (rows, columns, diagonals) after each move. If a player wins, the winning cells are highlighted, and a message is displayed.
- **Reset**: The `myfunc_2()` function resets the game by reloading the page and clearing the board for a new game.


## Future Enhancements
- Add support for tracking scores across multiple games.
- Implement AI for single-player mode.
