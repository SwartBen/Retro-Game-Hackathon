
- RetroGameHackathon was an event run by the Developer Student Club of University of Adelaide.

- Participated in this event in November of 2020 as a first year (Advanced) Computer Science student with another group member. 

- Created a snake like game where the player had to avoid randomly spawning obstacles. 

- The game was created in c++, and used the library ncurses to output graphics to the console.

- The game won the award for creativity. 

Retro-Game-Hackathon
====================

# How to Play!

-Enter the Enter key and then '<' or '>' arrow key to start the game.

-When in the game use '<' or '>' to move the snake around.

-Enter the 'q' key to exit game whilst in play


# The rules

-Avoid the ever changing obstacles at all cost!

-Play at your own pace! The more frequent you press down the '<' or '>' key 
the faster your snake moves.

-To win the game reach a count of 250.

-If the player hits an obstance they lose and the game is over.

# How to install

1. Download the grid.cpp as well as the makefile

2. In the console type 'make grid' to compile the grid.cpp file

3. Type ./grid in the console

4. Have fun!

# Feature of the Game (Cannot be felt by the player, however, plays an important role)

-The surprising backend feature of the game is that it allows the user the benefit of doubt, that is, 
when obstacles change their locations after every 25 turns, they won't change near the vicinity of the 
player's location.

In general, if the obstacle spawns just two places beside you than you obviously cannot win the game.

Therefore, each time when it changes, the game makes sure that the player has the benefit of doubt

# Game Description

-The game is a twist of two very well known Retro games, Snake and Asteroid. The game takes 
the functionality of the snake from the game Snake and takes the functionality of randomly
 spawning Asteroids that need to be avoided from the game Asteroids.

-The player itself is a snake that can move up or down in a diagonal direction.

-The player must avoid five ever changing obstacles that spawn in random posistions.

-The snake rebounds when it hits the top or bottom boarder

-The five big obstacles change their locations randomly after every 25 turns

-To win the game you should avoid hitting the obstacles and survive for 250 turns

-If You Lose or You Won window is displayed, then you need to press the E key to get out of the game
