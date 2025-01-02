# HyperCube1000

Prototype using three 2d canvases to navigte a cube. Requires a window width of 1240px to format propperly.

<img src="images/preview.png" alt="A screenshot of the game" width="600"></img>

# Instructions

Press c key to toggle controls. Press x key to toggle audio. Refresh the webpage to generate a new HyperCube1000.

The HyperCube is 10 x 10 x 10 cube viewed as Z, X & Y planes. It's navigated with AWSD keys for the Z plane, Arrow keys for the Y plane, and a combination of AWSD and Arrow Keys for the X plane. The mouse can also be used to jump directly to any location.

The cube is generated with a random number of "encounter" tiles labeled 1-9. When entering a tile the player automatically rolls a random number between 0-9. If the roll is equal or greater than the number displayed on the tile, the player doubles thier on-hand cash and the tile is removed. Otherwise, the player loses all but $1. Tiles are not removed on loss.

Other tiles: Bank or "b" tiles, which toggle moving money between the bank and the player's on-hand cash. Tiles marked "a" give a random amount of free cash (0-999,999). Tiles marked "c" will let the player keep half their on-hand cash on the next loss.

Choosing consecutive numbers (higher or lower) will raise the Combo Bonus up to the Max Combo. The combo is reset if the encounter is failed, but it is not interupted by visiting the bank or other bonus tiles.

# Play in browser

[Click Here](https://doomlazer.github.io/HyperCube1000)