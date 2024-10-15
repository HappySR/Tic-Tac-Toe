# Tic-Tac-Toe Game with Tkinter
This Python application implements a classic Tic-Tac-Toe game with a user-friendly graphical user interface (GUI) built using the Tkinter library. Players take turns placing their symbols (X or O) on a 3x3 grid.

## Features:

* Clear and intuitive GUI with a grid layout
* Two players with alternating turns (X and O)
* Win detection for horizontal, vertical, and diagonal wins
* Draw detection when the grid is filled without a winner
* Highlighting winning squares
* Informative messages for wins, draws, and current player turn
  
## How to Play:

1. **Installation**: Ensure you have Python 3 installed on your system. Download it from https://www.python.org/ if needed.

2. **Running the Game**: Save the code as tic_tac_toe.py and run it from the command line:
```
python tic_tac_toe.py
```
Use code with caution.

3. **Gameplay**: Click on an empty square on the grid to place your mark. The game automatically detects wins and draws, and highlights winning squares for clarity. 

## Additional Notes:

The code is well-structured, commented, and adheres to Python best practices for readability and maintainability.

Consider extending the game further by adding features like a "New Game" button, difficulty levels, or AI opponents.

## Understanding the Code:

The code consists of several key functions:

* **check_winner()**: Analyzes all winning combinations to determine a winner or draw.

* **button_click(index)**: Handles button clicks, updates the board with the current player's mark, and checks for win/draw.

* **toggle_player()**: Switches the current player between X and O.

**Enjoy playing Tic-Tac-Toe!**
