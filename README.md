# MegaLoot-Epoch-1.0.6.1-
Mega Loottables for Epoch 1.0.6.1+

===================================
Installation Steps:
Download the Archive: https://github.com/RHE24/MegaLoot-Epoch-1.0.6.1-/archive/master.zip

Extract and Paste it in your mission.pbo (any folder).

In your init.sqf: find DZE_MissionLootTable = false;
set it to true.

Like this:
DZE_MissionLootTable = true; //Custom Loot Tables

then go to you description.ext and paste this:

#include "MegaLoot\CfgBuildingLoot.hpp"

at the top of your description.ext

thats it you are done

Now happy Looting

