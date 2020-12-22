

# TicTacToe Game Specification

## About the Game:

Tic-Tac-Toe, it's a game of two players, who take turns marking spaces (**X or O**), it can be any symbols)in a 3*3 grid.

## Game Rules:

As we said, it's a two-player game, where one player takes one symbol(**X**) and the second player takes one symbol(**O**).

The first player to get 3 of her marks in a row (**up, down, across, diagonally**) is the winner.

When all 9 squares are full, the game is over or draw.

## Game design:

In our design, it's a game between a computer and a human.

We can design the grid in a 1D array or 2D array.


**GRID DESIGN**:

**1D ARRAY**
1 | 2 | 3
--|---|--
4 | 5 | 6
7 | 8 | 9

**2D ARRAY**
q
0 | 1 | 2 | 3
--|---|---|--
1 | 1*1 | 1*2 | 1*3
2 | 2*1 | 2*2 | 2*3
3 | 3*1 | 3*2 | 3*3



* First, write a program to select the random player who is going to get the chance to play first.

* Set a timer,for the player to think and decide a place.

* If the time exceeds,pass on to next player.

* Get the place as an input from the first player, where the player wants to fill the symbol.

* After the play, the second player gets the chance to fill the place, get the place as an input.

* Check the state for winning possibility.

* Again, get input from the first player, and second player and the cycle goes on.



* When all the places are filled and no one marks in a row, it's a **Draw**.

* If the player filled the row(winning state), then that player wins.

* Display the result.

### Winning state for X:
 
 X |  | |                
---|--|-
 |  | X
 |  | |X


- | - | X
--|---|--
- | X | -
X| - | -


- | - | X
--|---|--
- | - | X
- | - | X

- | - |- 
--|---|--
- | - | -
X | X | X

X | - | -
--|---|--
X | - | -
X | - | -

X | X | X
--|---|--
- | - | -
- | - | -

- | X | -
--|---|--
- | X | -
- | X | -





 




 
