# Snake-Ladder-Game
Created a GUI in JavaFX for the Snack & Ladder game where two players play the game.

## Design the game of Snake & Ladder
--------------------------------------------------------------------------------

- Create a Snake and Ladder application GUI in JavaFX library of java.
- The GUI has 10*10 size of gameboard . also having snake and ladder on the gamboard.
- Each snake will have its head at some number and its tail at a smaller number.
- Each ladder will have its start position at some number and end position at a larger number.
- There has two players in the game.

### Rules
- The board has numbers from 1 to 100.
- The players will make there move turn-by-turn.
- The game will have a six sided dice numbered from 1 to 6 and will always give a random number on rolling it.
- Each player has a piece which is initially kept outside the board (i.e., at position 0).
- Each player rolls the dice when their turn comes.
- Based on the dice value, the player moves their piece forward that number of cells. 
  Ex: If the dice value is 4 and the player is at position 7, the player will move to position 11 (7+4).
- A player wins if he reached the last cell (at 100 ) in the game board.
- Whenever a player ends up at a cell with the head of the snake, the player should go down to the cell that has the tail of that snake.
- Whenever a player ends up at a cell with the start of the ladder, the player should go up to the cell that has the end of that ladder.
- After the dice roll, if a piece is supposed to move outside position 100, it does not move.
- Snakes and Ladders do not create a cycle.

### Future Scope
- The game can be played by more than one dices. (i.e. if there are two dices then the numbers from 2 to 12 will be generated).
- On getting a 6, you get another turn and on getting 3 consecutive 6s, all the three of those get cancelled.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

# Class Diagram
![Snake and Ladder](https://user-images.githubusercontent.com/28945755/122057213-01c9e180-ce08-11eb-9a37-a3e711663623.png)
