# PACMAN
game built using javascript and HTML5 canvas

draw on the HTML5 canvas,  create the game loop,  load the game map using a tilemap, add click handlers to make the pacman move, create a simple algorithm to move each ghost at random, detect collisions between the pacman and ghosts, have pacman eat the food pellets, add a running score, reset the game when pacman collides with a ghost, and move onto the next level once pacman eats all the food pellets in the current stage. 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/178ee40b-d71c-451e-85c1-8e37e8419734" />

## Future Work:
You can design your own map by modifying the tileMap if you want. You can add power pellets to allow pacman to eat the ghosts. In addition, there is an opening on left and right, where if pacman goes through, it would appear on the other side of the map. Currently pacman just moves off screen out of the map so a fix would be needed to make pacman appear the other side. For more of a challenge, you can modify the ghosts movement to cover areas unreachable since the ghosts only change directions when they collide against a wall, and not when theres another path available to go through.
