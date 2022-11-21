Fork of https://github.com/OctavoPE/GW2MysticForgeMacro  
I just changed it from 5 keys to 2 keys, as the Mystic Forge has an auto-refill option.

# Guild Wars 2: Mystic Forge Macro
An incredibly simple AutoHotKey script for use in Guild Wars 2 that saves the coordinates of your cursor 2 times (One for the "Refill" button, and one for the "Forge" button) and then automatically presses these 2 buttons in a loop.

## How to use it
The script needs to know the location of the 5 buttons it has to press. (The four materials, and the "Forge" button) 
All the user has to do is hover over the needed locations and press the associated buttons (these can be changed)
**The steps are as follows:**
1. **Ctrl + Q** - Saves the location of the refill button
2. **Ctrl + W** - Saves the location of the forge button
6. **Ctrl + K** - Runs the script, it will click on the 2 sets of coordinates with very miniscule breaks in between to account for lag, animations, etc. It will also wait a moment before restarting the loop to account for the forging animation.
7. **Ctrl + P** - Immediately quits the script, to reuse simply reopen the autohotkey script. (You will have to resave your coords every time you quit)

## Disclaimer
Guild Wars 2 Macro Policy:  
https://help.guildwars2.com/hc/en-us/articles/360013762153-Policy-Macros-and-Macro-Use  
This should fall under "You may create an auto-clicker that opens or consumes a stack of items." and be allowed, but then again, they only specifically state "auto-clicking that opens/consumes stacks of tiems" and NOT auto-refilling the forge, so use at your own risk and all that stuff.
