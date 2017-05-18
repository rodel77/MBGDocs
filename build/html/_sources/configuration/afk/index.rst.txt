=======
AFK
=======

MiniBoardGames has Anti-AFK system, with this system, players playing will not be kicked

Enable/Disable
==============

You can enable and disable this searching in config ``antiafk``

My Players Get Kicked By Flying
===============================

MBG Anti-AFK system use move event to prevent AFK kick, and some anticheats detect this move like ``Hacked``

If you dont need AFK system go to ``antiafk`` node in config and disable it but if you need it

You can modify the force of that movement searching in config ``afk``
Then you have ``x: 0.5``  ``y: 0`` ``z: 0.5`` values, change this depending of you AFK system and your AntiCheat, example if you afk system detect slow movement set it to ``0.05`` ``0`` ``0.05``