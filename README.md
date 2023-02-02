## Tic Tac Toe Game
This is a simple Tic Tac Toe game written in Lua.

### Game Play 
The game is played on a 3x3 board where two players, represented by "X" and "O", take turns marking a square. The player who places three of their marks in a horizontal, vertical, or diagonal row wins the game.

### Board Representation
The board is represented by a 2-dimensional table called board. Each square on the board can contain either an "X", an "O", or a space " ".

### Functions
clear_board(): This function clears the board table by setting each square to " ".

display_board(): This function displays the current state of the board in the console.

board_full(): This function checks if all squares on the board are filled. If yes, the function returns true, otherwise it returns false.

check_winner(): This function checks all rows, columns, and diagonals of the board to see if there is a winner. If a player has placed three marks in a row, the function returns "X" or "O", depending on the winner. If there is no winner, the function returns nil.

### Game Loop
The game starts by calling clear_board() to clear the board. A game loop is then executed that alternates between players, prompting each player to enter the row and column where they would like to place their mark. The loop continues until a winner is found or the board is full.

### How to Run the Game
The game is written in Lua, so you'll need a Lua interpreter to run it. The code can be run from the command line by entering lua [filename].lua.
