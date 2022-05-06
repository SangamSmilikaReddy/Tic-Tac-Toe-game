# Tic-Tac-Toe-game

I have created a tic tac toe game using python basic concepts like funtion definition,
if else eleif concept, while loop.

 Algorithm
-----------

1. Create a list with 9 elements filled with dashes and variable name is board.
2. Strat player is X
3. define play_name which displays 1st output of th board and strats the game if its ist turn,
   else checks if the game ended and there is a winner or not and prints the winner or tie.
4. Define display_board which displays current updated board list and a default board with position numbers
5. Define handle_turn with parameter player which ask the player to choose a positopn to place x or o
   check if the position entered with in the limits and also not already used using if else.
7. Define check_if_game_over to check if there is a winner or it is a tie by calling 2 funtions
8. Define check_for_winner check wether row or column or diagonal matches by calling 3 functions if yes
   then winner is available, else none.
9. Define check_rows, check_column, check_diagonal which check respectively and return the element present
   in that list index
10.Define check_for_tie if none of the elements is "-" and and game ended then return false.
11.Define flip_player to flip the player from x to and vice versa till game_still_going is true.
12.Call the function play_game to start the game.
