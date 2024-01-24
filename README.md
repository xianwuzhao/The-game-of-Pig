# The-game-of-Pig
In this project, you will develop a simulator and strategy functionality for a pig game. You'll need to implement some higher-order functions, experiment with random number generators, and generate some ASCII art. 
The Game of Pig is a dice game with simple rules: two players compete to reach a total of 100 points. Each round, the player rolls the dice repeatedly until a 1 ("pig") is rolled, or the player holds and counts the total number of points rolled. The sum of the points rolled each round is called the total number of rounds. At any time during a player's turn, the player is faced with two decisions:
Throw - If the player throws:
1: The player scores 1 point and it is the opponent's turn.
Extras: Rolls will be added to the player's turn total before the turn continues.
Hold - A player turns their turn total into a score, which then becomes their opponent's turn.
In this project, you will create a variation of Pig that uses two different dice. Players roll a 6-sided die, unless the sum of both players' scores is a multiple of 7 (including 0), in which case they roll a 4-sided die. This score total does not include the round total.
