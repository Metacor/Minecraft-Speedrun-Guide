# Minecraft: Speedrun Guide - Any%, RSG, 1.16
[Discord](https://discord.com/invite/jmdFn3C) | [Website](https://www.minecraftspeedrunning.com/) | [Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki) | [Leaderboard](https://www.speedrun.com/mc#Any_Glitchless)

### To Do:
* Add Crafting Screenshots for each mention of Crafting an Item *(similarly to: Craft a [Composter](https://i.imgur.com/xRd6xYT.webp))*
	* *change all current Screenshots to be cropped the same as above, name/mats/window (2 gray lines)*
		* *use the [Crafting](https://minecraft.fandom.com/wiki/Crafting) wiki page to get the correct windows*
	* *take screenshots @ 250% zoom level, post imgur links as direct link (i.imgur.com/image.webp)*
* Add Links to all Video / Section / Item references, even if they have previously been linked to
* Check the skinny main view to make sure there isn't any unnecessary text wraps
* Spell Check / Phrasing Check the entire document *(missed words, poor punctuation, unclosed italics, etc)*
* Keep consistent Capitalization *(make sure all instances of an item/entity/word are the same)*
	* *words after a : or → should be treated as a new sentence*
	* *The first word of each sentence should be Capitalized*
		* *unless it's an italicized clarifying statement, such as this*
			* *Special Capitalized words should still be Capitalized in these comments*
				* *such as Item, Damage, Block, Nether*
					* *the "the" in "the Nether" should only be Capitalized if it's the first word in the sentence*
		* *all cases of "if" should be lower-case, even if it's the start of a sentence*
* Double Check every Link to make sure it actually links something *(and make sure it leads to the correct place)*
* Make sure there isn't any superfluous information in the Speedrun Guide section *(move it to Tips & Tricks)*

<br/>

## Table of Contents
* [Setup](https://github.com/Metacor/Minecraft_Speedrun_Guide#setup)
	* [Mods](https://github.com/Metacor/Minecraft_Speedrun_Guide#mods)
	* [Practice Maps](https://github.com/Metacor/Minecraft_Speedrun_Guide#practice-maps)
	* [F3 Keybinds](https://github.com/Metacor/Minecraft_Speedrun_Guide#f3-keybinds)
	* [Inventory Management](https://github.com/Metacor/Minecraft_Speedrun_Guide#inventory-management)
* [Speedrun Guide](https://github.com/Metacor/Minecraft_Speedrun_Guide#speedrun-guide)
	* [The Overworld](https://github.com/Metacor/Minecraft-Speedrun-Guide#the-overworld)
		* [Structureless](https://github.com/Metacor/Minecraft_Speedrun_Guide#beginner--structureless)
		* [Village](https://github.com/Metacor/Minecraft_Speedrun_Guide#standard--village)
		* [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate)
			* [Pirate → Ocean Monument](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate--ocean-monument)
		* [Hypermodern](https://github.com/Metacor/Minecraft_Speedrun_Guide#expert--hypermodern)
	* [The Nether](https://github.com/Metacor/Minecraft_Speedrun_Guide#the-nether)
		* [Microlensing](https://github.com/Metacor/Minecraft-Speedrun-Guide#microlensing-aka-e-ray)
		* [Bastions](https://github.com/Metacor/Minecraft-Speedrun-Guide#bastions)
		* [Pie-Ray](https://github.com/Metacor/Minecraft-Speedrun-Guide#pie-ray-aka-piedar)
		* [Fortress](https://github.com/Metacor/Minecraft-Speedrun-Guide#fortress)
		* [Travel](https://github.com/Metacor/Minecraft-Speedrun-Guide#travel)
	* [The Overworld, Part 2](https://github.com/Metacor/Minecraft_Speedrun_Guide#the-overworld-part-2)
		* [Triangulation](https://github.com/Metacor/Minecraft-Speedrun-Guide#triangulation)
		* [Stronghold](https://github.com/Metacor/Minecraft-Speedrun-Guide#stronghold-navigation)
	* [The End](https://github.com/Metacor/Minecraft_Speedrun_Guide#the-end)
* [Tips & Tricks](https://github.com/Metacor/Minecraft_Speedrun_Guide#tips--tricks)
* [Practice](https://github.com/Metacor/Minecraft_Speedrun_Guide#practice)
* [Speedrun Cheatsheet](https://github.com/Metacor/Minecraft_Speedrun_Guide#speedrun-cheatsheet)

# Setup 
[k4yfour](https://youtu.be/4cTbSyvWNgI) | [DashPum4](https://youtu.be/km0sXurMj5s) | [Lenszel's Speedrunning Tools List](https://docs.google.com/document/d/1REEzqLCmOizEhY797kLCXI4I0ftm4N-u8aaD8ECzIw8/edit)

**Before Launching**
* Win + r → %appdata% → .minecraft → options.txt → **gamma:5.0**

**In-game**
* Options → Music & Sounds → **Show Subtitles: ON**
* Options → Video Settings → Quality → **Entity Distance (500)**

**With Sodium Mod**
* Options → Video Settings → Advanced → **Disable Entity Culling**
	* *Disabling Entity Culling isn't required for Sodium v0.2.0+*
* Options → Video Settings → Unofficial → **Enable Planar Fog**  

**Timers**: [Livesplit](https://livesplit.org/downloads/) | [NinjaSnail1080's Minecraft Universal Timer](https://github.com/NinjaSnail1080/mc-universal-in-game-timer) - [Video](https://youtu.be/fPESBmKYi0Q)

## Mods
[Website](https://www.minecraftspeedrunning.com/public-resources/mods ) | [Explainations](https://youtu.be/km0sXurMj5s?t=126)  
### Fabric Loader *(DON'T USE FABRIC API)*: [Website](https://fabricmc.net/use/) | [Download](https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.7.4/fabric-installer-0.7.4.jar)  
* Auto Reset Mod: [Website](https://github.com/DuncanRuns/AutoResetMod) | [Download](https://github.com/DuncanRuns/AutoResetMod/releases/download/v1.2.0/autoreset-1.2.0+MC1.16.1.jar)
	* When Active, on pressing Quit: Quits → Creates a New World, with correct Settings → Loads the World
	* *[Guide](https://youtu.be/km0sXurMj5s?t=187) to reset with a Hotkey and cull Saved World files using AutoHotKey*
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
* Sethbling's Speedrun Datapack: [Video](https://youtu.be/UihtGJhK_-w) | [Download](https://sethbling.s3-us-west-2.amazonaws.com/Downloads/DataPacks/speedrun_practice.zip)
* AndyNovo's Mapless Treasure Seed Generator Tool: [Website](https://replit.com/@AndyNovo/JustLearnTreasure) | [Example](https://i.imgur.com/8Q7Vp6B.webp)
* Semper's Nether Portal: [Video](https://youtu.be/K233ih6nSCU) | [Download](https://www.mediafire.com/file/1oanxrh14db4u7g/Portal_Practice.zip/file)
* Llama's Bastion: [Video](https://youtu.be/jlA-jW7VGqw) | [Download](https://www.dropbox.com/s/9e103bjzroi85aa/Llama%27s%20Bastion%20Practice%20v2.6.1.zip?dl=0) | [Loadout Guide](https://youtu.be/uTn9LwB5WAE)
* Semper's Blaze: [Video](https://youtu.be/CNqrnlgCRXk) | [Download](https://www.mediafire.com/file/2c6vo3qt9hv3qp5/Blaze_Practice.zip/file)
* Emma's End: [Video](https://youtu.be/fV5B7xJmiZU) | [Download](https://sites.google.com/view/emma-practice-map/home)

## F3 Keybinds
* **F3**: Standard F3 Menu  
* **F3 + F4**: Game Mode Selection
	* *Open to LAN → Allow Cheats: ON → Start LAN World → F3 + F4*
		* *enabling cheats will invalidate the run, only do this after an already failed attempt* 
	* ***F3 + N** will directly toggle Spectator Mode*
* **F3 + Q**: Shows most of the F3 Commands in-game  
* **F3 + G**: Chunk Borders  
* **F3 + B**: Entity Hitboxes  

**Useful for [Pie-Ray](https://github.com/Metacor/Minecraft-Speedrun-Guide#pie-ray-aka-piedar) and [Mapless Treasure](https://youtu.be/_dyD8ZwagDg):**
* **Shift + F3**: Pie Chart F3 Menu
	* **Pie-Ray**: *Tick → Level → Entites → Block Entites*
	* **Mapless Treasure**: *gameRenderer → Level → Entites*
* **F3 + F**: Increases Render Distance by 1
* **F3 + Shift + F**: Decreases Render Distance by 1

## Inventory Management
**I would highly recommend changing your Hotbar Keybinds to something more comfortable** [Example](https://i.imgur.com/IRnM4qO.webp)  
* pressing 6-9 for Hotbar Hotkeys can be quite inconsistent, and remember: [don't scroll, kids](https://youtu.be/0mK4yq7AlvE?t=12)

**Hotbar Swap**: *1, 2, 3, 4, 5, 6, 7, 8, 9*
* Swaps the Hotbar Slot's Item, with the Item Slot under your Mouse's Cursor
* *this can be used to quickly Move Items into the Crafting Window, with minimal Mouse Movement*

**Collect All**: Shift + Click *(in the Crafting Output Slot)*
* Creates the maxiumum amount of an Item with the supplies currently in the Crafting Window
	* *will only Craft the Item currently shown in the Output Slot, even if the [Supplies can create multiple Items](https://i.imgur.com/TCqDxat.webp)*
		* *the Crafting Window above can Craft 1x Stone axe, 1x Stone Hoe, and 1x Stone Shovel*
		* *however, Shift + Clicking will only create the Stone Axe (and then the Hoe, and finally the Shovel)*
* Sends all of the Crafted items onto your Hotbar
	* *sends items to the highest available Hotbar Slot (9 > 8 > 7, etc)*
	* *if your Hotbar is full, the Items will be sent to your Inventory instead*

**Pick Block**: *Middle Mouse Button*
* Swaps your currently Selected Hotbar Slot with the Item that your Crosshair is pointed at
	* *this is assuming that you have any of that Item Type in your Inventory already*	
	* *if the Item is in another Hotbar Slot, you will simply switch Hotbar Selections*
	* *if the Item is in your Inventory, then it will be swapped to the lowest available Empty Slot*
		* *if you're currently Selecting an Empty Slot, the Item will be Moved to that Slot instead*
			* *even if your currently Selected Slot isn't the lowest available*
	* *if no Empty Slots are available, then your currently Selected Item will be Swapped into your Inventory*

**Drop Item**: *Q*
* Drops an Item
* *which Item you drop will depend on if your Inventory is currently Opened or Closed*
	* *Inventory Opened: Drops currently Hovered Item*
	* *Inventory Closed: Drop currently Selected Item*
* *holding the Control key while pressing Q will drop the entire Stack of Items in that Item Slot*

**Transfer Item**: *Shift + Click (left **or** right, both work)*
* Sends the Item that your Cursor is currently Hovering over To/From your Hotbar/Inventory
* *if an Interface is currently Open, then the Item will Transfer between that and your Character instead*
	* *the Chest Interface will prioritize your Hotbar, before putting items into your Inventory*
	* *the Crafting Interface will prioritize putting items into your Inventory first*

**Equip Item**: *Right Click **or** Shift + Click (transfer item)*
* Puts an Equipable Item onto your Character's corresponding Equipment Slot
* *the Keybind depends on if your Inventory is currently Opened or Closed*
	* *Inventory Opened: Shift + Click (transfer item)*
	* *Inventory Closed: Right Click (selected item)*
* *if the Equipment Slot is currently occupied, open your Inventory and either:*
	* *unequip the currently Equiped Item → Equip Item*
	* *Drag your new Item onto the relevant Equipment Slot*

**Half Split**: *Right Click*
* Selects half a Stack of an Item, leaving the other half in the Slot that you Selected it from
* *requires you to currently not have anything Selected*

**Drag Split, 1**: *Select an Item → Hold Right Click → Drag*
* Splits off 1 Item into each Slot that you Drag a Stack of Items over
* *press Left Click to undo the current Split Selection, (before releasing Right Click)*

**Drag Split, x**: *Select an Item → Hold Left Click → Drag*
* Equally Splits a Stack of Items between all Slots that you drag a Stack of Items over
	* *stack of 30: 2 Slots x 15 Items | 3 Slots x 10 Items | 4 Slots x 7 Items (2 remaining), etc*
* *press Right Click to undo the current Split Selection, (before releasing Left Click)*

**Select All of an Item Type**: *Double Left Click | Triple Left Click*
* Combines All Stacks of an Item Type into 1 Stack *(Max Stack Limits still apply)*
* *the Keybind depends on if you currently have an Item Selected or not*
	* *if nothing is Selected, Double Left Click the Item*
	* *if the SAME Item Type is Selected, Triple Left Click the Item*
	* *if an unrelated Item is Selected, you CANNOT Select All*
		* *trying to do so would just Select the Items back and forth*

**Transfer All of an Item Type**: *Shift + Double Left Click*
* Sends All Items of the same Type between Storage Interfaces and your Character
	* *the Transfer Item Interface priorities apply here aswell*
* *requires an Item to be currently Selected, otherwise you will just instantly send over a single Stack*
	* *your current Selected Item Stack will not be Transferred*
		* *to easily send ALL of an item type, have an unrelated Item Selected*

<br/>

# Speedrun Guide  
[Haroon Shah, Jun 2021](https://youtu.be/iaUF0oaegns) | [Nuskapuska, Mar 2021](https://youtu.be/0PXQvPNCxy8) | [Couriway, Dec 2020](https://youtu.be/REas9cmjlic) | [LiquidCandy, Dec 2020](https://youtu.be/14XeowuYgV0) | [Cuffep, Oct 2020](https://youtu.be/GQodZBfdL3g)  

## The Overworld

### **Beginner** | [Structureless](https://youtu.be/7dOca1LHefk)  
*Lower speed potential, but more consistent, resulting in far fewer resets*
* Gather 3 Logs → Craft 12 [Planks](https://i.imgur.com/kkWqvQM.webp) → Craft a [Crafting Table and 8 Sticks](https://i.imgur.com/3Is7R0F.webp)
* Find a nearby Cave → Descend into the Cave until you find Iron Ore
* Place the Crafting Table → Craft a [Wooden Pickaxe](https://i.imgur.com/AgRcfOf.webp) → Mine 3 Stone → Craft a [Stone Pickaxe](https://i.imgur.com/YdNn79N.webp) → 
	* Mine 7 Iron *(8 - if you want to Craft a [Shield](https://i.imgur.com/nyxJaf0.webp))*, 12 Stone, and 1-2 Coal
* Craft a [Furnace, a Stone Axe, and a Stone Shovel](https://i.imgur.com/aAeeqXo.webp) → Pickup the Crafting Table
* Resurface → Place the Furnace near a Tree → Smelt the Iron Ore → Chop 8+ Logs
	* Collect the first Iron Ingot → Search for Gravel → Dig for Flint → Craft a [Flint and Steel](https://i.imgur.com/XzZEIrF.webp)
	* Kill Burning Animals to get Pre-Cooked Meat
		* While Searching for Gravel / Animals: Collect [Dandelions or Blue Orchids](https://i.imgur.com/ma3RZTB.webp) (for Suspicious Stews)
* Collect the Iron once it's done → Place the Crafting Table → Craft an [Iron Pickaxe](https://i.imgur.com/lDMvU7r.webp), a [Bucket](https://i.imgur.com/eA21HpJ.webp), a [Boat, and Bowls](https://i.imgur.com/6OhCaRt.webp)
* Find a nearby Lava Lake, or Dig deeper in the Cave to find Lava → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* While in the Nether, Collect Mushrooms in order to Craft [Suspicious Stews](https://i.imgur.com/zl00UZT.webp)

### **Standard** | Village  
*Spawn with a nearby Village - Ideally a Plains, Desert, or Savanna Village (for the guaranteed Hay Bales)*  
*if the Village is in a Desert, Gather Wood and Stone before entering - Trees don't spawn, and buildings are Sand*  
*if high rolled, Taiga Villages have a chance to be very good, however on average they're worse than the ones above*  
*if you don't see a Village near your spawn, optionally try to [Pie-Ray](https://github.com/Metacor/Minecraft-Speedrun-Guide#pie-ray-aka-piedar) to locate one*

* Gather 3 Logs → Craft 12 [Planks](https://i.imgur.com/kkWqvQM.webp) → Craft a [Crafting Table and 8 Sticks](https://i.imgur.com/3Is7R0F.webp)
* Place the Crafting Table near your Mining Destination → Craft a [Wooden Pickaxe](https://i.imgur.com/AgRcfOf.webp) → Mine 6 Stone → 
	* Craft a [Stone Axe, a Stone Hoe, and a Stone Shovel](https://i.imgur.com/UDSN7Uc.webp) → Pickup the Crafting Table → Chop 8+ Logs 
 
**Village Tasks:**  
* Loot Blacksmiths, if available:
	* if 10+ Obsidian: Skip Bucket → Mine 4 Stone, *(instead of 6)* → Skip Crafting a Stone Hoe
		* *still Collect 5-10 Hay Bales by hand in order to Craft [Bread](https://i.imgur.com/zq8lZ3M.webp)*
	* if 3+ Iron Ingots: Gather 2 Logs, instead of 3 → Skip Crafting a Wooden Pickaxe
	* if 7+ Total Iron Ingots *(Blacksmith + Golem)*: Skip Trading for a Bucket of Cod 
		* *you can skip with 6 Iron, but that will require a [Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=9)*
* Collect Beds from the Village Houses, *(and Carpets, if you plan on doing the [Carpet Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=38))*
* Kill the Golem: Drops 3-5 Iron Ingots
	* Hit the Golem from max Distance, from behind if possible → Run a few Blocks away → Build up 3 Blocks
	* Crit the Golem ~8 times to Kill it: Jump → Fall → Attack, while Falling *(with Stone Hatchet)*
* Place the Crafting Table → Craft an [Iron Pickaxe](https://i.imgur.com/lDMvU7r.webp) and a [Boat](https://i.imgur.com/DVab0D2.webp)
	* if Bucket of Cod Trade: Place this Crafting Table near Villagers, additionally: Craft a [Composter](https://i.imgur.com/i0LLq5Q.webp) and a [Barrel](https://i.imgur.com/Mbx8xyo.webp)
	* if 4 Iron Ingots: Craft a [Flint and Steel](https://i.imgur.com/XzZEIrF.webp), *(after getting Flint from Digging up Gravel)*
		* *if you only get 3 Iron Ingots: [Flintless Portal](https://youtu.be/axHdNQtPOf8?t=66), or Search for a Shipwreck/Ruined Portal*
	* if 5 Iron Ingots: Save 1 Iron to Craft a [Shield](https://i.imgur.com/nyxJaf0.webp), in case you get a Fortress before a Bastion in the Nether
* Hoe 7 Hay Bales → Craft Wheat (7:63) → Hoe 5-10 additional Hay Bales → Complete the Bucket of Cod Trade
	* Find or Craft a [Composter](https://i.imgur.com/i0LLq5Q.webp) → Turn a Villager into a Farmer → Trade Wheat 60:3 Emeralds
	* Find or Craft a [Barrel](https://i.imgur.com/Mbx8xyo.webp) → Turn a Villager into a Fisherman → Trade Emeralds 3:1 Bucket of Cod
* Craft the remaining [Hay Bales into Wheat](https://i.imgur.com/X89zMQi.webp) → Craft [Bread](https://i.imgur.com/zq8lZ3M.webp) → Pickup the Crafting Table
* Leave the Village → Search for a Lava Lake or Ruined Portal → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* [Minimum Blocks Required](https://i.imgur.com/jSspUON.webp) | [Minimum Space Required](https://i.imgur.com/MvQjKXN.webp)
		* *for minimum space, the bottom 2 spaces aren't required if doing [Cave Portal](https://youtu.be/6Lw2Mng_q4U) | [1-Deep](https://youtu.be/IHnBUAgQwsc)*
		
### **Advanced** | [Pirate](https://youtu.be/EJ4G8QbhrGM)  
*Spawn near an Ocean with a Shipwreck nearby, with 7+ Iron inside (ideally 11+)*
* Gather 3 Logs → Craft 12 [Planks](https://i.imgur.com/kkWqvQM.webp) → Craft a [Crafting Table and 8 Sticks](https://i.imgur.com/3Is7R0F.webp)
* Place the Crafting Table near a Tree → Craft a [Wooden Axe](https://i.imgur.com/qdy0r1s.webp) → Chop 4+ Logs →
	* Craft [Doors, a Boat, and some Bowls](https://i.imgur.com/D7S3XDW.webp) → Pickup the Crafting Table
* Place the Boat in the Ocean → Search for a Shipwreck → Collect the Boat and Dive towards the Shipwreck
* Enter the Top Side at the Back of the Boat → Loot the Chest (Iron / Gold)
	* if < 7 Iron: Loot the Bottom Side Chest at the Back of the Boat → Collect the Buried Treasure Map
		* *you can use the opened Door in the Bottom Cabin to refresh your Breath Meter*
		* *locate the Buried Treasure, if the Loot is bad or it takes too long to find it → Reset*
* Swim to the nearest Gravel → Place the Crafting Table on the Ocean Floor → Place a Door on top of the Table →
	* Craft an [Iron Pickaxe](https://i.imgur.com/lDMvU7r.webp), a [Bucket](https://i.imgur.com/eA21HpJ.webp), a [Shovel](https://i.imgur.com/mEOj9eM.webp) 
		* if 8+ Iron: Iron Shovel, otherwise Wood/Stone Shovel
	* if 11+ iron: Craft an [Iron Axe](https://i.imgur.com/nhL9TfF.webp)
		* *if you don't get an Iron Axe, try to Gather 3 Cobblestone [while teleporting to the Nether](https://youtu.be/So076O4FrU0)*
	* if extra Iron Ingots, Craft [Iron Armor](https://i.imgur.com/USYD3CZ.webp) (can also save 1 to Craft a [Shield](https://i.imgur.com/nyxJaf0.webp), if Fortress before Bastion)
	* Dig up Gravel until you find some Flint → Craft a [Flint and Steel](https://i.imgur.com/XzZEIrF.webp) → Pickup the Crafting Table (and Door)
* Resurface → Place the Boat → Search for an Ocean Ravine
* Create a Ravine Nether Portal *([Spreadsheet](https://docs.google.com/spreadsheets/d/1VU6IZpyhr-3tMXC5GG4ryuqrbmQkvCKE_1nJm2eym4c/edit#gid=1186267001))* → Enter the Nether
	* [Standard](https://youtu.be/yGyMWYhHYoQ?t=85) | [1-Deep](https://youtu.be/yGyMWYhHYoQ?t=329) 
		* *Cobblestone Skip is faster, and not really any harder, so optionally: Skip learning the Standard Method*
	* [Cobblestone Skip](https://youtu.be/H2fHDidyfJo?t=62) - [Safe](https://youtu.be/x0SVexwfKZY) | [1-Deep](https://youtu.be/Q5kh9EYvoqs)
	* [2-Wide, Doors](https://youtu.be/5JXu6lQehQ0) - [Safe](https://youtu.be/CMl2xzC7jb0)

<br/>

* You wont have any Beds, so make sure you get enough String from Piglin Trades: [6 Beds = 72 String (+18 Planks)](https://i.imgur.com/PFGJa4f.webp)
	* *you can also Craft [Iron Nuggets 18:2 Iron Ingots](https://i.imgur.com/jrxLEur.webp) → Craft [Shears](https://i.imgur.com/T8iU2V6.webp)*
		* *Shear Sheep in the Overworld or Collect Cobwebs in a Stronghold Library*
* You wont have much Food *(if any)*:
	* Obtain Food
		* **Nether**: Craft [Mushroom Stews](https://i.imgur.com/5fLy4j5.webp) or Kill Burning Hoglins to get Pre-Cooked Meat
			* *if you Looted Carrots from the Shipwreck, you can Craft [Golden Carrots](https://i.imgur.com/U5GaNsx.webp)*
		* **Overworld**: Kill Burning Animals to get Pre-Cooked Meat
	* Suicide to Reset Hitpoints / Hunger
		* **Nether**: Craft a [Respawn Anchor](https://i.imgur.com/n7sZDd9.webp) → Charge it with a Glowstone Block → Set Spawn → Suicide
		* **Overworld**: Craft a [Bed](https://i.imgur.com/oioKEXE.webp) → Place the Bed → Set Spawn → Suicide
	* Suicide Methods: *make sure to dig down 2 Blocks and Suicide in a hole so your Items don't fly everywhere*
		* [**Fire**](https://youtu.be/itqFlGfKvdk?t=460): Use either a Flint and Steel or Lava to set yourself on Fire
			* *douse the Fire before you die, so you don't accidently destroy your Items*
		* **Ender Pearl**: Throw Ender Pearls [at the ground](https://youtu.be/IH47hXfRFl0), dealing 2.5 Hearts of Damage on impact
		* **Fall Damage**: 1/2 Heart per Block above 3 Blocks
			* *4 Blocks = 1/2 Heart | 7 Blocks = 2 Hearts | 15 Blocks = 6 Hearts, etc*
			* *While in the Stronghold, you can climb up the Starter Staircase to easily get some Height*

### **Advanced+** | Pirate → Ocean Monument  
**Ocean Monument Guides:** [T_Wagz](https://youtu.be/0dyHYkg_xIU) | [Silver](https://youtu.be/14FGC1eUHug) - [Part 2](https://youtu.be/-b7nQyXZkfw)   
*[Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate) Strats, but you also Gather the guaranteed 8 Gold Blocks from an Ocean Monument*  
*doing this will sometimes allow you to completely skip the need to go to a Bastion while in the Nether*  

* Pirate Start → Shipwreck (Craft a [Shield](https://i.imgur.com/nyxJaf0.webp), since you wont have Fire Resistance for the Fortress) → Ocean Monument
	* As soon as you see an Ocean Monument, turn your Render Distance to 2 (RD2)
		* *this will usually result in the Elder Guardians not spawning, allowing you to avoid Mining Fatigue*
	* if you get Mining Fatigue
		* Drink a Milk Bucket (use an Empty Bucket on a cow, mooshroom, or goat)
		* Set your Spawn at a Bed → Suicide *(see the Suicide Methods in the Pirate section above)*
			* *optionally: if you're close to the World Spawn, Suicide without setting your Spawn*
	* Mine the 8 Gold Blocks from the Monument → Leave the Monument as fast as possible
	* Once you're a reasonable Distance away from the Monument, set your Render Distance back to normal
* Locate an Ocean Ravine → Create a Ravine Nether Portal → Enter the Nether
	* The Bed and Food limitations from the Pirate Strats still apply here  

<br/>

* When you find a Fortress in the Nether, look around for nearby Piglins to Trade with
	* Trap 2 Piglins in a Boat → Throw them your Gold Ingots → Proceed into the Fortress
	* Kill Blazes for Blaze Rods → Return to the Piglins to Collect your Loot
		* *if you didn't get enough Loot to leave, either Find a Bastion or finish Trading using Classic Strats*

### **Expert** | [Hypermodern](https://youtu.be/gAHMJfsrHe4)  
*Combination of the most optimal Strats, Resets are frequent, so having a very high Reset Efficiency is recommended*
* [Mapless Treasure](https://youtu.be/_dyD8ZwagDg), *if available* → [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate) → [Ravine Nether Entry](https://youtu.be/H2fHDidyfJo?t=62) → 
	* *if you spot a Shipwreck from your spawn location, [prioritize that](https://youtu.be/CEG8oXyz9zc?t=257) over Mapless Treasure*
* [Microlensing](https://github.com/Metacor/Minecraft-Speedrun-Guide#microlensing-aka-e-ray) → [Bastion](https://github.com/Metacor/Minecraft-Speedrun-Guide#bastions) → [Pie-Ray](https://github.com/Metacor/Minecraft-Speedrun-Guide#pie-ray-aka-piedar) → [Fortress](https://github.com/Metacor/Minecraft-Speedrun-Guide#fortress) → [Nether Travel](https://github.com/Metacor/Minecraft-Speedrun-Guide#travel) →
* [Triangulation](https://github.com/Metacor/Minecraft-Speedrun-Guide#triangulation) → [Stronghold Navigation](https://github.com/Metacor/Minecraft-Speedrun-Guide#stronghold-navigation) → End Entry →
	* [Half-Bow](https://youtu.be/whwjNbIni58) | North / South Ground → [One-Cycle Dragon](https://youtu.be/aGMLHXnD6Bc) (~[4 Bed](https://youtu.be/R-9PGkSJU7g))  


***Optionally***  
*if Village with nearby Lava Lake *(very close)* | Ruined Portal *(completable)* | Blacksmith *(with 10+ Obsidian)**  
* [Village](https://github.com/Metacor/Minecraft-Speedrun-Guide#standard--village) Start
	* if 7+ Iron (Blacksmith + Golem): Craft an [Iron Pickaxe](https://i.imgur.com/lDMvU7r.webp) + [Bucket](https://i.imgur.com/eA21HpJ.webp) + [Flint and Steel](https://i.imgur.com/XzZEIrF.webp)
		* *optionally, if 4+ Iron (Blacksmith): Don't Kill the Golem → Skip Crafting an Iron Pickaxe → get lucky*
	* if 4-6 Iron: Skip Crafting an Iron Pickaxe, hopefully get lucky with Iron from Bastion Chests
	* if 3 Iron: Reset *(or Flintless Portal, if you REALLY want to force the seed)*

<br/>

## The Nether
*Find a Bastion, Trade Gold to Piglins for Obsidian and Ender Pearls → Find a Fortress, Kill Blazes for Blaze Rods*

### **Microlensing** *(a.k.a. E-Ray)*  
[k4yfour](https://youtu.be/jvTfMLPnMSw) - [Part 2](https://youtu.be/Ou58P7e-ZY0) | [Nuskapuska's Slide](https://i.imgur.com/98heFGq.webp)
* When you enter The Nether, open your F3 Menu *(if not already opened)*, and look at the **Right** [E: Value](https://i.imgur.com/w6WZlqf.webp)
	* *for example, in the image linked above, E: 32/**122**, you should be looking at 122*
	* *ideally, open your F3 Menu before entering your Nether Portal in the Overworld*
* if you notice the E: Value quickly raises, you likely just loaded a Bastion into your Render Distance
* if the sum of the M: & C: Values is ~30 higher than the E: Value, there is a Bastion within your Render Distance
* To find the Bastion Direction, change your Fov to 30 then slowly turn 360°, and look at the **Left** [E: Value](https://i.imgur.com/w6WZlqf.webp)
	* *as opposed to the previous example, in the image linked above, E: **32**/122, you should be looking at 32 this time*
	* *High density Biomes can sometimes give false positives for Bastions, use (E + 30 ≈ M + C), for a better idea*

### **Bastions**  
[pncakespoon's Route Spreadsheet](https://docs.google.com/spreadsheets/d/1qLgp5uhMOKuerNZaec1dpoECpJI0-6YhztMqa_wZ8W0/edit#gid=1811348189) | [Bastion Resources](https://docs.google.com/document/d/1yuruZF575xvwOCB5t6ftfRY9OEtLDRQsWFJRD6YetU0/edit) | [Zolstice's Beginner Screenshot Guide](https://www.reddit.com/r/MinecraftSpeedrun/Collection/a6121708-188c-43b9-8267-de61620456f1/)  
*ideally, locate and finish the Bastion before the Fortress, for the chance to get Fire Resistance Potions*  

**Identify the Bastion Type, and run the Route accordingly**  

* **Bridge**: [Structure Video](https://youtu.be/2pzMpX1RJGI?t=128) | [Screenshots](https://imgur.com/a/OHwW0tb) | [Strat Flowchart](https://i.imgur.com/S7Uqb6C.webp)  
*if buried, Craft a Gold Pickaxe at the Chalice*  
	* if Triple, *(Right Shoulder)*: [Dowsky](https://youtu.be/RAgYDi23Dww)
	* if Triple, *(Left Shoulder)*: [Reignex/Gus](https://youtu.be/aKxDbLTZ2f0) | [Buried](https://www.twitch.tv/videos/1056189431)
	* if Double Single: [Ela's Hole](https://youtu.be/3SHj_nm8mC0)
	* if Top Entry: [Lodestone Manhunt](https://youtu.be/QdUehnmxkjo?t=665)
* **Treasure**: [Structure Video](https://youtu.be/A9GGUWwNcrY?t=132) | [Screenshots](https://imgur.com/gallery/U4FnQC5) | [Bottom Placements](https://i.imgur.com/bDQjaBL.webp)  
*highly recommended to Craft a Gold Pickaxe with the [Gold Blocks on the bridge](https://youtu.be/9NNvyBx03iY)*
	* [Ninjabrain](https://youtu.be/0YvGkSOJVmU)
* **Housing**: [Structure Video](https://youtu.be/BoNr-pbEITM?t=132) | [Screenshots](https://imgur.com/gallery/wyjWcli) | [Correct Direction](https://youtu.be/BoNr-pbEITM?t=853)
	* if Bot: [Manhunt](https://streamable.com/tdzb21)
	* if Top: [Top Down Manhunt](https://youtu.be/55sRL0xsWe8)
		* Alternative: [Kuee Top Down](https://youtu.be/H2xy6q5Wp4Q)
			* *the Chest Method can also be used for the normal Top Down strat*
				* *Pick Block the Chest to easily get it into your Hotbar*
* **Stables**: [Structure Video](https://youtu.be/TioQsF5ygOg?t=149) | [Screenshots](https://imgur.com/gallery/u91rHC4) | [Gap Identification](https://www.youtube.com/watch?v=AczOTF5QpZ4&t=164s)
	* if Triple: [Triple Chest Stables](https://youtu.be/AJxgbRma25Q)
	* if no Triple, w/ Good Gap: [Good Gap Stables](https://youtu.be/ukyIkZMnw-w?t=141)
	* if no Triple, w/ Double Bad Gap: [Better Luck Next Time](https://i.imgur.com/YxRxdhI.webp)

**Required Items**  
* **Obsidian**
	* **10 Required** to [Blind Travel](https://github.com/Metacor/Minecraft-Speedrun-Guide#travel) out of the Nether
	* *20 for [Educated/Calculated Travel](https://github.com/Metacor/Minecraft-Speedrun-Guide#travel)*
	* *1-3 for the One-Cycle platform in the End (Crying Obsidian will also work)*
* **Ender Pearls**
	* **12 Required** to fill the 12 [End Portal Frames](https://minecraft.fandom.com/wiki/End_Portal_Frame) in the Stronghold
		* *the End Portal Frames can sometimes [already be filled](https://i.imgur.com/p1Cp5hd.webp), requiring fewer Eye of Enders*
	* *16+ to allow for more uses outside of just filling the End Portal Frames*
		* *2+ in case your Eye of Enders break while locating the Stronghold*
		* *2+ to quickly move around in the End, resulting in a less stressful Ender Dragon setup*
		* *and a few more to travel large Distances in the Nether/Overworld if needed*
* **String**
	* **0-72 Required** to Craft Beds *([4:1 Wool → 3:1 Bed](https://i.imgur.com/PFGJa4f.webp))*, in order to One-Cycle the Ender Dragon
	* *if you Collect enough Beds from Villages (4 minimum | 6+ for safety), you wont need any String*
		* *4 Beds = 48 String (48s → 12w → 4b) | 6 Beds = 72 String (72s → 18w → 6b)*

**Optional Items**  
* **Potion of Fire Resistance**: Makes you immune to Lava / Fire Damage 
	* *makes you immune to the Blaze's fireballs, but not their melee attacks*
* *Cross***Bow + Arrows**: Allows you to [Half-Bow](https://youtu.be/whwjNbIni58) while in the Ender Dragon fight
* **Fire Charge**: Can be used to light Nether Portals *(useful if you entered with a Flintless Portal)*
	* *alternatively: Gather Flint from Gravel → Craft [Iron Nuggets 18:2 Iron Ingots](https://i.imgur.com/jrxLEur.webp) → Craft a [Flint and Steel](https://i.imgur.com/XzZEIrF.webp)*

### **Pie-Ray** *(a.k.a. Piedar)*  
[k4yfour](https://youtu.be/Ou58P7e-ZY0?t=109) | [PandapigGamer](https://youtu.be/Aq9qfHNEOHM)  
*attempt to locate a Fortress, using Mob Spawners in the Block Entities section of the Shift+F3 Pie Chart Menu*  
*Blaze Spawners aren't the only Mob Spawner in the Nether, sometimes Treasure Bastions will cause a false positive*  
*this method can also be used in the Overworld to find Villages (using [Bells](https://minecraft.fandom.com/wiki/Bell) and [Workstations](https://minecraft.fandom.com/wiki/Villager#Professions) instead of Mob Spawners)*  

* Open the F3 Pie Chart by pressing Shift + F3
* Navigate to the correct Pie Chart Menu: *Tick → Level → Entites → Block Entites*
	* *you can use the numbers on your keyboard to select the corresponding option*
* Increase your Render Distance *[F3 + F]* until you see a Mob Spawner show up in the Pie Chart
	* *if there is already a Mob Spawner showing: First change to RD2 → Close/Reopen Shift+F3*
* Decrease RD by 4 *[F3 + Shift + F]* → Close/Reopen Shift+F3 → Increase RD by 3 *[F3 + F]*
* Enable Chunk Borders *[F3 + G]* → Cross the Chunk Border in each direction until the Mob Spawner reappears
	* *if the Mob Spawner doesn't reappear, it's likely diagonal from your location, check the corners*
* The direction the Mob Spawner reappears is the direction in which it's located
* Follow that direction until you find the Fortress *(or Treasure Bastion, if you're unlucky)*
	* *if it's a Treasure Bastion, either [break the Magma Spawner](https://youtu.be/Ymt8NCIyYt0?t=41) and try again, or reset*

### **Fortress**
[Pooply](https://youtu.be/swSbv4AImzI) | [Haroon Shah](https://youtu.be/iaUF0oaegns?t=3624) | [Couriway](https://youtu.be/LJ1PbhPAVAI?t=263)

* Fortresses are split into 2 sections, the Bad *(inside)* section and the Good *(outside)* section
	* *the Bad section of the Fortress will have a Netherbrick roof above it*
	* *the Good section of the Fortress with have either no roof, or a Netherrack/Soul Sand roof*
		* *Blaze Spawners only generate in the Good section, try to get there as fast as possible*
* [Inside Navigation](https://youtu.be/swSbv4AImzI?t=87)
	* *if there is a staircase with Nether Wart at the bottom: Go **down** the stairs*
	* *if there is a staircase without Nether Wart at the bottom: Go **up** the stairs*
	* *if there is a balcony room: Go in the **opposite** direction of it*
	* *the Lava pool room will always connect the Good and Bad sections*
		* *if viewed from above, this room will be the building [without roof access](https://youtu.be/LJ1PbhPAVAI?t=269)*
* Search the Good section of the Fortress until you locate a Blaze Spawner
* Activate a Potion of Fire Resistance if you have any *(this is the main reason we try to do Bastions first)*
	* *if you don't have Fire res, make sure to Craft a [Shield](https://i.imgur.com/nyxJaf0.webp) and put it in your offhand*
	* *if you don't have Fire res or a Shield, create a [safety platform](https://youtu.be/jXCyUOMP4wQ) to fight the Blazes*
* After you defeat the first wave of Blazes, begin to clear out the surrounding blocks, increasing the spawn rates
	* [Standard](https://youtu.be/mDb8VucFV9s?t=276): *manually use your Pickaxe to Mine out the Blocks*
	* [Blaze Bed](https://youtu.be/3TD4jkuT8QA): *use the explosion from clicking a Bed in the Nether to quickly clear the Blocks for you*	
		* [Methods](https://youtu.be/1spSd0Ussy0): [Open](https://youtu.be/3TD4jkuT8QA?t=165) - [2](https://youtu.be/3TD4jkuT8QA?t=379) | [Enclosed](https://youtu.be/3TD4jkuT8QA?t=460) - [2](https://youtu.be/3TD4jkuT8QA?t=268) | [TnT](https://youtu.be/X3kHn0PaZW0)
			* *when Blaze Bedding quickly put out the Fires, Blazes only spawn at Light Levels 11 or lower*
* Kill Blazes until you Collect 7-8 Blaze Rods → Craft [Blaze Powder](https://i.imgur.com/Bhr4808.webp) → Craft [Eye of Ender](https://i.imgur.com/0FjuMuE.webp)
	* *Craft ~10 Eyes for now, the remaining can be Crafted after you confirm the completed End Portal Frame count*
		* *doing this will make sure you don't waste any Ender Pearls that could've otherwise been used in the End*
* Leave the Fortress and navigate to the nearest [Blind location](https://imgur.com/gallery/i3fIanf)
	* *if 20 Obsidian: create a Nether Portal at the Fortress → use one of the Travel Methods listed below*

### **Travel**  
*[Build a Nether Portal](https://youtu.be/ZE5VEYWC_9s) at specific locations in the Nether to teleport close to the Stronghold*  
* **[Blind](https://youtu.be/0N8Wj8hOVKM)**
	* Build your Nether Portal at the closest of any of [these Coordinates](https://imgur.com/gallery/i3fIanf)
* **[Educated](https://youtu.be/0N8Wj8hOVKM)**
	* Requires you to have 20+ Obsidian, and for you to build a Nether Portal to reach the Overworld
		* *if your final Nether Structure is very close to your first Nether Portal, you can use that instead*
	* Once in the Overworld, Throw an Eye of Ender → Record the Angle → Return to the Nether
	* Follow that Angle in the Nether, and build a Nether Portal at the closest [Blind location](https://imgur.com/gallery/i3fIanf)
* **Calculated**
	* Similarly to Educated Travel, requires the use of 20+ Obsidian and a random Nether Portal
	* For Calculated, instead of throwing 1 Eye of Ender, fully use Triangulation *(read the section below)*
	* Build your Nether Portal *(in the Nether)*, at the general location of the Stronghold
		* *using both the Direction of the Eye of Ender *(like Educated)*, but also the rough Distance/8*
* **[Axis Calculated](https://www.youtube.com/watch?v=0LDj48fsRT8)** | [How-to Doc](https://docs.google.com/document/d/1oora0jzLf6IgydbGciE8-vL8JXsejqvAKm4N9jAfWVg/edit)
	* A more precise version of Calculated Travel, if you're interested, watch the Video linked above
* **[Divine](https://youtu.be/SXem01c44-I)**
	* if there is a Fossil in the 0,x,0 Chunk, build your Nether Portal at the [corresponding Coordinates](https://cdn.discordapp.com/attachments/405839885509984256/891800745760948224/finished3mdpi.jpg)

<br/>

## The Overworld, Part 2
*Find the Location of a Stronghold → Enter the Stronghold, and Navigate to the Portal Room → Enter The End*

### **Triangulation**  
[BoomerPlayz](https://youtu.be/8c29j0We2VQ) | [Distance Chart](https://i.imgur.com/6rvw5Bb.webp)  
*use the differing Angles from throwing multiple Eyes of Ender to find the location of the closest Stronghold*  
*even if you're not doing [Axis Calculated Travel](https://youtu.be/0LDj48fsRT8), you can still use Ninjabrain's Triangulation Method if you prefer*  

* While in the Overworld, throw an Eye of Ender → View the Eye in the center of your screen → Record the Angle°
	* *changing your FoV to 30 while looking at the Eye will make the Angle more precise*
	* *if you have trouble following the Eye, try throwing it while either [looking down](https://youtu.be/8c29j0We2VQ?t=200), or using [F5](https://youtu.be/0LDj48fsRT8?t=24)*
* Turn 90° *(either Direction)* → Travel 17.5 Blocks *(~4 Sprint Jumps)* → Throw another Eye → Record the Angle
* Calculate the difference in the Angles between your first and second Eyes
	* *for example: 56.3° *(first eye)*, and 57.2° *(second eye)* = 0.9° difference*
* The Distance will be *(1000/x°)* Blocks away, where x is the difference calculated
	* *alternatively, use this [chart](https://i.imgur.com/6rvw5Bb.webp), or go to the [Speedrun Cheatsheet](https://github.com/Metacor/Minecraft-Speedrun-Guide#speedrun-cheatsheet) section of this Guide*
	* *in the case above, a 0.9° difference will be ~1111 Blocks away from you*
		* *this is, of course, assuming you recorded the correct Angles, and travelled 17.5 Blocks*
* Follow the Angle for your Eye throws until you travel the rough Distance needed to reach the Stronghold
* Use the [8, 8 Method](https://youtu.be/w8Lqa2B01lo) to locate the exact Chunk that your Stronghold's Starter Staircase is in
	* *the Eye of Ender **always** points to the direct middle of the Chunk *(8/x/8)* where the Starter Staircase is located*
	* *The Starter Staircase will **always** be located @ 4/x/4 in the Chunk that 8,8 points to*
		* *digging down in any block between 3,3 and 5,5 will work for this, 4,4 is just the center*
		* *4/x/4 will be 4 Blocks diagonally from the North-West corner*
			* *using the [F3 Axis Cursor](https://youtu.be/w8Lqa2B01lo?t=187) is an easy way to quickly find North-West*
* Dig into the Starter Staircase, and begin your Stronghold Navigation

### **Stronghold Navigation**
*read the [Overworld, Part 2 - Tips & Tricks](https://github.com/Metacor/Minecraft-Speedrun-Guide#the-overworld-part-2-1) section for more Navigation Techniques*  
* Start at the Starter Staircase and Navigate through the Stronghold until you reach the Portal Room
	* *if you entered from somewhere else, go through [backwards Doors](https://i.imgur.com/ZZP3PuP.webp) until you find the Starter Staircase*
	* *all staircases lead **up** to the Starter Staircase, so if you find one always go up*
* Enter the Portal Room → Run up the Stairs → Place a Block in the Lava → Stand on it → Complete the End Portal
	* *when you place the final Eye of Ender into the End Portal Frames, you will be instantly teleported to the End*
			
<br/>

## The End  
[k4yfour](https://youtu.be/-Ta_1R1aXvA) | [Hashten](https://youtu.be/aGMLHXnD6Bc) | [BoomerPlayz](https://youtu.be/1daiTbj1OiE) - [Part 2](https://youtu.be/uBp8uVbW1us)  
*Kill the Ender Dragon, Finishing the Game*  

* When you spawn in The End, get to the Exit Portal as soon as possible
	* *if you spawn above ground, Ender Pearl directly to the Exit Portal*
	* *if you spawn underground, Mine up along the West wall, ideally in a corner*
		* *[Place a Block → Jump onto it → Mine up 5 Blocks → Place Blocks below you → Repeat](https://youtu.be/b96APrsfm6s?t=750)*
* Setup your preferred Bed Platform: [Obsidian]() | [Full Block]() | [Slab]()
	* *run away in your preferred Perch Direction (N/S or E/W)*
		* *your Bed Platform position might need to change, based on your chosen Perch Direction*
* Execute your preferred End Island Method:
	* if you have a *cross*Bow and Arrows → [Half-Bow]()
	* if you have 2+ Pearls, and you don't plan on doing Half-Bow:
		* [Pearl up to the highest Obsidian Tower](https://youtu.be/-Ta_1R1aXvA?t=116) in the Direction you chose, [build up until you reach y = 122](https://youtu.be/-Ta_1R1aXvA?t=128)
	* if you don't have 2+ Pearls, and you also don't plan on doing Half-Bow:
		* [Run as far away from the Exit Portal as possible](https://youtu.be/-Ta_1R1aXvA?t=519), while still being able to see if the Dragon is Perching
* Turn on Entity Hitboxes *(F3 + B)* to help with One-Cycling the Dragon
	* *hitboxes will also make it more obvious when the Dragon's head "snaps" to the center before Perching*
* When the Dragon begins to Perch, either Ender Pearl or run to the Exit Portal → One-Cycle the Dragon with Beds
* Once the Dragon is Defeated, stand inside of the Exit Portal - **Timing ends on the screen transition**
		
<br/>

# Tips & Tricks  
[Cuffep](https://youtu.be/CdoYoYrOyjU) - [Part 2](https://youtu.be/IhrK0AuMkBg) | [Couriway](https://youtu.be/fIeVOFqGwOM) | [Penney](https://youtu.be/TvvApbI6fis)  
*this section is roughly listed in the order each situation would appear in a run*  

### The Overworld
* [Shipwrecks](https://i.imgur.com/ws384ow.webp)
	* Front Side Chest: Food 
		* *if the Shipwreck is right-side up, you can loot this chest [from above](https://youtu.be/EUiU5MZt_7g?t=72)*
	* Back Side: *the back side is wider, and has a window on all 3 outer sides*
		* Top Chest: Iron Ingots, Gold Ingots
			* *if the Shipwreck is right-side up, you can Loot this chest [from above](https://youtu.be/dX83N4q4YWU?t=57)*
		* Bot Chest: Buried Treasure Maps
			* *Buried Treasure is always located @ 9/x/9 in the Chunk where the X is located*
			* *placing the Buried Treasure Maps in your offhand will make navigating easier*
* Buried Treasure can also be found in [Ocean Ruins](https://minecraft.fandom.com/wiki/Ocean_Ruins)
	* *[all but 2](https://youtu.be/4-6OUGu6uqY?t=427) configurations can have chests in them with Buried Treasure Maps (~40% of the time)*
	* *however, the Ocean Ruins usually form with blocks missing, and can sometimes spawn without a Chest*
* In Ocean Monuments, the Guardian's Lazer attack will Kill you in: Hits Required (Damage Taken/20)
	* Easy = 5 (4) **|** Normal = 4 (6) **|** Hard = 3 (9)
		* *with Healing, Easy will almost always take 6 hits, and Normal will sometimes take 5*
	* *their lazer attack requires 2 seconds of uninterrupted line of sight, simply break LoS to take 0 Damage*
		* *proper Door placement will usually negate all potential Damage when searching for the Gold Blocks*
* Desert Temples - *explode a single TnT to Collect all of the Chest Loot and any surrounding Blocks*
	* [Top TnT](https://youtu.be/gS6LxaNibWM?t=76) | [Bot TnT](https://youtu.be/CdoYoYrOyjU?t=5)
* Mining [Stone takes slightly less time than Cobblestone](https://i.imgur.com/LuyiYEa.webp), (typically found as part of Plains Village houses)
	* Wooden Pickaxe: Stone takes **1.15 Seconds** | Cobblestone takes **1.5 Seconds**
	* Stone Pickaxe: Stone takes **0.6 Seconds** | Cobblestone takes **0.75 Seconds**
* if the Iron Golem is already in a good spot, you can build up next to it before you attack
* if you need to climb something, but don't have many Blocks, you can use a [Bucket of Water](https://youtu.be/PkrCPuS6IZ8?t=380)
	* *this can also be used in the End, if you run out of Blocks while building up out of a buried spawn*
		* *although if you have Blocks, [just building up](https://youtu.be/b96APrsfm6s?t=749) is faster than using a Bucket of Water*
	* *doing this wouldn't work in the Nether, as Buckets of Water don't work in the Nether*
* if you have a limited amount of Gravel, and you need to Dig more to Collect Flint, put the Gravel in your offhand
	* *by doing this, you can Dig with a Shovel and place Gravel at the same time*
* You don't need to hit Chickens after igniting them, [the Fire Damage alone will kill it](https://youtu.be/FV2u8soBkeA?t=702)
* Lava Lakes tend to spawn underneath Water Lakes
	* *if you're unable to find a Lava Lake on the surface, try digging near small surface Water Lakes*
* [Lava Dousing](https://youtu.be/SzNbVxDj-do)
	* *more advanced and precise way to find subsurface Lava Lakes*
* When Searching for an Ocean Ravine, turn on Entity Hitboxes (F3 + B), and look out for Floating Kelp
	* *if you see floating Kelp in a Deep Ocean, there is [likely a Ravine below it](https://youtu.be/yGyMWYhHYoQ?t=471)*
* To avoid Glitchy Buckets while making Nether Portals, [don't move while grabbing Lava](https://youtu.be/EjwStTX4U3A)
* Since Buckets of Water don't work in the Nether, when you finish your Nether Portal, fill the Bucket with Lava
* if you plan on Microlensing your Bastion in the Nether, turn on the F3 Menu before you teleport to the Nether

### The Nether
* Falling while in a Boat will [negate all Fall Damage](https://youtu.be/REas9cmjlic?t=686)
* Killing Burning Hoglins is an easy way to get food in the Nether [Lava Bucket](https://youtu.be/wjbQyyHkr9M?t=110) | [Flint and Steel](https://youtu.be/REas9cmjlic?t=694)
* if you need more Blocks while in the Nether, Mine some Netherrack
	* Netherrack isn't flammable, and it's very fast to Mine (0.1s with an Iron Pickaxe)
* if there is a far away Ghast attacking you, quickly lower your Render Distance to 2
	* [This will usually despawn the Ghast](https://youtu.be/tWVrxt0G6r0?t=696)
	* *You can turn your Render Distance back up after it disappears*
	* *if the Ghast is close, just reflect its attack back at it*
* When running across Soul Sand, either [jump with Blocks](https://youtu.be/LdY59umJcuA?t=460), or [run along the edges](https://youtu.be/7mRh3TWajn0)
	* *this will also work on other movement impairing Blocks, such as Magma and Ice*
* if you find Nether Gold Ore while travelling to a Bastion, consider Mining it and making [Gold Boots](https://i.imgur.com/QrAbJ35.webp)
	* *Boots only take 4 Gold Ingots (36 Gold Nuggets), ~9 Ore on average*
	* *Wearing any Gold Armor will make it so Piglins don't auto-aggro you*
* Bastion Microlensing example *(using m+c=e)*
	* *for [M + C = 113, while E = 122, @16 RD](https://i.imgur.com/w6WZlqf.webp), if there is a Bastion, it's likely not fully rendered in*
		* *Starting at (-77, 59, 58), the closest Bastion is at [(-128, ~, -288)](https://i.imgur.com/EVScDGC.webp), being ~350 Blocks away*
		* *16 Render Distance renders ~256 Blocks in cardinal Directions, ~362 Diagonally (256√2)*
* Bastions cannot spawn inside of a Basalt Delta Biome
* Only 1 Structure *(Bastions and Fortresses)*, can spawn per *(432, 432)* MegaChunk, for example:
	* *if a Bastion spawns at (+x, +z), this will be the only Structure in that MegaChunk*
	* *in order to find a new Structure, you will need to go to a new MegaChunk*
	* *the remaining 3 inner Quadrants being: (+x,-z), (-x,-z), (-x,+z) | where x & z are < 432 (neg or pos)*
		* *Directions can also be called: (pos, pos), (pos, neg), (neg, neg), (neg, pos)*
	* *Structures in MegaChunks beyond the inner 4 Quadrants are known as Extra-Regional Structures*
* All Bastion types (besides Treasure), can spawn a Triple Chest top section - to easily tell them apart:
	* if there are [2 Blocks](https://i.imgur.com/SzHSK3A.webp) between the Double/Single Chest, then it's Stables
	* if there are [3 Blocks](https://i.imgur.com/wosezlF.webp), then it can be either Housing or Bridge
		* *Housing and Bridge are very different, so it shouldn't be too hard to Identify the correct one*
* if you want to Loot Chests in Bastions without worrying about Piglins, [dig down and hide your head](https://youtu.be/dAQGH8lPWAM?t=240)
	* *this can also be done [from above](https://youtu.be/55sRL0xsWe8) a Triple Chest Structure*
* Piglins have weird pathfinding around Lava
	* *when building bridges across Lava - while routing bottom side Manhunt Housing for example*
		* *build 1 block above Lava (instead of inside of it)*
			* *piglins seem to refuse to jump up/down a block at the edges of lava*
			* *if forced to build inside, use stairs at the ends of your bridge*
		* *build 3 Blocks wide, to make sure Piglins follow*
		* *piglins can't run across corners, so make sure there is a direct path over the Lava*
* Splash Potions have a [longer Duration if they directly impact an Entity](https://minecraft.fandom.com/wiki/Splash_Potion#Using)
	* *when using a Splash Potion of Fire Resistance, throw it directly upwards and let it fall on you*
		* *if you throw it directly at your feet, you lose ~20 seconds of Effect Duration*
	* *if a [Splash Potion is thrown while Falling](https://youtu.be/NVb0EMzorw4), you can recieve nearly the max Duration*
* While trying to Pie-Ray, if you accidentally press the wrong button, press '0' to go back a page  
* When approaching a Fortress, you can lower your Render Distance to 5 (5RD)
	* *this decreases the spawning area, while not changing the Mob Limit, effectively increasing spawn rates*
		* *this effective increase affects all enemies that spawn in that Biome, not just Blazes*
		* *Mob Spawners are not affected by this increase, so if you plan to camp a Spawner, 5RD wont help*
	* *it's a lot easier to deal with the increased density, if the Fortress isn't free floating above Lava*
	* *[Mobs spawn more often in Soul Sand Valleys](https://youtu.be/SDLFTWFpJOI?t=67), using 5RD while in one is pretty risky if you're low on food*
* if your Axe breaks while fighting Blazes, [Shovels do slightly more Damage than Pickaxes](https://i.imgur.com/gpxqtCg.webp) of the same Type
	* *while Pickaxes above Gold have very marginally more DPS, they also require an extra hit below Diamond*
	* *assuming Crits @ 100% Power, hits needed to Kill a Blaze:*
		* *Shovel: Wood/Gold = 6, Stone = 4, Iron = 3, Diamond = 3*
		* *Pickaxe: Wood/Gold = 7, Stone = 5, Iron = 4, Diamond = 3*
* Blazes will Target a Player if they have Line of Sight, and are within 48 Blocks
	* *once a Target is acquired, the Blaze will set itself... **ablaze**, for 3 seconds*
	* *at the end of this 3 second period, the Blaze will begin to shoot a Volley of 3 Fireballs*
		* *if the Blaze loses Line of Sight with its Target, the Volley will be paused*
		* *upon regaining Line of Sight, the Volley will be resumed, shooting any remaining Fireballs*
	* *after the final Fireball is shot, the Blaze will be unable to Target for 5 seconds*
	
### The Overworld, Part 2
* The Stronghold will spawn a [minimum of 1280 Blocks](https://minecraft.fandom.com/wiki/Stronghold#Java_Edition) from *(0, 0)*
	* *this Distance is calculated triangularly not linearly, so (a²+b²=c²), not (a+b=c)*
		* *(150x, 150z) would be ~212 Blocks away from (0, 0), not ~300*
	* *if you're just adding x + z, then the Stronghold ≈ 2000 - 2400 (Overworld) | 250 - 300 (Nether)*
* When travelling across Water, it is faster to use a [Dolphin's Boost](https://minecraft.fandom.com/wiki/Dolphin%27s_Grace), than it would be to use a Boat
* if you find an underwater Stronghold, make sure to look around for the Portal Room before blindly entering
* Strongholds are [extremely unlikely](https://youtu.be/_rbWryJVEmw?t=1011) to spawn in Swamps ([supposedly impossible](https://bugs.mojang.com/browse/MC-136288))
* The Portal Room is usually within [5 = 7](https://youtu.be/u42bjqtq5-s) Rooms of the Starter Staircase
* [Hidden Rooms Identification](https://www.youtube.com/watch?v=vztJNmUdyBY)
	* *Hidden Rooms can only occur in "5-way" room types*
	* *if you're facing +x/+z (South/East) from the main entrance, there **CANNOT** be Hidden Rooms*
	* *if you're facing -x/-z (North/West) from the main entrance, there **CAN** be Hidden Rooms*
		* *if you see an indentation in the wall, there will be a hidden room on that side*
		* *for example, if there is an indentation in the top left, the bottom left wall will be a Hidden Room*
			* *assuming you're in a 5-way that faces North or West*
* Libraries lead nowhere, if you enter a Library from the Starter Staircase, turn around
	* if you need more Beds, you can Gather string from Library Cobwebs
		* *when Gathering, use either a Sword or Shears (decreasing the Gather Time from 20s → 0.4s)*
		* *alternatively, you can use a [Bucket of Water](https://youtu.be/D714cio_nv4?t=673)*
* Be sure to pay attention to the Subtitles, look for popping Lava and Silverfish noises

### The End
* You will **always** spawn East of the Island, facing West, towards the Exit Portal
* The Dragon has a [higher chance to Perch the farther away you are from the Exit Portal](https://i.imgur.com/e3JyPex.webp)
* The Dragon will Perch from the opposite side of you, in relation to the Exit Portal
	* *Diagonal Perches are a lot harder to One Cycle, so it's recommended to run away N/S/E/W*
	* *N/S Perch is faster than E/W, however it gives the player less time to react to the Perch*
* The Dragon's Fireball doesn't actually do Damage, the AoE ground Effect left behind is what Damages you
	* *an easy way to avoid the Damage, is to get hit on purpose, then Jump → place a Block below you*
* if you aggro an Enderman, try to trap it in a Boat so you can easily Kill it without taking damage
	* *this can also be used in the Overworld / Nether to Collect Ender Pearls*
* Using Pick Block to select Beds while One-Cycling the Dragon makes inventory management a lot more simple
* if you failed to One-Cycle the Dragon: attack the Dragon's Head Hitbox
	* *don't try to crit, just stand normally and hit with fully charged attacks*
	* *you can deal up to 50 Damage (~6 Stone Axe hits), before the Dragon will fly away*
		* *if you haven't destroyed the End Crystals, failing to defeat the Dragon at this point will result in a Reset*
		
<br/>

# Practice
*Ideally, get comfortable with each of these steps before starting runs*  

## Crafting  
*learn to quickly, and optimally, complete the most common early game Crafting Windows*  

**Notation:**
* *sClick: Shift + Click | lClick: Left Click | rClick: Right Click*
* *item(num): Press that Hotbar Keybind into the Crafting Window*
	* *if item(num), xX: Put the Item into that specific Crafting Window Slot*
* *xX: tL,tM,tR - mL,mM,mR - bL,bM,bR*
	* *first, small letter is top/middle/bottom (row)*
	* *second, Big letter is Left/Middle/Right (column)*  

*the given intructions/screenshots will only be for the most optimal version, even if multiple videos are provided*  
*the Item(num) positions will assume that you have completed the previous Methods as listed*  
	
<br/>

**Crafting Table + Sticks**: *used in practically every run*  
[Screenshot](https://i.imgur.com/3Is7R0F.webp) | [Videos](https://youtu.be/lEdAMNweD7E): **[Half Split (8c)](https://youtu.be/lEdAMNweD7E?t=2)** - [Kuee (8c)](https://youtu.be/lEdAMNweD7E?t=8) - [Split 2 (10c)](https://youtu.be/lEdAMNweD7E?t=13) - [Double Split, Move (10c)](https://youtu.be/lEdAMNweD7E?t=20) - [Double Split, Throw (9c)](https://youtu.be/lEdAMNweD7E?t=28)  
*while Kuee's Method also only takes 8 Clicks, I personally feel that it doesn't flow as nicely as the Half Split Method*  
*this is by far the most common Craft you'll execute when speedrunning, so be sure to pick the one that feels best to you*  
* Gather 3 Logs, turn them into 12 Planks, then Craft a Crafting Table and 8 Sticks
	* Logs(1) → Collect: sClick → Planks(9), bR → Half Split → Drag bR, bL, tL → lClick tR → Collect: sClick x2  
	
<br/>

### **Standard Crafts** - *used in structureless and village overworlds*
**Wooden Pickaxe**:  
[Screenshot](https://i.imgur.com/AgRcfOf.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=37)
* Place the Crafting Table, Craft a Wooden Pickaxe → *Mine 6 Cobblestone*
	* Sticks(8), bM → Half Split → lClick mM → Planks(1), tL → Half Split → Drag tM, tR → Collect: 8
		* *highly recommend to Collect to your Pickaxe Hotbar Keybind, instead of shift + clicking*
			* *i have my hotkey set to 8, rebound to F, just Collect to whatever yours is bound to*

**Stone Tools**: *if Hoe Skip: Mine 4 Cobblestone instead - the same movements can be used*  
[Screenshot](https://i.imgur.com/UDSN7Uc.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=45)
* Craft a Stone Axe, a Stone Hoe, and a Stone Shovel → *Pickup the Crafting Table → Chop 8+ Logs*
	* Sticks(2), bM → Half Split → lClick mM → Stone(3), tM → Half Split → rClick mL → lClick tL → Collect: 7 → 4 → 5
		* *once again, i'd recommend Collecting directly to your axe/hoe/shovel slots*
	
<br/>

### **Pirate Crafts** - *used in pirate overworlds*
**Wooden Axe**:  
[Screenshot](https://i.imgur.com/qdy0r1s.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=53)
* Place the Crafting Table, Craft a Wooden Axe → *Chop 4+ Logs*
	* Sticks(8), bM → Half Split → lClick mM → Planks(1), tM → Half Split → Drag tR, mR → Collect: 7
		* *highly recommend to Collect to your Axe Hotbar Keybind, instead of Shift + Clicking*
			* *i have my hotkey set to 7, rebound to R, just Collect to whatever yours is bound to*

**Doors + Boat + Bowls**:  
[Screenshot](https://i.imgur.com/D7S3XDW.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=60)
* Craft Doors, a Boat, and Bowls → *Pickup the Crafting Table → Boat on the Ocean*
	* Logs(3) → Collect: sClick → Planks(1), bM → Half Split → Drag mM, tM, tR, mR, bR, bM → 
	* rClick bR → lClick mR → Collect: 3 → Half Split, bM → rClick bL → lClick mL → Collect: 4 → sClick
		* there are a few ways to do the Door Drag → Corner Drag, [they're all basically the same](https://i.imgur.com/ngH7DoB.webp)
		* and as always, change the Hotkey Keybinds to fit your specific setup

## Tasks  
**[Structure Location Commands](https://pastebin.com/raw/ifkr19dc)**  
*learn to efficiently complete these tasks*  

**Villages**  
* Kill the Golem → Craft an Iron Pickaxe and a Boat 
	* *if Bucket of Cod Trade: also Craft a Composter and a Barrel → Trade with Villagers*
* Identify which Houses have Beds in them, and which don't
	* *also identify which houses have Carpets in them, in case you need to do a Flintless Portal*

**Shipwrecks**  
* Identify each Shipwreck type from a Distance *(full, front, front+map, back)*
* Practice entering through the back side windows → Loot the Chest → get out
* Follow the Map and find the Buried Treasure

**Ocean Monuments**  
* Optimal Door placements when checking for the Gold Blocks
* Avoid the Guardian's Lazer attack

**Nether Portal Constructions** *[spreadsheet](https://docs.google.com/spreadsheets/d/1VU6IZpyhr-3tMXC5GG4ryuqrbmQkvCKE_1nJm2eym4c/edit#gid=0)*  
*also learn the 1-Deep Versions of each Portal*  
* Lava Lake Nether Portal
	* [Standard]()
	* [Flintless]() | [Carpet Flintless]()
* Ocean Ravine Nether Portal
	* [Cobblestone Skip]()
	* [2-Wide]()

**Bastions**  
* Microlensing: Locate a Bastion from your Nether Portal
* [Identification and Optimal Routing](https://github.com/Metacor/Minecraft_Speedrun_Guide#bastions)

**Fortress**  
* Pie-Ray: Locate the Fortress Direction using the F3 Pie Chart *(also useful for finding Villages)*
* Inside Navigation: Navigate to the Outside section of the Fortress, and locate a Blaze Spawner
* Blazebed: Learn to execute the correct technique for both enclosed and open Spawners
* Consistently complete the Fortress without a Fire Resistance Potion *(can use a shield)*

**Stronghold**  
* Blind Travel: Try to remember the general Coordinates for atleast the First Ring
* Triangulation: Accurately turn 90°, and be able to consistently travel 17.5 Blocks
* Stronghold Navigation: Complete [Stronghold Trial Runs](https://pastebin.com/raw/ifkr19dc)

**The End**
* Force a N/S Perch, and be able to tell when the Dragon is Perching
* One Cycle with 4-6 Beds - with both Obsidian, and either Full or Slab Block Setups *(no obby backup)*
	
<br/>

# Speedrun Cheatsheet  
[pebetedesame's Slide](https://cdn.discordapp.com/attachments/405839885509984256/891800745760948224/finished3mdpi.jpg)
### [Blind Travel](https://imgur.com/gallery/i3fIanf)
**First Ring**


0 , 220 | 50 , 210 | 75 , 200 | 100 ,  190 | 125 , 175 | 155 , 155

**Second Ring**


0 , 620 | 100 , 610 | 150 , 600 | 200 , 585 | 250 , 565 | 300 , 540 | 350 , 510 | 435 , 435

**Third Ring**


0 , 1010 | 200 , 900 | 300 , 965 | 400 , 930 | 500 , 880 | 600 , 815 | 715 , 715

### [Triangulation](https://i.imgur.com/6rvw5Bb.webp)
**1° = 1000 Blocks (Math = 1000 / x)**

| x | x.0 | x.1 | x.2 | x.3 | x.4 | x.5 | x.6 | x.7 | x.8 | x.9 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| 0 | - | - | - | - | 2500 | 2000 | 1660 | 1430 | 1250 | 1110 |  
| 1 | 1000 | 910 | 835 | 770 | 715 | 665 | 625 | 590 | 550 | 525 |  
| 2 | 500 | 475 | 455 | 435 | 415 | 400 | 385 | 370 | 355 | 345 |  
| 3 | 333 | 320 | 310 | 305 | 295 | 285 | 275 | 270 | 265 | 255 |  
| 4 | 250 | 245 | 240 | 230 | 225 | 220 | 215 | 210 | 210 | 205 |      
