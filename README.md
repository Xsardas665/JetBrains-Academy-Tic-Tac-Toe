# Tic Tac Toe project from JetBrains Academy

### Description :
#### Stage 1/5:
Nowadays, this game is known all over the world. Each country may have its own version of the name, 
sometimes the rules are different, but the meaning of the game remains the same. Below are the main rules 
that may be familiar to you since childhood.
Tic-tac-toe is a game played by two players on a 3x3 field where the duel takes place. One of the players plays as 'X', 
and the other player is 'O'. 'X' plays first, then the 'O' side plays, and so on.
The first player that writes 3 'X's or 3 'O's in a straight line (including diagonals) wins.
#### Stage 2/5:
However, our game should show the field in an "intermediate" states too. Let's try to visualize different combinations 
that the user will determine from the input. It is also important to think about the interface and set boundaries for 
our field.
#### Stage 3/5:
It is time to learn to see the result (or the lack thereof) of the game. In this stage, you should analyze a Tic-Tac-Toe field.
Is it already clear who's the winner or is the game not over yet? Is it a draw or an impossible combination of moves? Let's find out!
Note that in this stage either 'X' or 'O' can start the game.

#### Stage 4/5:
In addition to analyzing the field, it is equally important to have the ability to select a cell for your move. Now you need to implement players' moves. Let's divide the field into cells.

Suppose the bottom left cell has the coordinates (1, 1) and the top right cell has the coordinates (3, 3) like in this table:

(1, 3) (2, 3) (3, 3)  
(1, 2) (2, 2) (3, 2)  
(1, 1) (2, 1) (3, 1)

The program should ask to enter the coordinates where a user wants to make a move.

Note that in this stage user places X, not O. Keep in mind that the first coordinate goes from left to right and the second coordinate goes from bottom to top. Also, note that coordinates start with 1 and can be 1, 2, or 3.

What if the user enters incorrect coordinates? The user could enter symbols instead of numbers or enter coordinates of the already occupied cells. You need to prevent all of that by checking the user input and catching possible exceptions.
#### Stage 5/5:
We are at the finish line! But playing alone is not so interesting, is it? Let's combine all our success from the past stages and get the Tic-Tac-Toe with the ability to play from the beginning (empty field) to the result (win or draw).

Now it is time to make a working game!

In the last stage, make it so you can play a full game with a friend. The first one of you moves as X, and then the other one moves as O.

### Objectives
#### Stage 1/5:
Your first task in this project is to print any state of the field in the console output. Do not forget to show the moves for both players.
#### Stage 2/5:
In this stage, you should write a program that:

- Reads 9 symbols from the input and writes an appropriate 3x3 field. 
  Elements of the field can contain only 'X', 'O' and '_' symbols.
- Sets the field to a specific format, i.e. the field should start and end with ---------, 
  all lines in between should start and end with '|' symbol and everything in 
  the middle should be separated with a single space.
  
#### Stage 3/5 :
In this stage your program should:

- Fill the field from the input and print it as in the previous stage.
- Find the state in which the game is at the moment and print it. Possible states:
  - "Game not finished" when no side has a three in a row but there are still empty cells;
  - "Draw" when no side has a three in a row and there are no empty cells left;
  - "X wins" when the field has three Xs in a row;
  - "O wins" when the field has three Os in a row;
  - "Impossible" when the field has three Xs in a row as well as three Os in a row. Or the field has a lot more Xs than Os or vice versa (if the difference is 2 or more, should be 1 or 0). For this stage, consider that the game can start both with X or O.

Also, you can use ' ' or '_' to print empty cells – it's up to you
#### Stage 4/5 :
The program should work in the following way:
- Get the 3x3 field from the input as in the previous stages.
- Output this 3x3 field with cells before the user's move.
- Then ask the user about his next move.
- Then the user should input 2 numbers that represent the coordinates of the cell which they want to mark X or O. (9 symbols representing the field would be on the first line and these 2 numbers would be on the second line of the user input)
- Analyze user input and show these messages in the following situations:
  - "This cell is occupied! Choose another one!" if the cell is not empty;
  - "You should enter numbers!" if the user enters other symbols instead of numbers;
  - "Coordinates should be from 1 to 3!" if the user goes beyond the field.
- Then output the table including the user's most recent move.
- The program should also check user input. If it's unsuitable, the program should ask them to enter their coordinates once again.

So, you need to output a field from the first line of the input and then ask the user to make their move. Keep asking until the user enters coordinates that represent an empty cell on the field and after that output the field with that move. You should output the field only 2 times, before and after a correct move.

Do not delete code that checks table state; it will be useful in the future.
#### Stage 5/5 :
In this stage, you should write a program that:

- Prints an empty field at the beginning of the game.
- Creates a game loop where the program asks the user to enter the cell coordinates, analyzes the move for correctness, and shows a field with the changes if everything is ok.
- Ends the game when someone wins or when there is a draw.
You need to output the final result after the end of the game.

Good luck gaming!