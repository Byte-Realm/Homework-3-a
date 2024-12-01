Chai Levy - 313589038
# Spaceship Game Additions

This is a revised version of the game we showed during class.
* In this version the map has boundaries on the top and bottom parts.
* The player can warp between the right side to the left side and vice versa.
* The player can perform a dodge essentially dodge the incoming enemies and destroy them.
## Changes code locations and usage
The code changes were all made in the InputMover script attached to the Player Spaceship.
* HorizontalWarp - This function is responsible for warping the player from the right to the left boundary and vice versa.
* VerticalBoundaryBlock - This function is responsible for blocking the player's movement on the y-axis (upper and lower boundary).
* PerformDodge - This function is responsible for making the player dodge to the direction the player is going (if no direction is given then the player will dodge to the right) and destroying enemy ships on it's way whilst also having invincibility frames.

## Player Keybinds
* Arrow Keys for movement
* Shift to dodge
* Spacebar to shoot

 
## Acknowledgements

Graphics:
* [Matt Whitehead](https://ccsearch.creativecommons.org/photos/7fd4a37b-8d1a-4d4c-80a2-4ca4a3839941)
* [Kenney's space kit](https://kenney.nl/assets/space-kit)
* [Ductman's 2D Animated Spacehips](https://assetstore.unity.com/packages/2d/characters/2d-animated-spaceships-96852)
* [Franc from the Noun Project](https://commons.wikimedia.org/w/index.php?curid=64661575)
* [Greek-arrow-animated.gif by Andrikkos is licensed under CC BY-SA 3.0](https://search.creativecommons.org/photos/2db102af-80d0-4ec8-9171-1ac77d2565ce)
