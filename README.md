
Loottables-for-Epoch-1.0.6.1 and Legacy-1.0.5.1
[for 1.0.6.1 see down below!!]

=============1.0.5.1===========================

Installation Steps:
Download the Archive: https://github.com/RHE24/Loottables-for-Epoch-1.0.6.1-Legacy-1.0.5.1/archive/master.zip

Extract the MegaLoot Ordner and copy it in your mission.pbo.

In your init.sqf: find DZE_MissionLootTable = false;
set it to true.

Like this:
DZE_MissionLootTable = true; //Custom Loot Tables

then go to your description.ext and paste this:

#include "MegaLoot\CfgBuildingLoot.hpp"

at the top of your description.ext

thats it, you are done
Now happy Looting

=============1.0.5.1===========================


=============1.0.6.1===========================

Installation Steps:
Download the Archive: https://github.com/RHE24/Loottables-for-Epoch-1.0.6.1-Legacy-1.0.5.1/archive/master.zip

Extract the dayz_code Ordner and copy it in your mission.pbo.

In your init.sqf: find DZE_MissionLootTable = false;
set it to true.

Like this:
DZE_MissionLootTable = true; //Custom Loot Tables

then go to your description.ext and paste this:

#include "dayz_code\Configs\CfgLoot\CfgLoot.hpp"

at the top of your description.ext

then find:  #include "\z\addons\dayz_code\Configs\CfgLoot\CfgLoot.hpp"   exclude or delete it

thats it, you are done
Now happy Looting

=============1.0.6.1===========================

our Post on Epoch Mod: https://epochmod.com/forum/topic/43914-mega-loot-tables-epoch-1061/

