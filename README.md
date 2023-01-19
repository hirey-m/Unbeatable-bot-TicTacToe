# TicTacToe_MiniMax

Welcome to the Tic-Tac-Toe game! This is a command-line based game where you can play against another human player, a computer, or even a "GeniusComputer" that employs the MiniMax algorithm and never loses. You can also pit two computer players against each other.

## How to Play
1. Clone the repository and navigate to the root directory of the game.
2. Run the game by executing the command python `main.py`
3. Select the type of players you want to play the game with by entering the corresponding number.
4. Players will be prompted to enter their moves by entering the row and column coordinates of the cell they want to play in.
5. The game will continue until a player wins or the game is a draw.

## Game Rules
1. The game is played on a 3x3 grid.
2. Players take turns placing their respective symbol ('X' or 'O') on the grid.
3. The player who succeeds in placing three of their symbols in a horizontal, vertical, or diagonal row wins the game.
4. If the grid is filled and no player has won, the game is a draw.

## GeniusComputer
The GeniusComputer uses the MiniMax algorithm to decide its next move. This algorithm evaluates all possible future game states and chooses the move that leads to the highest-scoring state for the computer. As a result, the GeniusComputer will either win or draw the game.

### Note
The game is developed and tested on python 3.8.2

Enjoy the game!
