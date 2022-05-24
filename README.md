# Dead Ops Arcade 2

For viewing and editing the source code on desktop, I highly recommend using Visual Studio Code with the CoD Syntax Highlighting extension.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Name: CoDScript
Id: atrX.vscode-codscript
Description: Syntax highlighting for Call of Duty scripts
Version: 1.1.3
Publisher: atrX
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=atrX.vscode-codscript
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


In order to start modifying and building the decompiled code here, first you must download the black ops 3 mod tools through the Steam store. Once you do so, open them and create a new mod titled the name of the repo ("doa2_reimagined" in this case). Then open your Git interface of choice (BASH, Github Desktop, etc.) and navigate to the mods directory in your Black Ops 3 installation. 

Once you are in the mods folder, first you need to delete the exisiting files within the "doa2_reimagined" folder you have created. Then run the command `git clone https://github.com/bczekalski/doa2_reimagined.git` at the same directory. If you've done it correctly all of the code should be downloaded and placed within the mod folder you created. You are now free to modify it and then build it with the mod tools.


Translations and important names of variables, functions, and assets in general can be found here.

Important Global Variables:

`level.doa.var_da96f13c - arena laps`
`level.doa.current_arena`
`level.doa.round_number`
`level.doa.arena_round_number`
`level.doa.var_b351e5fb - current enemy count`
`level.doa.rules.max_enemy_count`
`level.doa.rules.var_88c0b67b - rounds per arena (default 4)`
`level.doa.var_c061227e - anim playback speed (zombie speed cap)`
`level.doa.zombie_move_speed`


OBJECT.type numbers for various pick-ups:

`gems/money (or prizes / uber prizes).type - 1`

`max ammo.type - 2`

`sentry gun.type - 3`

`boots.type - 4`

`chicken.type - 5`

`electric balls.type - 6`

`barrels.type - 7`

`extra life.type - 8`

`heli.type - 9`

`boost.type - 10`

`monkey bomb.type - 11`

`nuke.type - 12`

`teddy bear.type - 13`

`clock.type - 14`

`DEBUG .type - 15`

`weapons.type - 16`

`umbrella.type - 17`

`rocket turret.type - 18`

`saw blade.type - 19`

`sprinkler.type - 20`

`magnet.type - 21`

`cerberus.type - 22`

`egg.type - 23`

`mech.type - 24`

`raps.type - 25`

`marwga heart.type - 26`

`fidolina egg (post boss fight).type - 27`

`vortex.type - 29`

`skeleton guardian.type - 30`

`robot guardian.type - 31`

`skull.type - 32`

`tank.type - 33`

`gloves.type - 34`

`first person.type- 35`

`golden egg.type - 36`

`coat of arms.type - 37`

`fido mech.type - 38`

Fates, and their corresponding values assigned to OBJECT.doa.fate:

`1 - Firepower`

`2 - Fortune`

`3 - Friendship`

`4 - Feet`

`10 - Fury`

`11 - Fortitude`

`12 - Favor`

`13 - Force`


Arena Names and their index in the arena sequence: 

`Island/Beach - "island" - 1`

`Docks - "dock" - 2`

`Farm/Cows - "farm" - 3`

`Circle/Dirt Nap/Cemetery  "graveyard" - 4`

`Temple/RoF Arena/Shadow Boogie - "temple" - 5`

`Coliseum/Square - "safehouse" - 6`

`Blood Lake/Blood Pool - "blood" - 7`

`Margwa - "cave" - 8`

`China - "vengeance" - 9`

`Donut/Hole - "sgen" - 10`

`Evac - "apartments" - 11`

`Combine/Bridge "sector" - 12`

`Metro - "metro" - 13`

`Snow/Dogs/Wolves - "clearing" - 14`

`Rooftops - "newworld" - 15`

`Jungle - "boss" - 16`








Tags: 

`//THIS LINE IS FOR CHANGING ARENA TO THE NEXT ONE IN THE ARRAY`

