# tictactoe
Game
Scope of the game is to createa simple tic tac toe game with two players.

Board is the critical piece of this games.
    Players
    Game State
    Staus on the winner

    Track of the turns and providing feedback who's turn is it.

    Overall establishes the view of the board and setting the buttons and rows.

Square is Parent and child relationship and provides information around each button

    Filled, Tik, color scheme

Key on the winning buttons and all possbilities.

const win = [
//row
[0,1,2],
.
.
.
Etc

Future Improvements:

1. Once a row is made(Tic-Tac-Toe), feature will disable rest of the board.

Implementation:
Condition to disable the open buttons once a row is completed. validation on each step
Mount and unmount components will also play that role.

2. Once a row is made, feature will highlight the boxes and make it standout from rest of the board.
Implement: CSS className to highlight completed row. Conditional as well

function example() {
  return condition1 ? value1
    : condition2 ? value2
    : condition3 ? value3
    : value4;
}

3. If the turn is for X, it will not show O in the choice on the open blocks.
Condition to only show players option.

4.  Highlight the Winner.
Working with CSS to highlight the winner on the board.
Git: https://abdulali01.github.io/tictactoe/
Code Git: https://github.com/abdulali01/tictactoe


