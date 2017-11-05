# pigdice-game

#### PigDice Game, 5-11-2017

#### By Brenda Okumu

## Description

https://brendaokumu.github.io/pigdice-game/

pigdice-game is an application which enables two players to roll a dice and counts their rolls but the first to score a total of 100 or more points wins the game.

## Specifications

The first player to score 100 or more points after rolling the dice severally, wins the game:
    Example Input {No. of times dice rolled} : 20times
    Example Output : [3, 5, 2, 6, 4, 6, 6, 5, 4, 5, 6, 6, 6, 6, 6, 6, 6, 6, 6]
    Example Total Output : 100 

But with the following exceptions:
Each turn, a player repeatedly rolls a dice until either a 1 is rolled or the player decides to hold.

* If the player rolls a 1 they score 0 and it becomes the next player's turn
    Example Input {No. of times dice rolled} : 3times
    Example Output : [4, 2, 1]
    Example Total Output : 0
Next Player's Turn

* If the player rolls any other number, it is added to their total output and the player's turn continues
    Example Input {No. of times dice rolled} : 2times
    Example Output : [4, 2]
    Example Total Output : 6
Same Player Continues

* If a player chooses to hold, their total output is added to their score and it becomes the next player's turn
    Example Input {No. of times dice rolled} : 2times THEN hold
    Example Output : [4, 2]
    Example Total Output : 6
Next Player's Turn

Therefore the FIRST Player to score 100 or more points WINS

## Setup/Installation Requirements

To pull the application and perform changes, kindly perform...

* On GitHub, navigate to the main page of the repository.
* Under the repository name, click Clone or download.
* In the Clone with HTTPs section, click  to copy the clone URL for the repository.
* Open Terminal.
* Change the current working directory to the location where you want the cloned directory to be made.
* Type git clone, and then paste the URL you copied in Step 2.
* Press Enter. Your local clone will be created.

## Technologies Used

* Bootstrap
* JavaScript

## Support and contact details

Kindly contact Brenda on brenda.okumu2@gmail.com to make a contribution to the code.
