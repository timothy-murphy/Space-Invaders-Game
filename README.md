# Space-Invaders-Game
This project is a Space Invaders Game, based off the classic arcade game. I created this game using the Module "Pygame", which is designed to help programmers create fully interactive games. 

The way Space Invaders works, is that the user controls a space ship that can shoot out lasers. The user then has to shoot down enemy space ships that try to make to the users "safe zone". If an enemy ship makes it too the safe zone, then the player loses a life. The user can move the space ship around by using the WASD keys and presses the space bar to shoot. 

The main method of the program is the main() method. This method essentially runs the game, with all the other methods being abstract methods. The main method essentially cycles through 60 times per second for 60 fps and checks if any of the following actions have occured: if the user moved the space ship, shot the laser, any colliions happened, which remove the enemy ships, it also counts the number of enemy ships per round, and then ends the game if the user runs out of lives, or ends the round and starts the next one, once all ships have been destroyed. 
