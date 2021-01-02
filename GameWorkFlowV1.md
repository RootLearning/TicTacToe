# Game WorkFlow
#### 1.   Display Choice.
#### 2.   Get player choice to start.
#### 3.   Print Board.
#### 4.   Get Input from the player.
#### 5.   Check Repetition from the player input.
#### 6.   Check winning state.
#### 7.   Game Continue or Quit choice.

   ###### 1. Display Choice.
  *   Display Choice the choice to player  **X** And **O** .
   ###### 2. Get player choice to start.
  *   In this case, I am going to Get choice from the player **X** or **O** . If the Player Choice is **X**, then the player goes first. 
  If the player choice is **O**, then AI goes first.
  * Because I set the condition default **X** Goes first always.

  ###### 3. Print Board.
  *  For printing the Board , I am using 1D array. 
```
   1D array = {1,2,3,4,5,6,7,8,9} 
```

 A |  B | C
---------|----------|---------
 1 | 2 | 3
 4 | 5 | 6
 7 | 8 | 9

 * We can also use 2D array . But i goes to 1D array.

 ###### 4. Get input from the Player.

 * Getting the input from the player to take which position.
 * the player selecting from the choice given in the table 1 to 9. 
 * If the player input =**5**.

  A |  B | C
---------|----------|---------
 1 | 2 | 3
 4 | **X** | 6
 7 | 8 | 9

 ###### 5. Check Repetition from the player Input.

 * Check the given input is repeat or not.
 * If the input is repeated, give the error message and again get the input.
 * if the given input is no repeated then goes to the next step.


 ###### 6. Check wininng state.

 * In this method, check the Boxes if the player is fill the positions in three in a row  horizontally, vertically, or diagonally. The player wins.
 * AI fils the position, AI wins.
 * If all positions are filled match is Draw.
 

 ###### 7. Game Continue or Quit choice. 
* If one round is finish I give a choice to the player.
* You want to continue press = 1.
* You want to quit press = 2.