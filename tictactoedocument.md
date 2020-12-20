#  TIC-TAC-TOE-GAME  
## OBJECTIVE  
The tic-tac-toe is to be the two player, to get three in a row any one of the player on a 3-by-3 squares.If a players is able to draw three X's or three O's in a row alternatively,then that players wins.If all squares are filled and neither player has made a complete row of Xs or Os alternatively,then the game is a draw.  
## RULES FOR TIC-TAC-TOE 

1.The game is played on a 3 by 3 squares.   
2.the game is played two players alternatively at a time,Player 1:X and Player 2:O  
3.The  player 1 to get 3 of her marks in a row (up, down, across, or diagonally)alternatively,then win player 1.  
4.The  player 2 to get 3 of her marks in a row (up, down, across, or diagonally)alternatively,then win player 2.  
5. The  players to get 3 of her marks in a random row (up, down, across, or diagonally)alternatively,then draw.  
 6.When all 9 squares are full alternatively, the game is over.   

 ## CONDITIONS FOR TIC-TAC-TOE   
* players are played the game alternatively.  
* player-X place the value one position,player-O does not place the same position.  
* one player play one position at a time.  
* The players are playing time within 30 seconds in one round then changed atomatically  
* Toss to choose players first.

 ## METHODS FOR TIC-TAC-TOE  
*  Order to win the game, a players must place three of their marks in a horizontal, vertical, or diagonal row.  

* Structure for tic-tac-toe game.  

 A |  B |  C
---------|----------|---------
 1| 2| 3
 4 | 5 | 6
 7 | 8 | 9  

* The following example game is won by the first player:X   
### STEP-1  
* place the value from this squares-player:X  
  
 
ALL | THE | BEST
---------|----------|---------
 X | . | .
 . | . | .
 . | . | .


### STEP-2
  * place the value from this squares-player:O    

  ALL | THE | BEST
---------|----------|---------
 X | . | .
 . | . | .
 . | . | O
  
  
 ### STEP-3  
*  place the alternate value form this squares-player:X  

ALL | THE | BEST
---------|----------|---------
 X | . | X
 . | . | .
 . | . | O

  
  ### STEP-4
* place the alternate value form this squares-player:O  

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | . | .
 . | . | O
### STEP-5
*   place the alternate value form this squares-player:X    

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | . | .
 X | . | O
### STEP-6  
* place the alternate value form this squares-player:O    

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | O | .
 X | . | O
### STEP-7  (FINALLY)
* place the alternate value form this squares-player:X  

ALL | THE | BEST
---------|----------|---------
 ~~X~~ | O | X
 ~~X~~ | O | .
 ~~X~~ | . | O
  
  :smile: player-X Won The Match :smile:

* Players soon discover that the best play from both parties leads to a draw.  
 * Hence, tic-tac-toe is most often played by young children, who often have not yet discovered the optimal strategy.
* Because of the simplicity of tic-tac-toe, it is often used as a pedagogical tool for teaching the concepts of good sportsmanship and the branch of artificial intelligence that deals with the searching of game trees. It is straightforward to write a computer program to play tic-tac-toe perfectly or to enumerate the 765 essentially different positions (the state space complexity) or the 26,830 possible games up to rotations and reflections (the game tree complexity) on this space.   

 

## FUTURE UPDATES FOR TIC-TAC-TOE  
 
* It can be generalised even further by playing on an arbitrary incidence structure, where rows are lines and cells are points. Tic-tac-toe is the game given by the incidence structure shown to the right, consisting of nine points, three horizontal lines, three vertical lines, and two diagonal lines, each line consisting of at least three points  
## TRICKS FOR TIC-TAC TOE  
* The first player contains an 5 moves and second players contains an 4 moves for this game  
#### For example:  
1. First player contains winning possibility-60%  
2. Second player contains winning possibility-40%  
* The first player start with center, the winning possibility is less for this game 
 * The first player start with corner,the winning possibility is high  for this game
*  The first player start with center position,the second player should  start with any corner position for defense this game  
 * The first player start with any corner position,the second player should start with center position for defense this game  
 * The first player start with row(4 (or) 6) position,the second player should start with row(3(or)9(or)1(or)7) position for winning possibility for this game.

 