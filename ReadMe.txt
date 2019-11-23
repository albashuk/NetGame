NetGame – it’s a game, where you play like a tank. The main target is to destroy the opponent in the middle of the field with many bullets that reflect from the walls and disappear only when hitting somebody.

There are two main objects: tanks and bullets. They have a very similar structure, but tanks are controlled by players and can’t move through the walls when bullets are flying the whole time and reflects from the walls. 

You can run a server and connect two players to the game. Every tick of time, the players send their information about pressed buttons to the server. The server makes all movements of all objects by action() and returns the current status by data() of all objects on the field to the players and they draw it on the field.

If you want to test the game in a single-player mode without server, you need to use the code in comments at the end of main().

Future improvements: add ways to use more types of bullets, add a possibility to change the map and increase the maximum size of players. 

MAIN FUNCTIONS:

check_two_rect() – check if two rectangles intersect each other;

check_walls() – check if an object intersects with walls;

action() - make all object actions, like movement or rotation, depended on its type, position, angle and which buttons on the keyboard are pressed;

data() - make a string of all important information about an object. 
