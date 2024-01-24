# Functions and Components Need for TicTacToe

1) Make a board - generate_board()
    - generates and returns a 2D list
    - The outer list will contain three inner lists.
    - Each inner list will contain three " "

2 ) Display the current state of the board - display_board(board)
    - Parameter: board
    - Prints the board in a aesthetically appealing way. i.e. doesn't show list and quotes

3) Determine which player is "X" and "O"
    - Players will alternate turns.
    - Options on mechanism that alternates whose turn it is:

        a) Use a boolean variable, x_turn.

        b) Use a count variable that keeps track of the number of plays made. If the count variable is even, "X" plays otherwise the "O" plays.

4) Place player's mark on board - place_mark(board, player)
    - Parameters: board and player
    - Use input statements to get the row and column values where the player wants to place his/her mark
    - Check that the row and column values are eligible places. If the values are not eligible, then print an error message and prompt the player to guess again.
    - Place mark on board.

5) Check for winner.
    - Utilize the helper functions from the previous assignments.

6) GAME LOOP:

    - Use a while loop that will repeat as long as neither "X" nor "O" has won and the play count is less then nine.

    - Steps to be repeated:

        a) Display board

        b) Determine whose turn it is

        c) Place player's mark
        
        d) Check for a winner



