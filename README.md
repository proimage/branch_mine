BRANCH MINE
===========

ComputerCraft Turtle program for creating branch mines. Variable main trunk size & length, branch spacing & length - all controlled via an interactive text menu.

Coded by Sandwich (@sandwich_hlp on Twitter; sandwichHLP on YouTube)

Some functions taken from the 'tunnel' program included with ComputerCraft / Feed The Beast.

Installation
------------
Open the ComputerCraft Zip archive in something like 7-Zip and place the "branch_mine" file (not folder!) in the /lua/rom/programs/turtle/ directory. This will make the program available to all your turtles in all your worlds.

Specific Installation Instructions for Feed The Beast:

1. Run the launcher.
2. Click the "Edit Mod Pack" button under the MODPACKS tab.
3. In the window that opens up, click the "Open Folder" button in the bottom-left.
4. In the Explorer window that loads up, find and open the ComputerCraft1.46.zip (or whichever version you're using), and follow the directions above (place the program in the Zip archive).

Usage
-----
Just run the "build_mine" program on a mining turtle (the one with a pickaxe). The main menu will appear - look through the options and get things to your liking - everything's fairly self-explanatory.

Fuel (coal) goes in slot 1, and cobblestone in slot 2. I recommend you fill the rest of the turtle's inventory with single "placeholders" (a block of ore, a diamond, a piece of redstone dust, etc) that you want the turtle to reserve space for, otherwise it'll fill up on cobblestone and discard all the valuables.

Make sure to run this program at the beginning of your Minecraft session so that it has time to complete. Exiting the Minecraft world will interrupt the program, and the turtle will not resume upon reload.

Changelog
---------
- 1.0 (2012-12-29):
	- Initial public release

Features
--------
- Interactive Text Menu for configuration of settings
- Configurable main trunk size (1x2, 3x3, 5x4)
- Configurable main trunk length
- Able to skip excavation of main trunk entirely and only dig side branches
- Configurable branch spacing (blocks between branches)
- Configurable branch length
- Able to connect branches at their ends

Wishlist
--------
Give me feedback on these - or code 'em in yourself! :)

- Automatic crafting & placing torches
- Keep track of progress and resume where left off if interrupted

Copyright
---------
Feel free to share and distribute the program freely. Don't charge money for it. If you enhance it with modifications, be a good community member and share your modifications equally freely (forking it on GitHub is ideal). Please leave the attribution in.