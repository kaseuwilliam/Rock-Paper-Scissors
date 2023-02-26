# Classes: Rock-Paper-Scissors Assignment

## Introduction

This week, you will implement the rock-paper-scissors game.

In this game, you and your opponent make a motion three times with your fists and show:

- a flat hand (paper)
- a fist (rock)
- two fingers (scissors)

Depending upon what is shown, the game is a tie (both show the same hand) or one person wins. Paper wraps up rock, so it wins. Scissors cut paper, so it wins. And rock break scissors, so it wins. 

In this computerized version of rock-paper-scissors, you need to create a program where a user plays against the computer. This game should run until a player wins 3 games. 

## Skills

This project will make use of the following skills or technologies:

- Variables
- Comparison Operators
- Functions
- Lists
- Loops
- Print Statements
- Classes
- Polymorphism and Inheritance

## Project Structure

You must create 5 files in this project: `actions.py`, `computer.py`, `human.py`, `player.py`, and `game.py`.

You must implement the basic game loop in the `game.py` file. The `actions.py` file is where you implement the rock-paper-scissors logic of the game. The `player.py` file is where you define a player's characteristics and actions and score. The `human.py` file inherits the `player.py` file and asks for input from a user through the console to determine an action to play. The `computer.py` file inherits the `player.py` file and chooses a random action to play. At the end of the game, you should print out the winner to the console. 

To run the game, run `python3 game.py` in the terminal.


## Project-Specific Acceptance Criteria

We want you to:

- [✅] implement the main loop of the game in the `game.py` file.
- [✅] create a Player class and within it, a `play method` that randomly picks which actions to play (i.e. rock, paper, scissor).
  - store this Player class within the `player.py` file. 
- [✅] create a Human and Computer class and have them inherit all attributes and methods from the Player class.
  - store the Human class within the `human.py` file. 
  - store the Computer class within the `computer.py` file. 
- [✅] use polymorphism to override the `play method` in the Human class that was inherited from the Player class.  
  - the play method should ask input from a user through the console to determine an action to play (i.e. rock, paper, scissor). 
  - the play method should have the appropriate error handling so that if a user inputs an invalid response, then the program doesn't crash. 
- [✅] the `computer.py` file should choose a random action to play (i.e. rock, paper, scissor).
- [✅] the `actions.py` file should implement the rock-paper-scissors logic of the game.
  -  Paper beats rock, rock beats scissor, and scissor beats paper.
- [✅] the game should run until a player wins 3 games.
- [✅] display the winner and loser at the end of the game. 


## Rubric

Functionality: 60%
- The program should adhere to the structure defined in the Project-Specific Acceptence Criteria above. 
- The program should be able to accept user input for their choice of rock, paper or scissors.
- The program should be able to generate a random choice for the computer.
- The program should be able to compare the user's choice and the computer's choice and determine the winner.
- The program should be able to keep track of the score.
- The program should be able to display the winner of each round and the final score.

User Interface: 25%
- The game should be played in the console. 
- The user interface should be clear and easy to understand.
- The user interface should prompt the user for their choice.
- The user interface should display the computer's choice and the winner of each round.

Code quality: 15%
- The code should be well-organized, easy to read and follow.
- The code should follow Python best practices.
- The code should be properly commented.
