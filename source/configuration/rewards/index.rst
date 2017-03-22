=======
Rewards
=======

You can create rewards for each game, and when player win the game, all command go to be executed

How to add it
=============

For add rewards select a game, then go to the node (Configuration Section):

.. image:: https://proxy.spigotmc.org/fc93c04a1ca7b1cb6107ec9ab1ad3f9a493fb9aa?url=http%3A%2F%2Fimage.prntscr.com%2Fimage%2F57900485a6a24c138381f011c479e682.png

Then in the same space (Like "colors: " node) add "finalCommand: [COMMAND HERE]"
You can use {player} to replace it for the winner name and multiple commands separated with comma:

Example: ``say {player} wins, it's super cool,give {player} minecraft:diamond_block 1000``

With this you add all commands you wan't vanilla, from other plugins etc

.. note:: More info about vanilla commands: http://minecraft.gamepedia.com/Commands

