

# TicTacToe Game Specification

## About the Game:

Tic-Tac-Toe, it's a game of two players, who take turns marking  (**X or O**) in the square,in a 3*3 grid.

## Game Rules:

 It's a two-player game ,if one player takes **X** Marker,then second player will take the **O** Marker and vice versa.

 Winning Condition-The first player to get 3 Markers in a row or column or diagonal is the winner.

When all square are filled without attaining the winnig condition, the game is draw.

## Game design:

 It's a game between a computer and a human.

 We can design the grid as a 1D array or 2D array.


**GRID DESIGN**:

**1D ARRAY**

c1 |c2 | c3
------- | ------- | -------
0 | 1 | 2
3 | 4 | 5
6 | 7 | 8


**2D ARRAY**

 - | 0 | 1 | 2
--|---|---|--
0 | 0*0 | 0*1 | 0*2
1 | 1*0 | 1*1 | 1*2
2 | 2*0| 2*1 | 2*2



* First, write a program to select a random player who is going to get the chance to play first.

* Get a value as an input from the first player, where the  player wants to fill the Marker.

* Fill a square respective to the given input value.

* **Possibilities for 1D array input** -It can be any integer values  between 1 to 6.

* **Possibilities for 2D array input** -Get both row value and  columm value as a input.(Example- Row-0,coloumn-2).
 
 * Set of possible input values: **Row and column**.

    (0,0) (0,1) (0,2)  
 (1,0) (1,1) (1,2)  
 (2,0) (2,1) (2,2)

 * After the first player filled a square, the second player gets the chance to fill a square.

 * Get the value as an input from the second player and then fill a square respective to the input value.

 * Check the state for winning possibility.

 * If the winning state is not attained, again get input from the first player and fill.

 * Get input from the second player and fill.

 * Check the state and the cycle goes on until the winning state or draw state.

 * When all the places are filled and no one attains the winning state, it's a **Draw**.

 * If a player reached the winning state, display the result which player wins!




### Winning state for X:
 
 X |  | |                
---|--|-
 |  | X
 |  | |X


~ | ~ | X
--|---|--
~ | X | ~
X| ~ | ~


 ~ | ~ | X
--|---|--
 ~ | ~ | X
 ~ | ~ | X

~ | ~ |~
--|---|--
~| ~ | ~
X | X | X

X | ~| ~
--|---|--
X | ~ | ~
X | ~ | ~

X | X | X
--|---|--
~ | ~ | ~
~ | ~ | ~

~ | X | ~
--|---|--
~ | X | ~
~ | X | ~

~ | ~| ~
--|---|--
X | X | X
~ | ~ | ~






 




 
