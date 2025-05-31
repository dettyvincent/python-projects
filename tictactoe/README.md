# Tic Tac Toe game.
In this project I am creating a Tic Tac Toe game using Python in Jupiter environment. Here are the requirements:
*	2 players should be able to play the game (both sitting at the same computer)
*	The board should be printed out every time a player makes a move
*	You should be able to accept input of the player position and then place a symbol on the board.

## Requirements:
Jupyter Notebook

## Step 1: 
Write a function that can print out a board. Set up your board as a list, where each index 1-9 corresponds with a number on a number pad, so you get a 3 by 3 board representation.
**display_board(board)**

## Step 2: 
Write a function that can take in a player input and assign their marker as 'X' or 'O'. Think about using while loops to continually ask until you get a correct answer.
**player_input()**

## Step 3: 
Write a function that takes in the board list object, a marker ('X' or 'O'), and a desired position (number 1-9) and assigns it to the board.
**place_marker(board, marker, position)**

## Step 4: 
Write a function that takes in a board and a mark (X or O) and then checks to see if that mark has won. 
**win_check(board, mark)**

## Step 5: 
Write a function that uses the random module to randomly decide which player goes first. You may want to lookup random.randint() Return a string of which player went first.
**choose_first()**

## Step 6: 
Write a function that returns a boolean indicating whether a space on the board is freely available.
**space_check(board, position)**

## Step 7: 
Write a function that checks if the board is full and returns a boolean value. True if full, False otherwise.
**full_board_check(board)**

## Step 8: 
Write a function that asks for a player's next position (as a number 1-9) and then uses the function from step 6 to check if it's a free position. If it is, then return the position for later use.
**player_choice(board)**

## Step 9: 
Write a function that asks the player if they want to play again and returns a boolean True if they do want to play again.
**replay()**

## Step 10: 
Use while loops and integrate all the functions to run the game.
