# roboOdd
Robot Odyssey clone for Minetest

## Goals

* A walk-in Robot. (Possibly build a schematic so we can make creative bots for those making a creative environment)
* A environment with various blocks/nodes which can provide various actions and feedback. (From the Environment Recognition node to the Computer Module all these provide physical actions and feedbacks)
* Make some kind of physical manual / guide. (Provide assistance where assistance is needed, in-game and out of game guides and manuals / wiki)

## Todo

* Use the concept of [area_containers](https://github.com/TurkeyMcMac/area_containers) to develop a "box" rather a space in which we can make a "Robot".
* Build the Environmental Recognition (A block which will emit on all sides the block or liquid (fake-liquid) to show environment/surroundings)
* Build the Manual Flight Controller (This will take player input and move the craft/robot, updating internal stuff like exit point that way)
* Build the Auto Flight Controller (This will allow code to control the current Robot)
* Build the Mine Displacer (This will allow a player to manually or via code break and collect blocks, which will be placed in a chest/chestlike node next to this block)
* Build the Communications System (This will allow setting up to 4 channels to send or recieve mode and allow code to send out only on sending channels)
* Build the Computer Module (Allows writing via dynamic programming, loading pre-build (Some basic programs: move around in a circle, mine the block underneath then move down till hitting a block that can't be broken in which returning to starting position, etc.) or pre-written (written some other time then saved), and saving current dynamic program for that player)

## Credits

* I'd like to thank jwmhjwmh for creating [area_containers](https://github.com/TurkeyMcMac/area_containers) the base for which the robot can be built on.
* I'd like to thank the [Minetest](https://github.com/minetest/minetest) community for creating the game and it's game engine.

