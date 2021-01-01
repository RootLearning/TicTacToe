# Game Flow

1. ### Display a welcome message

2. ### Random Player Selection

3. ### Select X or O marker

4. ### Print the board

5. ### Get Input from the user alternatively.

6. ### Fill the input in the board.

7. ### Check for reptition in the input.

8. ### Check whether the game can be continued or the game ends.

9. ### Display result.

### Display a welcome message:

Display a welcome message as given below:

**"Welcome to Tictactoe game! Let's play".**


### Random Player Selection:

Write a program to select the 1st player randomly.


### Select Marker:

In this method,the user allowed to select their marker.

Two choices(X or O) are given to the Randomly selected 1st player.

If the 1st player selected the X marker,then the O marker is automatically allocated to 2nd player
and vice versa.


### Print the board:

For printing the board, the Programmer can use a 1D or 2D array.

**1D array**

c1 |c2 | c3
------- | ------- | -------
0 | 1 | 2
3 | 4 | 5
6 | 7 | 8


**2D array**

~ | 0 | 1 |  2
--|---|---|---
0 | 0*0 | 0*1 | 0*2
1 | 1*0 | 1*1 | 1*2
2 | 2*0 | 2*1 | 2*2

**Why 1D array?**

* The winning state can be easily determined.

* Suitable for simple collections.

* Simple indexing.


**Why 2D array?**

* The 2D array is organized as matrices which can be represented as the collection of rows and columns.

* Ease of holding the bulk of data at once.


### Get input form the user alternatively:

Get the input from the selected 1st player.

**Possibilities for 1D array input** -It can be any integer value  between 0 to 8.

* **Possibilities for 2D array input** -Get both row value and  columm value as a input.(Example- Row-0,coloumn-2).
 
 * Set of possible input value: **Row and column**.

    (0,0) (0,1) (0,2)  
 (1,0) (1,1) (1,2)  
 (2,0) (2,1) (2,2)

 Display the possible input values while getting user input.


### Check for repeatation in input:

Check if the input given by the user already exists or not.

If not, then go to the next step.

If the input given is repeated, display an error message, and again get the input.


### Fill the Board:

Fill the board respective to the input given by the user.

Example:

**1D array**

column0 | column1 | column2
------- | ------- | -------
0 | 1 | 2
3 | 4 | 5
6 | 7 | 8

If the input value is **4**-1D

Fill the respective marker in 4th square.

column0 | column1 | column2
------- | ------- | -------
0 | 1 | 2
3 | X | 5
6 | 7 | 8

**2D ARRAY**

column0 | column1 | column2 | column3
------- | ------- | ------- | -------
 |  | 0 | 1|2
0 | 0*0 | 0*1 | 0*2
1 | 1*0 | 1*1 | 1*2
2 | 2*0 | 2*1 | 2*2

If the input value is **(1,0) -2D array**

column0 | column1 | column2 | column3
------- | ------- | ------- | -------
 |  | 0 | 1|2
0 | 0*0 | 0*1 | 0*2
1 | X | 1*1 | 1*2
2 | 2*0 | 2*1 | 2*2


### Check whether game can be continued or not:

Full state = Where all the squares in the boards are full.

If **Current state != Winning state** &&

 **Current state != Full state** && 
 
**Current state != Draw state**, the game can be **continued**.

Call print board method to show the current state, then continue to get input from second player(Get input alternatively) and the cycle goes on until the game ends.



If **Current state == Win state** ||

**Current state == Draw state**||

**Current state == Full state**,  the game **ends**.

Display the result.
 


 
### Display result:

Then display the result, which player wins, or display a draw message or full state message.





