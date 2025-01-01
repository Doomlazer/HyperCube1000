# HyperCube1000

Prototype game test 

# Play in browser

[Click Here](https://doomlazer.github.io/HyperCube1000)

# Instructions 

The HyperCube is 10 x 10 x 10 cube viewed as Z, X & Y planes. It's navigated with AWSD keys 
for the Z plane, Arrow keys for the Y plane, and a combination of AWSD and Arrow Keys for 
the X plane. The mouse can also be used to jump directly to the desired location.

The cube is generated with a random number of "encounters" labeled 1-9. When entering the
encounter the player automatically rolls a random number between 0-9. If the roll is equal
or greater than the number marked on the room the player doubles thier on-hand cash. Otherwise,
the player loses all but $1.

Besides the 1-9 encounters there are also "bank" tiles which toggle moving money between the
bank and the player's on-hand cash. Tiles marked "a" give a random amount of free cash (0-999,999).
Tiles marked "c" will let the player keep half their on-hand cash on the next loss.