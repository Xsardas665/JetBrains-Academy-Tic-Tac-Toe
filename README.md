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