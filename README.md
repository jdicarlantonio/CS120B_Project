# CS/EE 120B Final Project -- Monster Hunter

## Tasks
There are four different tasks used in this project with their implementations defined in the header directory:

**PlayerMovement** (playerMovement.h)
	This task manages the control of the player’s movement. The player will either be ducking or stationary.

**PlayerShoot** and **UpdateShots** (playerShots.h)
	PlayerShoot manages the actual shooting of the player while UpdateShots will handle the logic of when a player actually hits a monster

**Game** (game.h)
	The game task handles the flow of the game. The player is either in the start menu, playing the game, or in the game over menu. This task oversees this logic.
