# CS 110
## Chapter 11 - Lab - Working with Pygame


### [Assignment Description](https://docs.google.com/document/d/1kFLQs7Lepb8hcYOrZq5scmRmdcNkIwWZ6Kb85_0bCVY/edit?usp=sharing)

***
Replace anything surrounded by the `< >` symbols._

## SUMMARY:
 The game provided contains a hero, enemy and controller class. Within the enemy class there is an init function and an update function. The init function creates the enemy sprite, assigns the image to it, and creates a rectangle object for it. The updste function updates the enemies to change both the x and y coordinates of its internal rectangle object by a random value: -1, 0, or 1. Within the hero class, there is an init function, move functions, and a fight function. The init function creates the hero sprite, assigns the image to it, and creates a rectangle object for it. The move functions define what happens when the player is prompted to move in each direction (as defined in the controller class with certain key presses). The fight function uses a random value to decide if the hero "wins" the fight and in turn returns true, otherwise false is returned. Each of these classes is called to within the controller class which contains an init fuction that sets up and defines the screen, a main loop that causes the game to run with a while loop while the game state is game and exits when the game state is game over. The game loop function defines what happens when keys are pressed and collisions occur between sprites. The game over loop defines the game over screen and exits the game when the hero is killed. Finally, the controller and the main loop are called to in the main file in order to allow the game to run.

#### Unique Feature
 I added a line to the game loop function in the controller class that causes the speed of the hero to increase everytime it kills an enemy.

## GRACE DAYS
Grace days used for this assignment: 1

Grace days remaining: 4/5

## KNOWN BUGS AND INCOMPLETE PARTS:
 None

## REFERENCES:
 None

## MISCELLANEOUS COMMENTS:
 None
