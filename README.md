# Scavengers Modification :axe:
The following is a modification of the Scavengers game done through the official Unity tutorial.

THe following modifications were made:

The files under `Assets/Resources` are each a text file that represent a day in the format dayX, where X is a number. Preferably continuous numbers–e.g., 1, 2, 3, 4...
The text file should use the following key to specify where game objects should reside in the 10 x 10 board:

X = wall
F = food
E = enemy
T = exit
Example:

```
xxxxxxxxxx
x  x     T
x     F  x 
x  F     x 
x        x
x     E  x
x        x 
x    F   x
x        x 
xxxxxxxxxx
```

The file above should render the exit in the top-right corner of the board with a single enemy and three food items.
