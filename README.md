# Goose-on-the-Loose-
Hybrid board game with electrionic elements where players try to be the first one to catch the goose who ran away. The "Loose Goose" if you will. In this game, players take turns hitting buttons on the circuit playground to determain how far they can move while trying to catch up to the goose that moves in a random direction. 
The game takes place on a board with the playground essentially cating like a dice with a different number of sides depending on what the used is making. 
This game also includes various obsticals, traps, sound effects and lights to make the playing expericnce more intersting. 

Imputs and outputs:
Slide switch: changes between players turns by altering the function of the other buttons.
Left button: When the switch is left, it chooses the goose direction.. When it's right it controls the winner of the fight.
Right Button: When the switch is left, it generates the movement distance for the goose. When it's right it controls the direction.  
  (All 4 button options call on functions that play light patterns, and sounds.)
Serial Print: Prints rules, the story line, as well as uses random interger functions to generate the locations of obsticals and traps.


Upon start the game uses serial print to explain the following rules:

-Loose goose gets to spin each turn for a randomized dirrection");
-Animal patrol gets to spin once per turn in player defined dirrection");
-Bread trap skips one Loose Goose turn if crossed.");
-If an Animal Patrol player goes through an obstical they take twice as to move.");
-Anamial Patrol and Loose Goose fight if in adjacent tiles.");
-If Animal Patrol players lose fight, they miss 1 turn and return to start 
-First Animal Patrol player to win the fight wins the game"

It also tells a very breif storyline for the context of the situation.
