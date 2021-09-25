# Minecraft: Speedrun Guide - Any%, RSG, 1.16.1
[Discord](https://discord.com/invite/jmdFn3C) | [Minecraft Speedrunning Website](https://www.minecraftspeedrunning.com/) | [Minecraft Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki) | [Speedrun.com](https://www.speedrun.com/mc#Any_Glitchless)

## Table of Contents
* [Setup](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#setup)
	* [Mods](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#mods)
	* [Practice Maps](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#practice-maps)
* [Bastions](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#bastions)
* [Speedrun Guide](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#speedrun-guide)
	* [The Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#beginner--structureless-overworld)
		* [Structureless](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#beginner--structureless-overworld)
		* [Village](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#standard--village-overworld)
		* [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate-overworld)
			* [Pirate → Ocean Monument](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate--ocean-monument)
		* [Hypermodern](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#expert--hypermodern)
	* [The Nether](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-nether)
	* [The Overworld, Part 2](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-overworld-part-2)
	* [The End](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-end)
* [Keybinds & Shortcuts](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#keybinds--shortcuts)
	* [F3](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#f3-keybinds)
	* [Inventory Management](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#inventory-management)
* [Tips & Tricks](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#tips--tricks)
	* [The Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-overworld)
	* [The Nether](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-nether-1)
	* [The Overworld, Part 2](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-overworld-part-2-1)
	* [The End](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-end-1)
* [Practice](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#practice)
	* [Crafting](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#crafting)
	* [Tasks](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#tasks)
* [Speedrun Cheatsheet](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#speedrun-cheatsheet)

## Setup 
**Video Guides:** [k4yfour](https://youtu.be/4cTbSyvWNgI) | [DashPum4](https://youtu.be/km0sXurMj5s)
* Win + r → %appdata% → .minecraft → options.txt (gamma:5.0, syncChunkWrites:false)  
* Options → Music & Sounds → Show Subtitles: ON  
* Options → Video Settings → Quality → Entity Distance (500)  
* with Sodium Mod: (Disabling Entity Culling isn't required for Sodium v0.2.0+)
	* Options → Video Settings → Advanced → Disable Entity Culling   
	* Options → Video Settings → Unofficial → Enable Planar Fog  

## Mods
[Website](https://www.minecraftspeedrunning.com/public-resources/mods ) | [Explainations](https://youtu.be/km0sXurMj5s?t=126)  
### Fabric Loader (DON'T USE FABRIC API): [Website](https://fabricmc.net/use/) | [Download](https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.7.4/fabric-installer-0.7.4.jar)  
* Auto Reset Mod: [Website](https://github.com/DuncanRuns/AutoResetMod) | [Download](https://github.com/DuncanRuns/AutoResetMod/releases/download/v1.2.0/autoreset-1.2.0+MC1.16.1.jar)
	* When Active, on pressing Quit: Quits → Creates a New World, with correct Settings → Loads the World
	* **Optional**: AHK Keybind Reset + Saved Worlds Culling [Video](https://youtu.be/km0sXurMj5s?t=187)
* Fast Reset: [Website](https://github.com/jan-leila/FastReset) | [Download](https://github.com/jan-leila/FastReset/releases/download/1.15.2-1.0.0/fast_reset-1.15.2-1.0.0.jar)
	* Disables the forced Auto Save when Exiting a World, saving time between Resets  
* LazyDFU: [Website](https://modrinth.com/mod/lazydfu) | [Download](https://cdn.modrinth.com/data/hvFnDODi/versions/0.1.2/lazydfu-0.1.2.jar)
	* Lowers the time it takes to initially open the game
* Sodium: [Website](https://github.com/mrmangohands/sodium-fabric) | [Download](https://github.com/mrmangohands/sodium-fabric/releases/download/mc1.16.1-0.2.0%2Bbuild.17/sodium-1.16.1-backport-fabric-0.2.0+build.17.jar)
	* Greatly increases General Performance, Reduces Micro-Stutters, and Fixes Graphical Issues
* Lithium: [Website](https://github.com/mrmangohands/lithium-fabric) | [Download](https://github.com/mrmangohands/lithium-fabric/releases/download/mc1.16.1-0.6.6/lithium-1.16.1-backport-fabric-0.6.6.jar)
	* Optimizes Game Areas  


**Starlight is incompatible with Phosphor, only use Phosphor if Starlight doesn't work for you**
* Starlight: [Website](https://github.com/PaperMC/Starlight) | [Download](https://github.com/PaperMC/Starlight/releases/download/1.0.0-RC2/starlight-fabric-1.0.0-RC2-1.16.x.jar)
	* Completely rewrites the Lighting Engine, greatly reducing World Creation times
* Phosphor: [Website](https://github.com/mrmangohands/phosphor-fabric) | [Download](https://github.com/mrmangohands/phosphor-fabric/releases/download/mc1.16.1-0.7.2/phosphor-1.16.1-backport-fabric-0.7.2.jar)
	* Optimizes the Lighting Engine, causing general improvements and faster World Generation  


## Practice Maps
[Website](https://www.minecraftspeedrunning.com/public-resources/maps)  
* Sethbling's Speedrun: [Video](https://youtu.be/UihtGJhK_-w) | [Download](https://sethbling.s3-us-west-2.amazonaws.com/Downloads/DataPacks/speedrun_practice.zip)
* Semper's Nether Portal: [Video](https://youtu.be/K233ih6nSCU) | [Download](https://www.mediafire.com/file/1oanxrh14db4u7g/Portal_Practice.zip/file)
* Llama's Bastion: [Video](https://youtu.be/jlA-jW7VGqw) | [Download](https://www.dropbox.com/s/9e103bjzroi85aa/Llama%27s%20Bastion%20Practice%20v2.6.1.zip?dl=0) | [Loadout Guide](https://youtu.be/uTn9LwB5WAE)
* Semper's Blaze: [Video](https://youtu.be/CNqrnlgCRXk) | [Download](https://www.mediafire.com/file/2c6vo3qt9hv3qp5/Blaze_Practice.zip/file)
* Emma's End: [Video](https://youtu.be/fV5B7xJmiZU) | [Download](https://sites.google.com/view/emma-practice-map/home)


## Bastions
[Routing Spreadsheet](https://bit.ly/3kv8NL1)
* **Bastion Type:** Identification, **Videos** *by T_Wagz* | **Screenshots** *by ElaMeTrataDiferente*
	* Recommend Routes

<br/>

* Bridge: [Video](https://youtu.be/2pzMpX1RJGI?t=128) | [Screenshots](https://imgur.com/a/OHwW0tb)
	* if Triple, (right side): [Dowsky]()
	* if Single, (right side): [Dip by EleventyBillion]()
* Treasure: [Video](https://youtu.be/A9GGUWwNcrY?t=132) | [Screenshots](https://imgur.com/gallery/U4FnQC5)
	* [Ninjabrain]()
* Housing: [Video](https://youtu.be/BoNr-pbEITM?t=132) | [Screenshots](https://imgur.com/gallery/wyjWcli)
	* if Top: [Top Down Manhunt]()
	* if Bot: [Manhunt]()
* Stables: [Video](https://youtu.be/TioQsF5ygOg?t=149) | [Screenshots](https://imgur.com/gallery/u91rHC4)

	* if Triple: [Triple Chest Stables]()
	* if no Triple, w/ Good Gap: [Good Gap Stables]()
	* if no Triple, w/ Double Bad Gap: [Better Lucky Next Time](https://i.imgur.com/YxRxdhI.png)


<br/>

# Speedrun Guide
**Video Guides:** [Haroon Shah, Jun 2021](https://youtu.be/iaUF0oaegns) | [Couriway, Dec 2020](https://youtu.be/REas9cmjlic) | [LiquidCandy, Dec 2020](https://youtu.be/14XeowuYgV0) | [Cuffep, Oct 2020](https://youtu.be/GQodZBfdL3g)

## **Beginner** | [Structureless Overworld](https://youtu.be/7dOca1LHefk)
*Lower speed potential, but more consistent, resulting in far fewer resets - great for new runners*
* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.png)
* Find a nearby Cave → Decend into the Cave until you find Iron Ore
* Place the Crafting Table → Craft a Wooden Pickaxe → Mine 3 Cobblestone → Craft a Stone Pickaxe → 
	* Mine 7 Iron (8 - if you want a Shield), 12 Cobblestone, and 1-2 Coal
* Craft [a Furnace, a Stone Axe, and a Stone Shovel](https://i.imgur.com/4kdtS6b.png) → Pickup the Crafting Table
* Resurface → Place the Furnace near a Tree → Smelt the Iron Ore → Chop 8+ Logs
	* Collect the first Iron Ingot → Search for Gravel → Dig for Flint → Craft a Flint and Steel
	* Kill Burning Animals to get Pre-Cooked Meat
		* While Searching for Gravel / Animals: Collect [Dandelions or Blue Orchids](https://i.imgur.com/iMwY9Wo.png) (for Suspicious Stews)
* Collect the Iron once it's done → Place the Crafting Table → Craft an Iron Pickaxe, a Bucket, [a Boat, and Bowls](https://i.imgur.com/ROB8bsI.png)
* Find a nearby Lava Lake, or Dig deeper in the Cave to find Lava → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* While in the Nether, Collect Mushrooms in order to Craft [Suspicious Stews](https://i.imgur.com/9ckpeB6.png)

## **Standard** | Village Overworld 
*Spawn with a nearby Village - Ideally a Plains, Desert, or Savanna Village (for the guaranteed Hay Bales)*  
*if the Village is in a Desert, Gather Wood and Stone before entering - Trees don't spawn, and buildings are Sand*  

* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.png)
* Place the Crafting Table near your Mining Destination → Craft a Wooden Pickaxe → Mine 6 Stone → 
	* Craft [a Stone Shovel, a Stone Axe, and a Stone Hoe](https://i.imgur.com/TCqDxat.png) → Pickup the Crafting Table → Chop 8+ Logs  
### Village Tasks:
* Loot Blacksmiths, if available:
	* if 10+ Obsidian: Skip Bucket → Mine 4 Stone, instead of 6 → Skip Hoe (slightly slower, but doesn't require a second Stick Craft)
	* if 3+ Iron Ingots: Gather 2 Logs, instead of 3 → Skip Wooden Pickaxe
	* if 7+ Total Iron Ingots (Blacksmith + Golem): Skip the Bucket of Cod Trade (can skip with 6, but requires [Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=9))
* Collect Beds from the Village Houses, (and Carpets, if you plan on doing the [Carpet Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=38))
* Kill the Golem: Drops 3-5 Iron Ingots
	* Hit the Golem from max distance, from behind if possible → Run a few Blocks away → Build up 3 Blocks
	* Crit the Golem 8-9 times to Kill it: Jump → Fall → Attack, while Falling (with Stone Hatchet)
* Place the Crafting Table → Craft an Iron Pickaxe and a Boat
	* if you're doing the Bucket of Cod Trade, place this Crafting Table near Villagers, and addtionally Craft a [Composter](https://i.imgur.com/qK3yzOP.png) and a [Barrel](https://i.imgur.com/arI5xh9.png)
	* if 4 Iron Ingots: Craft a Flint and Steel, (after getting Flint from Digging up Gravel)
		* if you only get 3 Iron Ingots: [Flintless Portal](https://youtu.be/axHdNQtPOf8?t=66), or Search for a Shipwreck/Ruined Portal
	* if 5 Iron Ingots: Save for a Shield, in case you get a Fortress before a Bastion in the Nether
* Hoe 7 Hay Bales → Craft Wheat (7:63) → Hoe 5-10 additional Hay Bales → Complete the Bucket of Cod Trade
	* Find or Craft a [Composter](https://i.imgur.com/qK3yzOP.png) → Turn a Villager into a Farmer → Trade Wheat 60:3 Emeralds
	* Find or Craft a [Barrel](https://i.imgur.com/arI5xh9.png) → Turn a Villager into a Fisherman → Trade Emeralds 3:1 Bucket of Cod
* Craft Hay Bales → Wheat → Bread → Pickup the Crafting Table
* Leave the Village → Search for a Lava Lake or Ruined Portal → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* [Minimum Blocks Required](https://i.imgur.com/jSspUON.png) | [Minimum Space Required](https://i.imgur.com/GKtJlok.png)

## **Advanced** | Pirate Overworld
*Spawn near an Ocean, with a Shipwreck nearby - with 7+ Iron inside (ideally 11+)*
* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.png)
* Place the Crafting Table near a Tree → Craft a Wooden Axe → Chop 8+ Wood →
	* Craft Doors, and a Boat → Pickup the Crafting Table
* Place the Boat in the Ocean → Search for a Shipwreck → Collect the Boat and Dive towards the Shipwreck
* Once you find a Shipwreck → Enter the Top Side at the Back of the Boat → Loot the Chest (Iron / Gold) →
	* if < 7 Iron: Loot the Bottom Side Chest at the Back of the Boat → Collect the Buried Treasure Map
		* You can use the opened Door in the Bottom Cabin to refresh your Breath Meter 
		* Locate the Buried Treasure, if the Loot is bad → Reset
* Swim to the nearest Gravel → Place the Crafting Table, on the Ocean Floor → Place a Door on top of the Table →
	* Craft an Iron Pickaxe, a Bucket, a Shovel 
		* if 8+ Iron: Iron Shovel, otherwise Wood/Stone Shovel
		* if 11+ iron: Craft an Iron Axe
		* if any remaining Iron Ingots, Craft Iron Armor (can also save 1 for a Shield, if Fortress before Bastion)
	* Dig up Gravel until you find some Flint → Craft a Flint and Steel → Pickup the Crafting Table (and Door)
* Resurface → Place the Boat → Search for an Ocean Ravine
	* When Searching for an Ocean Ravine, turn on Entity Hitboxes (F3 + B), and look out for Floating Kelp
		* Kelp Tends to spawn above Ravines, and if the Ravine has Gravel/Sand in it, [the Kelp will Break](https://youtu.be/yGyMWYhHYoQ?t=471)
* Create a Ravine Nether Portal:
	* [Standard](https://youtu.be/yGyMWYhHYoQ) | [1-Deep]()
	* [Cobblestone Skip](https://youtu.be/H2fHDidyfJo?t=63) | [1-Deep]()
	* [2-Wide](https://youtu.be/K233ih6nSCU?t=94) | [1-Deep]()

<br/>

* You wont have any Beds, so make sure you get enough String from Piglin Trades: 7 Beds = 84 String (+21 Planks)
	* You can also use Iron Nuggets 9:1 Iron Ingots → Shears →
		* Shear Sheep in the Overworld or Collect Cobwebs in a Stronghold Library
* You wont have much Food (if any):
	* In the Nether: Craft [Mushroom Stews](https://i.imgur.com/FUo9nfP.png)
	* In the Overworld: Kill Burning Animals to get Pre-Cooked Meat
	* Optionally: Suicide to Reset Hitpoints / Hunger
		* Nether: Craft a [Respawn Anchor](https://i.imgur.com/mo7y0XA.png) → use a Glowstone Block on it → Suicide
		* Overworld: Place a Bed → Right-Click the Bed → Suicide
	* Suicide Methods: use any Method that seems convienent to you at the time
		* [Fire](https://youtu.be/itqFlGfKvdk?t=460): Burn yourself with either a Flint and Steel, or Lava (put out the Fire, so you don't destroy Items)
		* Ender Pearl: if you have excess Pearls, throw them into a nearby Wall or Floor, taking 2.5 Hearts of Damage on impact
		* Fall Damage: 1/2 Heart per Block above 3 Blocks (4 Blocks = 1/2 Heart | 7 Blocks = 2 Hearts | 15 Blocks = 6 Hearts, etc)
			* While in the Stronghold, you can climb up the Starter Staircase to easily get some height

## **Advanced+** | Pirate → Ocean Monument
***Ocean Monument Guides:* [T_Wagz](https://youtu.be/0dyHYkg_xIU) | [Silver](https://youtu.be/14FGC1eUHug) | [Silver, Part 2](https://youtu.be/-b7nQyXZkfw)**  
*Same start as [Pirate Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate-overworld), but you also Gather the guaranteed 8 Gold Blocks from an Ocean Monument - sometimes allowing you to completely skip the Bastion while in the Nether*
* Pirate Start → Shipwreck (Craft a Shield, since you wont have Fire Resistance for the Fortress) → Ocean Monument
	* As soon as you see the Ocean Monument, turn your Render Distance to 2 (RD2), this will usually result in the Elder Guardians not spawning, stopping them from giving you Mining Fatigue
	* if you get Mining Fatigue anyway, either Drink a Bucket of Milk, or set your Spawn and Suicide (or raw Suicide, near the World Spawn)
	* loot the 8 Gold Blocks from the Monument, following one of the guides linked above → Leave the Monument
	* Once you're a reasonable distance away from the Monument, set your Render Distance back to normal
* Continue with the normal Pirate Overworld strats → Ravine Nether Portal → Enter the Nether
	* The same Bed/Food limitations exist
* While in the Nether: Find a Fortress → Trade with nearby randomly spawned Piglins → Kill Blazes for Blaze Rods
	* *trap 2 Piglins in a Boat, or in a 2 Block deep hole → Throw them your Gold Ingots → Proceed into the Fortress*
		* *don't forget to return to the Piglins to collect your loot - if you didn't get enough → Find a Bastion*

## **Expert** | [Hypermodern](https://youtu.be/gAHMJfsrHe4)
*Combination of the most optimal strats, Resets are frequent, so having a very high Reset Efficiency is recommended*
* [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate-overworld) → [Ravine Nether Entry](https://youtu.be/H2fHDidyfJo?t=63) → [Microlensing](https://youtu.be/jvTfMLPnMSw) → [Bastion](https://github.com/Metacor/Minecraft_Speedrun_Guide#bastions) → [Pie-Ray](https://youtu.be/Aq9qfHNEOHM) → Fortress, [Blazebed](https://www.youtube.com/watch?v=3TD4jkuT8QA) → [Blind](https://i.imgur.com/96KhbT2.png) / [Divine](https://youtu.be/SXem01c44-I) Travel
	* if 20+ Obsidian: [Axis Calculated Travel](https://youtu.be/0LDj48fsRT8)
* [Triangulation](https://youtu.be/8c29j0We2VQ) → Starter Staircase Stronghold Entry (if Ocean exposed: Portal Room Entry) → End Entry →
	* [Half-Bow](https://youtu.be/whwjNbIni58) + North / South Ground + [One-Cycle Dragon](https://youtu.be/aGMLHXnD6Bc) (~[4 Bed](https://youtu.be/R-9PGkSJU7g))  


*Optionally*   
* Village Start: if there is a close Lava Lake | Ruined Portal | Blacksmith, with 10+ Obsidian
	* if >= 7 Iron (Blacksmith + Golem): Iron Pickaxe + Bucket + Flint and Steel
	* if 4-6 Iron: Skip Iron Pickaxe, get lucky with Bastion Chests
	* if 3 Iron: Reset (or Flintless Portal, if you REALLY want to force the seed)

<br/>

## The Nether
*Find a Bastion, Trade Gold to Piglins for Obsidian and Ender Pearls → Find a Fortress, Kill Blazes for Blaze Rods*


	Only 1 Structure can Spawn per 432, 432 MegaChunk, for Example:
		if Bastion @ +x,+z you will have to go to any of the remaining three quadrants; +x,-z | -x,-z | -x,+z
			aka; pos, pos | pos, neg | neg, neg | neg, pos
		in order to find a Fortress (or another Bastion), go to whatever direction is closer to x0/y0
		you can also go out beyond +/- 432 x or z to go into a new MegaChunk, but this may take awhile

	Bastion: if you can, do the Bastion first - Trading has a chance to give you Fire Resistance Potions
		Identify the Bastion Type, and run the route accordingly
		Mine Gold Blocks → Turn into Gold Ingots → Trap Piglins in a hole → Trade with Piglins;
			While the Piglins Trade; Loot Chests | Pie-Ray for Fortress Location, if Bastion first
			@10+ Obsidian, @16+ Ender Pearls; Leave for Fortress (if close to 20 Obsidian, you should wait)
				Optional Items; Not necessary for the run, but can make it easier
					Fire Resistance Potion; Makes you Immune to Lava / Blaze Fire damage (Not Melee)
						if multiple Potions; use one now, to avoid accidental Lava damage
					Iron (nuggets/ingots) Craft Iron Axe (if Flintless Portal, Craft Flint and Steel first)
					String; Beds (not really optional), Fishing Rod (grab roaming Blazes), Bow (see below)
					(Cross)Bow + Arrows; Half-Bow Dragon Fight, https://youtu.be/whwjNbIni58

	Fortress: https://youtu.be/iaUF0oaegns?t=3624
		Fortress Navigation: Blaze Spawners only generate in the Outside portion of the Fortress
			The Inside section will have a Netherbrick roof
			The Outside section will either have no roof, or a Netherrack/Soul Sand roof
			if looking down from above, the structure without a roof entrance leads to the open area
				if you're inside the Fortress, this room has a 1x1 pool of Lava in the middle
			Inside Navigation:
				if staircase with Netherwart at the bottom; go down the stairs
				if staircase with no Netherwart; go up the stairs
				if balcony room; go in the opposite direction of the balcony		

		When entering a Fortress, change your Render Distance to 5 (RD5), increasing nearby enemy spawns rates
			this wont change the spawn rate from Blaze Spawners, but will increase naturally spawning blazes
		Locate a Blaze Spawner → Drink/Throw Fire Resistance Potion (if acquired) → Kill Blazes;
			Loot atleast 7/8 Blaze Rods, you can Mine out around the Blaze Spawner to increase spawn rates
				Learn how to efficiently Blazebed; (put out Fires ASAP, Blazes only spawn @ Light level <= 11)
					Blazebed; https://www.youtube.com/watch?v=3TD4jkuT8QA
					BlazeTnT; https://www.youtube.com/watch?v=X3kHn0PaZW0 (suboptimal?)

	Advanced Nether Scouting Methods; saves a significant amount of time, while not being all that hard to learn
		Microlensing; Locating Bastions based on the E value in the F3 Menu
			https://www.youtube.com/watch?v=jvTfMLPnMSw
			https://www.youtube.com/watch?v=Ou58P7e-ZY0
		Pie-Ray; Locating Fortresses based on Blaze Spawner Entities in the Shift+F3 Pie Chart
			keep in mind, Treasure Bastions also have a Spawner, sometimes causing a false positive
			to quickly update the pie chart, find RD, -RD4, +RD3 (use keybinds; Shift + F3 + f, F3 + f)
			https://youtu.be/Ou58P7e-ZY0?t=109 (same video as above)
			https://www.youtube.com/watch?v=Aq9qfHNEOHM

	Blind Travel: Optimal Nether Coordinates, y = 64+
		First Ring; https://i.imgur.com/96KhbT2.png
		1st/2nd/3rd; https://imgur.com/gallery/i3fIanf
	Educated/Calculated Travel: Requires 20+ Obsidian, https://www.youtube.com/watch?v=0N8Wj8hOVKM
		Educated = Throw 1 Eye, then Blind at ~normal Coordinates in the correct direction
		Calculated = Throw 2 Eyes, Triangulate the Stronghold's distance for a better Blind
			Axis Calculated Guide (very precise calculated travel); https://youtu.be/0LDj48fsRT8

<br/>

## The Overworld, Part 2
*Find the Location of a Stronghold → Enter it and Navigate to the Portal Room → Enter The End*


	Stronghold Navigation: Minimum 1400 Blocks away from 0,0 (~175 in the Nether, since Distance is 8:1)
		This is calculated Triangularly not linearly, so a²+b²=c², not a+b=c | 150x,150z = 212, not 300
			Generally if you're just adding x+z, 2000-2400 for The Overworld, 250-300 for the Nether

	Triangulation: Throwing multiple Eyes and calculating their angle differences to find the Stronghold
		Simple Methods; 
			17.5 Block Method - Makes ° calc very simple (1000 / x° = distance)
				https://i.imgur.com/6rvw5Bb.png
				https://i.imgur.com/uutGOSx.png
				https://www.youtube.com/watch?v=8c29j0We2VQ
			20 Block Method - Easier to move 20 blocks instead of 17.5, but makes the math harder
				https://i.imgur.com/vZAaWp8.png
				https://www.youtube.com/watch?v=LgRTgPTzoXU
		Indepth Explainations;
			https://www.youtube.com/watch?v=Zy7XEr-zl_A
			https://www.youtube.com/watch?v=tkv2Jb-8Oqo
		NinjaBrain Axis Calculated, (can be used for general Triangulation); https://youtu.be/0LDj48fsRT8
		Change FoV to 30 when Recording the Angle for a more precise Triangulation;
			Either go to 30 FoV at the start, and back to your normal FoV after Triangulation, or
			Throw Eye → Look @ Eye → FoV: 30 → Record ° → FoV: Reset → Move → Repeat for Second Eye
				It could also be useful to go into Third Person View when throwing the Eye (default F5)
				to make sure you know which direction it flew, (still look at the Eye in First Person View)
				if you don't want to use F5, you could also just look at the ground when you throw
		Locate the Stronghold; when close, do another Triangulation near the Stronghold to find the exact Chunk

	Enter the Stronghold
		if Entering from above, Dig @ 4/x/4 (3,4,5/x/3,4,5 all work) in the Chunk to enter the Starter Staircase
		if not entering @ the Starter Staircase; Go through Backwards Doors until you find it
		on entering the Portal Room, run up the stairs → place a block in the lava → stand on it →
			Place Eyes of Ender into the End Portal Frames, on the final Frame, you will be teleported to The End
			
<br/>

## The End
*Kill the Ender Dragon, Finishing the Game*


		End Guide: https://youtu.be/-Ta_1R1aXvA
		In-depth explainations: https://youtu.be/1daiTbj1OiE
		One-Cycle Tips: 
			https://www.youtube.com/watch?v=aGMLHXnD6Bc
			https://www.youtube.com/watch?v=uBp8uVbW1us

	Get to the Fountain asap → setup the bed platform → run in your desired direction
	if 2+ Pearls; Pearl to the highest tower in your desired direction (N/S/E/W), build up to y = 122
		if the Dragon fireballs you, either dodge it, or get hit on purpose then jump → place a block below you
	F3 + B to enable Hitboxes for the Dragon fight, also helps with recognizing the Perch
	When the Dragon starts to Perch, Pearl/Run to the fountain and Kill it with beds
	
<br/>

# Keybinds & Shortcuts
## F3 Keybinds
**F3**: Standard F3 Menu

**F3 + F4**: Game Mode Selection | Open to LAN → Allow Cheats: ON → Start LAN World → F3 + F4 *(after a Failed Run)*

**F3 + Q**: Shows most of the F3 Commands in-game 

**F3 + G**: Chunk Borders

**F3 + B**: Entity Hitboxes  

**Useful for [Pie-ray](https://www.youtube.com/watch?v=Aq9qfHNEOHM) scouting:**
* **Shift + F3**: Pie Chart F3 Menu | Tick → Level → Entites → Block Entites
* **F3 + F**: Increases Render Distance by 1
* **F3 + Shift + F**: Decreases Render Distance by 1

		
## Inventory Management
*Storage Interfaces: Chests, Crafting Tables etc*  

**Hotbar Swap**: *1, 2, 3, 4, 5, 6, 7, 8, 9*
* Swaps the Hotbar Slot's Item, with the Item Slot under your Mouse's Cursor
* *this can be used to Quickly Move Items into the Crafting Window, with minimal Mouse Movement*

**Pick Block**: *Middle Mouse Button*
* Swaps your currently Selected Hotbar Slot with the Item that your Crosshair is pointed at
	* *this is assuming that you have any of that Item Type in your Inventory already*	
	* *if the Item is in another Hotbar Slot, you will simply switch Hotbar Selections*
	* *if the Item is in your Inventory, then it will be moved to the lowest available Empty Slot*
		* *unless you are currently Selecting an Empty Slot, in that case, the Item will move to that Slot, even if that particular Slot is not the lowest available*
	* *if no Empty Slots are available, then your currently Selected Item will be Swapped into your Inventory*
* *using Pick Block to select Beds while One Cycling the Dragon is very useful*

**Drop Item**: *Q*
* Drops an Item
* *which Item you will drop depends on if your Inventory is Currently Opened or Closed
	* *Inventory Opened: Drops Currently Hovered Item*
	* *Inventory Closed: Drop Currently Selected Item*
* *holding the Control key while pressing Q will drop the entire Stack of Items in that Item Slot*

**Transfer Item**: *Shift + Click (left **or** right, both work)*
* Sends the Item that your Cursor is currently Hovering over To/From your Hotbar/Inventory
* *if a Storage Interface is currently Open, then the Item will Transfer between that and your Inventory instead*

**Equip Item**: *Right Click **or** Shift + Click (transfer item)*
* Puts an Equipable Item onto your Character's corresponding Equipment Slot
* *the Keybind depends on if your Inventory is currently Opened or Closed*
	* *Inventory Opened: Shift + Click (transfer item)*
	* *Inventory Closed: Right Click (selected item)*
* *both of these methods require the Equipment Slot to be currently Empty, otherwise you will need to Manually Equip*

**Half Split**: *Right Click*
* Selects half a Stack of an Item, leaving the other half in the Slot that you Selected it from
* *requires your Inventory to be Opened*
* *requires you to currently not have anything Selected*

**Drag Split, 1**: *Select an Item → Hold Right Click → Drag*
* Splits off 1 Item into each Slot that you Drag a Stack of Items over
* *press Left Click to undo the current Split Selection, (before releasing Right Click)*

**Drag Split, x**: *Select an Item → Hold Left Click → Drag*
* Equally Splits a Stack of Items between all Slots that you drag a Stack of Items over
	* *stack of 30: 2 Slots x 15 Items | 3 Slots x 10 Items | 4 Slots x 7 Items (+2), etc*
* *press Right Click to undo the current Split Selection, (before releasing Left Click)*

**Select All of an Item Type**: *Double Left Click | Triple Left Click*
* Combines All Stacks of an Item Type into 1 Stack *(Max Stack Limits still apply)*
* *the Keybind depends on if you currently have an Item Selected or not*
	* *if nothing is Selected, Double Click the Item*
	* *if the SAME Item Type is Selected, Triple Left Click the Item*
	* *if an unrelated Item is Selected, you CANNOT Select All*
		* *trying to do so would just Select the Items back and forth*

**Transfer All of an Item Type**: *Shift + Double Left Click*
* Sends All Items of the same Type between Storage Interfaces and your Inventory
	* *the Chest Interface will prioritize your Hotbar, before putting items into your Inventory*
	* *the Inventory and Crafting Interfaces will prioritize putting items into your Inventory first*
* *requires an Item to be currently Selected, otherwise you will just instantly send over a single Stack*
	* *your current Selected Item Stack will not be Transferred*
	* *to easily send ALL of an item type, have an unrelated Item Selected*
		
<br/>

# Tips & Tricks
### The Overworld
* Shipwrecks 
	* Front Side Chest: Food 
	* Back Side: 
		* Top Chest: Iron Ingots, Gold Ingots
		* Bot Chest: Buried Treasure Maps
			* Buried Treasure is always located @ 9/x/9 in the Chunk where the X is located 
* Ocean Monuments
	* Guardian Lazer Hits taken to Kill you, without Healing (Damage/20): Easy = 5 (4) | Normal = 4 (6) | Hard = 3 (9)
		* with Healing, Easy will almost always take 6 hits, and Normal will sometimes take 5 
* [Desert Temples](https://youtu.be/gS6LxaNibWM?t=76)
	* To quickly collect all of the Chests, aswell as any surrounding Blocks
		* Collect all of the TnT → Place 1 TnT under you → 
		* Place 1 TnT in a Corner on the Top → 
		* Place a Pressure Plate next to it → 
		* Activate the Pressure Plate →
		* Break the TnT below you (don't activate it) →
		* Crouch in the hole under the active TnT, avoiding most of it's Damage
* It takes slightly less time to Mine Stone than it does to Mine Cobblestone
	* Wooden Pickaxe: Stone takes **1.15 Seconds** | Cobblestone takes **1.5 Seconds**
	* Stone Pickaxe: Stone takes **0.6 Seconds** | Cobblestone takes **0.75 Seconds**
* Lava Lakes
	* if you're unable to find a Lava Lake on the surface, try digging near small surface Water Lakes
		* Lava Lakes tend to spawn underneath Water Lakes
* [Ocean Ravines](https://youtu.be/yGyMWYhHYoQ?t=471)
	* While searching for Ocean Ravines, look out for Kelp - it tends to spawn above Ravines
	* if you see floating Kelp in a Deep Ocean, there is likely a Ravine below it
* [Glitchy Buckets](https://youtu.be/EjwStTX4U3A)
	* if you're having trouble with Glitchy Buckets while making Nether Portals, watch the video posted above
* Buckets of Water don't actually work in the Nether, so when you finish your Nether Portal, fill the Bucket with Lava

### The Nether
* Falling while in a Boat will negate all Fall Damage: [Video](https://youtu.be/REas9cmjlic?t=686)
* Killing Burning Hoglins is an easy way to get food in the Nether [Lava Bucket](https://youtu.be/iaUF0oaegns?t=3861) | [Flint and Steel](https://youtu.be/REas9cmjlic?t=694)
* if you need more Blocks while in the Nether, Mine some Netherrack
	* Netherrack isn't flammable, and it's fast to Mine (0.1s with an Iron Pickaxe)
* if there is a far away Ghast attacking you, quickly lower your Render Distance to 2
	* [This will usually despawn the Ghast](https://youtu.be/tWVrxt0G6r0?t=696)
	* You can turn your Render Distance back up after it disappears
* if you find Nether Gold Ore while travelling to a Bastion, consider Mining it and making Gold Boots
	* Boots only take 4 Gold Ingots (36 Gold Nuggets)
	* Wearing any Gold Armor will make it so Piglins don't auto-aggro you
* Piglins have weird pathfinding around Lava
	* *when building bridges across Lava - while routing bottom side Housing Manhunt for example*
		* *build 1 block above Lava (instead of inside of it)*
			* *if forced to build inside, use stairs at the ends of your bridge*
			* *piglins seem to refuse to jump up/down a block at the edges of lava*
		* *build 3 Blocks wide, to make sure Piglins follow*
		* *piglins can't run across corners, so make sure there is a direct path over the Lava*
* Bastions cannot spawn inside of a Basalt Delta Biome
* All of the Bastions (besides Treasure), can spawn a Triple Chest, top section - to easily tell them apart:
	* if there are 2 Blocks between the Double/Single Chest, then it's Stables
	* if there are 3 Blocks, then it can be either Housing or Bridge
		* Housing and Bridge are very different, so it shouldn't be too hard to Identify the correct one
* Mobs spawn more often in Soul Sand Valleys, so if a Fortress is located in one, 5RD is pretty risky
* While trying to Pie-Ray, if you accidentally press the wrong button, press '0' to go back a page
	
### The Overworld, Part 2
* When travelling across Water, it is faster to use a Dolphin's Boost, than it would be to use a Boat
* if you find an underwater Stronghold, make sure to look around for the Portal Room before blindly entering
* Strongholds are extremely unlikely to spawn in Swamps ([supposedly](https://youtu.be/_rbWryJVEmw?t=1011))
* The Portal Room is usually within 5-7 Rooms of the Starter Staircase
* In the Stronghold, Spiral Staircases always lead up, towards the Starter Staircase
* Libraries lead nowhere, if you enter a Library from the Starter Staircase, turn around
	* if you need more Beds, you can Gather string from Library Cobwebs 
		* make sure to use either a Sword or Shears, (decreasing the Gather Time from 20s → 0.4s)

### The End
* You always Spawn to the East, facing the Main Island
	* *if you spawn underground, Dig up in the top left corner*
* The Dragon Perches faster the farther away you are from the Fountain, both height and distance
* The Dragon will Perch from the opposite side of you, in relation to the Fountain
	* *Diagonal Perches are a lot harder to One Cycle, so it's recommended to run away N/S/E/W*
	* *N/S Perch is faster than E/W, however it gives the player less time to react to the Perch*
* The Dragon's Fireball doesn't actually do damage, the AoE ground effect it leaves behind does
	* an easy way to avoid the damage is to get hit on purpose, then Jump → place a Block below you
		
<br/>

# Practice
*Ideally, get comfortable with each of these steps before starting runs*

# @@@@@@@ ADD PIRATE STUFF TO PRACTICE @@@@@@@@@@

### Crafting  
*learn to quickly, and optimally, complete the most common early game Crafting Windows*  

**Notation:**
* *sClick: Shift + Click | lClick: Left Click | rClick: Right Click*
* *item(num): Press that Hotbar Keybind into the Crafting Window*
	* *if item(num), xX: Put the Item into that specific Crafting Window Slot*
* *xX: tL,tM,tR - mL,mM,mR - bL,bM,bR*
	* *first, small letter is top/middle/bottom (row)*
	* *second, Big letter is Left/Middle/Right (column)*  

*the given intructions/screenshots will only be for the most optimal version, even if multiple videos are provided*  

**Crafting Table + Sticks**: *used in practically every run*  
[Screenshot](https://i.imgur.com/pzABDu2.png) | Videos: **[Optimal (8 Clicks)](https://youtu.be/TeFeMmjoUIc?t=28)** | [Split 2 → Left Click (10 Clicks)]() | [Double Split (10 Clicks + bad planks)]()
* Gather 3 Logs, turn them into 12 Planks, then Craft a Crafting Table and 8 Sticks
	* Logs(1) → collect: sClick → Planks(9), bR → Half Split → Drag bR, bL, tL → lClick tR → collect: sClick x2  

**Wooden Pickaxe**: *used in non-pirate strats | unless: 3+ Iron from Blacksmith, or Golden Pickaxe from Ruined Portal*  
[Screenshot](https://i.imgur.com/k3vCKuq.png) | [Video]()
* Place the Crafting Table, Craft a Wooden Pickaxe, then Mine 6 Cobblestone
	* Sticks(8), bM → Half Split → lClick mM → Planks(1), tL → Half Split → Drag tM, tR → collect: 8
		* *highly recommend to collect to your Pickaxe Hotbar Keybind, instead of shift + clicking*
		* *i have my hotkey set to 8, rebound to f, just collect to whatever yours is bound to*

**Stone Tools**: *used in non-pirate strats | if you don't want a Hoe, Mine 4 Stone instead - can use the same movements*  
[Screenshot](https://i.imgur.com/TCqDxat.png) | [Video]()
* Craft a Stone Axe, a Stone Shovel, and a Stone Hoe
	* Sticks(2), bM → Half Split → lClick mM → Stone(3), tM → Half Split → rClick mL → lClick tL → collect: 7 → 4 → 5
		* *once again, i'd recommend collecting directly to your axe/shovel/hoe slots*

### Tasks  
*learn to efficiently complete these tasks*  

**Villages**  
* Kill the Golem → Craft an Iron Pickaxe and a Boat 
	* *if Bucket of Cod Trade: also Craft a Composter and a Barrel → Trade with Villagers*
* Identify which Houses have Beds in them, and which don't
	* *also identify which houses have Carpets in them, in case you need to do a Flintless Portal*

**Nether Portal Constructions**
* Lava Lake Nether Portal
	* Standard
	* Flintless
	* Carpet Flintless
* Ocean Ravine Nether Portal
	* Standard
	* Cobblestone Skip
	* 2-Wide
* 1-Deep verions of all of the Above

**Bastions**  
* [Identification and Optimal Routing](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#bastions)
* Microlensing: Locate a Bastion from your Nether Portal

**Fortress**  
* Inside Navigation: Find your way to the outside section of the Fortress and find a Blaze Spawner
* Blazebed: Learn to execute the correct technique for both enclosed and open spawners
* Pie-Ray: Locate the Fortress direction using the F3 Pie Chart *(also useful for finding Villages)*

**Stronghold**  
* Blind Travel: Try to remember the general Coordinates for atleast the First Ring
* Triangulation: Quickly and accurately turn 90°, and be able to consistently travel 17.5 Blocks
* Stronghold Navigation: Complete a lot of Stronghold trial runs, starting from random positions

**The End**
* Force a N/S Perch, and be able to tell when the Dragon is Perching
* One Cycle with <= 7 Beds - with both Obsidian, and either Full or Slab Block Setups *(no obby backup)*
	
<br/>

# Speedrun Cheatsheet:
### [Blind Travel](https://imgur.com/gallery/i3fIanf)
**First Ring**


0 , 220 | 50 , 210 | 75 , 200 | 100 ,  190 | 125 , 175 | 155 , 155

**Second Ring**


0 , 620 | 100 , 610 | 150 , 600 | 200 , 585 | 250 , 565 | 300 , 540 | 350 , 510 | 435 , 435

**Third Ring**


0 , 1010 | 200 , 900 | 300 , 965 | 400 , 930 | 500 , 880 | 600 , 815 | 715 , 715

### [Triangulation](https://i.imgur.com/6rvw5Bb.png)
**1° = 1000 Blocks (Math = 1000 / x)**

| x | x.0 | x.1 | x.2 | x.3 | x.4 | x.5 | x.6 | x.7 | x.8 | x.9 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| 0 | - | - | - | - | 2500 | 2000 | 1660 | 1430 | 1250 | 1110 |  
| 1 | 1000 | 910 | 835 | 770 | 715 | 665 | 625 | 590 | 550 | 525 |  
| 2 | 500 | 475 | 455 | 435 | 415 | 400 | 385 | 370 | 355 | 345 |  
| 3 | 333 | 320 | 310 | 305 | 295 | 285 | 275 | 270 | 265 | 255 |  
| 4 | 250 | 245 | 240 | 230 | 225 | 220 | 215 | 210 | 210 | 205 |      
