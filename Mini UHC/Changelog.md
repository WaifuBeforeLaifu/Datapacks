# V2
- Reduced size of world border
- Slowed down the world border
- Reduced max range players can spawn from the center
- Added warnings every 5 minutes for the world border
- Players now can use the F3 menu again
- Anvils can instakill players if you get lucky enough to drop one right on someone
- Added healing effect so players can't be killed while in the hub


# V2.1
- Banned players from having eyes of ender
- Bans players from using totems of undying
- Players can heal slowly while in a bed. Hunger must be full
- Drop a campfire(item) on the ground to heal while near it. Hunger must be full
- Removed change to random tick speed to lessen the lag
- Added functionality for care packaged to be dropped at 45 minutes in. Not enabled as of right now
- Drop TNT(item) on the ground to turn it into unstable TNT

# V2.2
- Made some small optimizations to tick.mcfunction
- Iron and gold ore autosmelt when mined to speed up resource gathering
- Added "/trigger uhcinfo" for players to get a direct link to my github
- Updated the hub to tell players about /trigger
- Added an ingame message telling players how to use a campfire

# V2.3
- Campfires can now be placed like normal instead of dropped to give the healing effect
- Updated campfire message
- Made optimizations to the regen effect you get from beds

# V2.4
- Set gamerule reducedDebugInfo back to true
- Removed previous world border warnings
- Added a message that tells you your coordinates every 5 minutes, along with distance from the world border

# V2.5
- More optimizations to tick.mcfunction
- Fixed world border warnings not updating
- Sets time to morning when game starts
- Made optimizations to the world border warning
- Removed campfire info message
- Moved the setworldspawn command to gamesetup.mcfunction to avoid having players spawn in the air upon world creation

# V2.6
- Updated the Hub to look nicer
- Removed unused scoreboard objectives
- Added the option to set the max players per team. Set to 10 by default
- Major optimizations to tick.mcfunction

# V2.7
- Fixed world border messages. again

# V2.8
- Removed death messages that told you what team killed who
- Changed gold apples from starting kit into campfires
- Added the other stone tools to the starting kit
- Made villages a bit more hostile
- Diamonds can be crafted with 4 emeralds
- Fixed issue where players wouldn't be in adventure mode in the hub

# V2.8.1
- Lessened the lag created by tick.mcfunction by making a lot of commands run less often
- Fixed the issue where replacing villagers would spawn 2 zombies

# V2.9
- Hard coded a rule to make it so players can hold a max of 8 regular golden apples
