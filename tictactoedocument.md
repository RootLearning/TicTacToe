#  TIC-TAC-TOE GAME  
## OBJECTIVE  
The tic-tac-toe is to be the two-player, to get three in rows or columns or diagonals 3-by-3 squares. If a player is able to draw three X's or three O's in rows or columns or diagonals alternatively, then that player wins. If all squares are markers and neither player has made complete rows or columns or diagonals of Xs or Os alternatively, then the game is a draw.  
## RULES FOR TIC-TAC-TOE 

1.The game is played on 3 by 3 squares.   
2.the game is played two players alternatively at a time, Player 1->X and Player 2->O  
3.The  player X to get 3 of his/her marker in rows or columns or diagonals alternatively, then win player X.  
4.The  player O to get 3 of his/her marker in rows or columns or diagonals alternatively, then win player O.  
5. The players to get 3 of his/her marker in random rows or columns or diagonals alternatively, then draw.  
 6.When all 9 squares are marked alternatively, the game is over. 

 ## CONDITIONS FOR TIC-TAC-TOE   
* players are played the game alternatively.  
* player X place the value in one position,player O does not place the same position.  
* one player play one position at a time.   
* Toss to choose players first.

 ## METHODS FOR TIC-TAC-TOE  

* Structure for a tic-tac-toe game.  

 A |  B |  C
---------|----------|---------
 1| 2| 3
 4 | 5 | 6
 7 | 8 | 9  

* The following example game is won by the first player X   
### STEP-1  
* place the value in this squares player X  


ALL | THE | BEST
---------|----------|---------
 X | . | .
 . | . | .
 . | . | .


### STEP-2
  * place the value in this squares player O    

  ALL | THE | BEST
---------|----------|---------
 X | . | .
 . | . | .
 . | . | O


 ### STEP-3  
*  place the alternate value in this squares player X  

ALL | THE | BEST
---------|----------|---------
 X | . | X
 . | . | .
 . | . | O


  ### STEP-4
* place the alternate value in this squares player O  

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | . | .
 . | . | O
### STEP-5
*   place the alternate value in this squares-player X    

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | . | .
 X | . | O
### STEP-6  
* place the alternate value in this squares player O    

ALL | THE | BEST
---------|----------|---------
 X | O | X
 . | O | .
 X | . | O
### STEP-7  (FINALLY)
* place the alternate value in this squares player X  

ALL | THE | BEST
---------|----------|---------
 ~~X~~ | O | X
 ~~X~~ | O | .
 ~~X~~ | . | O

  :smile: player X Won The Match :smile:

  
 * Hence, tic-tac-toe is most often played by young children, who often have not yet discovered the optimal strategy.
* Because of the simplicity of tic-tac-toe, it is often used as a pedagogical tool for teaching the concepts of good sportsmanship and the branch of artificial intelligence that deals with the searching of game trees. It is straightforward to write a computer program to play tic-tac-toe perfectly or to enumerate the 765 essentially different positions (the state space complexity) or the 26,830 possible games up to rotations and reflections (the game tree complexity) on this space.   



## FUTURE UPDATES FOR TIC-TAC-TOE  

*  It can be generalized even further by playing on an arbitrary incidence structure, where rows are lines and cells are pointed. Tic-tac-toe is the game given by the incidence structure shown to the right, consisting of nine points, three horizontal lines, three vertical lines, and two diagonal lines, each line consisting of at least three points
## TRICKS FOR TIC-TAC-TOE  
* The first player contains 5 moves and the second players contain 4 moves for this game  
#### For example:  
1. First player contains winning possibility-60%  
2. Second player contains winning possibility-40%  
* The first player starts with the center position, the winning possibility is less in this game 
 * The first player starts with a corner position, the winning possibility is high  in this game
*  The first player starts with center position, the second player should  start with any corner position for the defense this game  
 * The first player starts with any corner position, the second player should start with a center position for the defense this game  
 * The first player starts with row(4 (or) 6) position, the second player should start with row(3(or)9(or)1(or)7) position for winning possibility in this game.
