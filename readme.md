# Minecraft: Speedrun Guide - Any%, RSG, 1.16.1
[Discord](https://discord.com/invite/jmdFn3C) | [Minecraft Speedrunning Website](https://www.minecraftspeedrunning.com/) | [Minecraft Wiki](https://minecraft.fandom.com/wiki/Minecraft_Wiki) | [Speedrun.com](https://www.speedrun.com/mc#Any_Glitchless)

### To Do:
* Complete **The Nether** and **The Overworld, Part 2** Sections
* Add Crafting Screenshots for each mention of Crafting an Item *(similarly to: [Composter](https://i.imgur.com/xRd6xYT.webp))*
	* *change all current Screenshots to be cropped the same as above, name/mats/window (2 gray lines)*
		* *use the [Crafting](https://minecraft.fandom.com/wiki/Crafting) wiki page to get the correct windows*
	* *take screenshots @ 250% zoom level, post imgur links as direct link (i.imgur.com/image.webp)*
* Add Links to all Video / Section / Item references, even if they have previously been linked to

* On Completion:
	* Check the skinny main view to make sure there isn't any unnecessary text wraps
	* Spell Check / Phrasing Check the entire document *(look for missed words, poor punctuation, unclosed italics, etc)*
	* Keep consistent Capitalization *(make sure all instances of an item/entity/word are the same)*
		* *not counting the first word of a sentence*
		* *italicized side comments, such as this, should be lower case*
			* *unless referencing an otherwise Capitalized Item/Video/Section/Entity*
	* Double Check every Link to make sure it actually links something *(and make sure it leads to the correct place)*
	* Make sure there isn't any superfluous information in the Speedrun Guide section *(move it to Tips & Tricks)*

## Table of Contents
* [Setup](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#setup)
	* [Mods](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#mods)
	* [Practice Maps](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#practice-maps)
	* [F3 Keybinds](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#f3-keybinds)
	* [Inventory Management](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#inventory-management)
* [Speedrun Guide](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#speedrun-guide)
	* [The Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#beginner--structureless-overworld)
		* [Structureless](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#beginner--structureless-overworld)
		* [Village](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#standard--village-overworld)
		* [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate-overworld)
			* [Pirate → Ocean Monument](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate--ocean-monument)
		* [Hypermodern](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#expert--hypermodern-overworld)
	* [The Nether](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-nether)
		* [Bastions](https://github.com/Metacor/Minecraft-Speedrun-Guide/blob/main/readme.md#bastions)
	* [The Overworld, Part 2](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-overworld-part-2)
	* [The End](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#the-end)
* [Tips & Tricks](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#tips--tricks)
* [Practice](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#practice)
* [Speedrun Cheatsheet](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#speedrun-cheatsheet)

# Setup 
**Setup Video Guides**: [k4yfour](https://youtu.be/4cTbSyvWNgI) | [DashPum4](https://youtu.be/km0sXurMj5s)  
[Lenszel's Speedrunning Tools List](https://docs.google.com/document/d/1REEzqLCmOizEhY797kLCXI4I0ftm4N-u8aaD8ECzIw8/edit) | [
Nuskapuska Slideshow Speedrun Guide](https://youtu.be/0PXQvPNCxy8)
* Win + r → %appdata% → .minecraft → options.txt → gamma:5.0
* Options → Music & Sounds → Show Subtitles: ON  
* Options → Video Settings → Quality → Entity Distance (500)  
* with Sodium Mod: (Disabling Entity Culling isn't required for Sodium v0.2.0+)
	* Options → Video Settings → Advanced → Disable Entity Culling   
	* Options → Video Settings → Unofficial → Enable Planar Fog  

* **Timers**: [Livesplit](https://livesplit.org/downloads/) | [NinjaSnail1080's Minecraft Universal Timer](https://github.com/NinjaSnail1080/mc-universal-in-game-timer) - [Video](https://youtu.be/fPESBmKYi0Q)

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
* Sethbling's Speedrun Datapack: [Video](https://youtu.be/UihtGJhK_-w) | [Download](https://sethbling.s3-us-west-2.amazonaws.com/Downloads/DataPacks/speedrun_practice.zip)
* AndyNovo's Mapless Treasure Seed Generator Tool: [Website](https://replit.com/@AndyNovo/JustLearnTreasure) | [Example](https://i.imgur.com/8Q7Vp6B.webp)
* Semper's Nether Portal: [Video](https://youtu.be/K233ih6nSCU) | [Download](https://www.mediafire.com/file/1oanxrh14db4u7g/Portal_Practice.zip/file)
* Llama's Bastion: [Video](https://youtu.be/jlA-jW7VGqw) | [Download](https://www.dropbox.com/s/9e103bjzroi85aa/Llama%27s%20Bastion%20Practice%20v2.6.1.zip?dl=0) | [Loadout Guide](https://youtu.be/uTn9LwB5WAE)
* Semper's Blaze: [Video](https://youtu.be/CNqrnlgCRXk) | [Download](https://www.mediafire.com/file/2c6vo3qt9hv3qp5/Blaze_Practice.zip/file)
* Emma's End: [Video](https://youtu.be/fV5B7xJmiZU) | [Download](https://sites.google.com/view/emma-practice-map/home)

## F3 Keybinds
* **F3**: Standard F3 Menu  
* **F3 + F4**: Game Mode Selection | Open to LAN → Allow Cheats: ON → Start LAN World → F3 + F4 *(after a Failed Run)*  
* **F3 + Q**: Shows most of the F3 Commands in-game  
* **F3 + G**: Chunk Borders  
* **F3 + B**: Entity Hitboxes  

**Useful for [Pie-ray](https://www.youtube.com/watch?v=Aq9qfHNEOHM) scouting:** *villages and fortresses*
* **Shift + F3**: Pie Chart F3 Menu | Tick → Level → Entites → Block Entites
* **F3 + F**: Increases Render Distance by 1
* **F3 + Shift + F**: Decreases Render Distance by 1

## Inventory Management
*Storage Interfaces: Chests, Crafting Tables etc*  

**I would highly recommend changing your Hotbar Keybinds to something more comfortable** [Example](https://i.imgur.com/IRnM4qO.webp)  
* pressing 6-9 for Hotbar Hotkeys can be quite inconsistent, and remember: [don't scroll, kids](https://youtu.be/0mK4yq7AlvE?t=12)

**Hotbar Swap**: *1, 2, 3, 4, 5, 6, 7, 8, 9*
* Swaps the Hotbar Slot's Item, with the Item Slot under your Mouse's Cursor
* *this can be used to quickly Move Items into the Crafting Window, with minimal Mouse Movement*

**Collect All**: Shift + Click *(in the Crafting Output Slot)*
* Creates the maxiumum amount of an Item with the supplies currently in the Crafting Window
	* *will only Craft the Item currently shown in the Output Slot, even if the [Supplies can create multiple Items](https://i.imgur.com/TCqDxat.webp)*
		* *the Crafting Window above can Craft 1x Stone axe, 1x Stone Hoe, and 1x Stone Shovel*
			* *however, Shift + Clicking will only create the Stone Axe (doing so again will then create the hoe)*
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
* *using Pick Block to select Beds while One Cycling the Dragon is very useful*

**Drop Item**: *Q*
* Drops an Item
* *which Item you will drop depends on if your Inventory is currently Opened or Closed*
	* *Inventory Opened: Drops currently Hovered Item*
	* *Inventory Closed: Drop currently Selected Item*
* *holding the Control key while pressing Q will drop the entire Stack of Items in that Item Slot*

**Transfer Item**: *Shift + Click (left **or** right, both work)*
* Sends the Item that your Cursor is currently Hovering over To/From your Hotbar/Inventory
* *if a Storage Interface is currently Open, then the Item will Transfer between that and your Inventory instead*

**Equip Item**: *Right Click **or** Shift + Click (transfer item)*
* Puts an Equipable Item onto your Character's corresponding Equipment Slot
* *the Keybind depends on if your Inventory is currently Opened or Closed*
	* *Inventory Opened: Shift + Click (transfer item)*
	* *Inventory Closed: Right Click (selected item)*
* *both of these methods require the Equipment Slot to be currently Empty*
	* *if the Equipment Slot is currently occupied, either:*
		* *unequip the currently Equiped Item first*
		* *manually Drag your new Item onto the relevant Equipment Slot*

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

# Speedrun Guide
**Video Guides:** [Haroon Shah, Jun 2021](https://youtu.be/iaUF0oaegns) | [Couriway, Dec 2020](https://youtu.be/REas9cmjlic) | [LiquidCandy, Dec 2020](https://youtu.be/14XeowuYgV0) | [Cuffep, Oct 2020](https://youtu.be/GQodZBfdL3g)

## **Beginner** | [Structureless](https://youtu.be/7dOca1LHefk) Overworld
*Lower speed potential, but more consistent, resulting in far fewer resets - great for new runners*
* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.webp)
* Find a nearby Cave → Decend into the Cave until you find Iron Ore
* Place the Crafting Table → Craft a Wooden Pickaxe → Mine 3 Cobblestone → Craft a Stone Pickaxe → 
	* Mine 7 Iron *(8 - if you want a Shield)*, 12 Cobblestone, and 1-2 Coal
* Craft [a Furnace, a Stone Axe, and a Stone Shovel](https://i.imgur.com/4kdtS6b.webp) → Pickup the Crafting Table
* Resurface → Place the Furnace near a Tree → Smelt the Iron Ore → Chop 8+ Logs
	* Collect the first Iron Ingot → Search for Gravel → Dig for Flint → Craft a Flint and Steel
	* Kill Burning Animals to get Pre-Cooked Meat
		* While Searching for Gravel / Animals: Collect [Dandelions or Blue Orchids](https://i.imgur.com/iMwY9Wo.webp) (for Suspicious Stews)
* Collect the Iron once it's done → Place the Crafting Table → Craft an Iron Pickaxe, a Bucket, [a Boat, and Bowls](https://i.imgur.com/ROB8bsI.webp)
* Find a nearby Lava Lake, or Dig deeper in the Cave to find Lava → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* While in the Nether, Collect Mushrooms in order to Craft [Suspicious Stews](https://i.imgur.com/9ckpeB6.webp)

## **Standard** | Village Overworld 
*Spawn with a nearby Village - Ideally a Plains, Desert, or Savanna Village (for the guaranteed Hay Bales)*  
*if the Village is in a Desert, Gather Wood and Stone before entering - Trees don't spawn, and buildings are Sand*  
*if high rolled, Taiga Villages have a chance to be very good, however on average they're worse than the ones above*  

* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.webp)
* Place the Crafting Table near your Mining Destination → Craft a Wooden Pickaxe → Mine 6 Stone → 
	* Craft [a Stone Shovel, a Stone Axe, and a Stone Hoe](https://i.imgur.com/TCqDxat.webp) → Pickup the Crafting Table → Chop 8+ Logs  
### Village Tasks:
* Loot Blacksmiths, if available:
	* if 10+ Obsidian: Skip Bucket → Mine 4 Stone, *(instead of 6)* → Skip the Stone Hoe Craft
		* *skipping the Stone Hoe Craft makes gathering hay bales take slightly longer*
			* *but it allows you to skip a second Sticks Craft when making your Iron Pickaxe*
	* if 3+ Iron Ingots: Gather 2 Logs, instead of 3 → Skip Wooden Pickaxe
	* if 7+ Total Iron Ingots *(Blacksmith + Golem)*: Skip the Bucket of Cod Trade 
		* *you can skip with 6 Iron, but that will require a [Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=9)*
* Collect Beds from the Village Houses, *(and Carpets, if you plan on doing the [Carpet Flintless Portal](https://youtu.be/DVDbfKuLaWo?t=38))*
* Kill the Golem: Drops 3-5 Iron Ingots
	* Hit the Golem from max distance, from behind if possible → Run a few Blocks away → Build up 3 Blocks
	* Crit the Golem ~8 times to Kill it: Jump → Fall → Attack, while Falling *(with Stone Hatchet)*
* Place the Crafting Table → Craft an Iron Pickaxe and a Boat
	* if Bucket of Cod Trade: Place this Crafting Table near Villagers, additionally: Craft a [Composter](https://i.imgur.com/qK3yzOP.webp) and a [Barrel](https://i.imgur.com/arI5xh9.webp)
	* if 4 Iron Ingots: Craft a Flint and Steel, *(after getting Flint from Digging up Gravel)*
		* *if you only get 3 Iron Ingots: [Flintless Portal](https://youtu.be/axHdNQtPOf8?t=66), or Search for a Shipwreck/Ruined Portal*
	* if 5 Iron Ingots: Save 1 Iron for a Shield, in case you get a Fortress before a Bastion in the Nether
* Hoe 7 Hay Bales → Craft Wheat (7:63) → Hoe 5-10 additional Hay Bales → Complete the Bucket of Cod Trade
	* Find or Craft a [Composter](https://i.imgur.com/qK3yzOP.webp) → Turn a Villager into a Farmer → Trade Wheat 60:3 Emeralds
	* Find or Craft a [Barrel](https://i.imgur.com/arI5xh9.webp) → Turn a Villager into a Fisherman → Trade Emeralds 3:1 Bucket of Cod
* Craft the Hay Bales into Wheat → Craft Bread → Pickup the Crafting Table
* Leave the Village → Search for a Lava Lake or Ruined Portal → [Create a Nether Portal](https://youtu.be/iaUF0oaegns?t=2029) → Enter the Nether
	* [Minimum Blocks Required](https://i.imgur.com/jSspUON.webp) | [Minimum Space Required](https://i.imgur.com/MvQjKXN.webp)
		* *for minimum space, the bottom 2 spaces aren't required if doing [Cave Portal](https://youtu.be/6Lw2Mng_q4U) | [1-Deep](https://youtu.be/IHnBUAgQwsc)*
		
## **Advanced** | [Pirate](https://youtu.be/EJ4G8QbhrGM) Overworld
*Spawn near an Ocean, with a Shipwreck nearby - with 7+ Iron inside (ideally 11+)*
* Gather 3 Logs → Craft 12 Planks → Craft [a Crafting Table + 8 Sticks](https://i.imgur.com/pzABDu2.webp)
* Place the Crafting Table near a Tree → Craft a Wooden Axe → Chop 4+ Logs →
	* Craft Doors, a Boat, and some Bowls → Pickup the Crafting Table
* Place the Boat in the Ocean → Search for a Shipwreck → Collect the Boat and Dive towards the Shipwreck
* Once you find a Shipwreck → Enter the Top Side at the Back of the Boat → Loot the Chest (Iron / Gold) →
	* if < 7 Iron: Loot the Bottom Side Chest at the Back of the Boat → Collect the Buried Treasure Map
		* You can use the opened Door in the Bottom Cabin to refresh your Breath Meter 
		* Locate the Buried Treasure, if the Loot is bad → Reset
* Swim to the nearest Gravel → Place the Crafting Table, on the Ocean Floor → Place a Door on top of the Table →
	* Craft an Iron Pickaxe, a Bucket, a Shovel 
		* if 8+ Iron: Iron Shovel, otherwise Wood/Stone Shovel
		* if 11+ iron: Craft an Iron Axe
			* *if you don't get an Iron Axe, try to Gather 3 Cobblestone while teleporting to the Nether [Video](https://youtu.be/So076O4FrU0)*
		* if any remaining Iron Ingots, Craft Iron Armor (can also save 1 for a Shield, if Fortress before Bastion)
	* Dig up Gravel until you find some Flint → Craft a Flint and Steel → Pickup the Crafting Table (and Door)
* Resurface → Place the Boat → Search for an Ocean Ravine
* Create a Ravine Nether Portal: [Spreadsheet](https://docs.google.com/spreadsheets/d/1VU6IZpyhr-3tMXC5GG4ryuqrbmQkvCKE_1nJm2eym4c/edit#gid=1186267001)
	* [Standard]() | [1-Deep]() 
		* *Cobblestone Skip is faster, and not really any harder, so optionally: skip learning Standard*
	* [Cobblestone Skip]() - [Safe]() | [1-Deep]()
	* [2-Wide, Doors]() | [1-Deep]()

<br/>

* You wont have any Beds, so make sure you get enough String from Piglin Trades: 6 Beds = 72 String (+18 Planks)
	* You can also use Iron Nuggets 9:1 Iron Ingots → Shears →
		* Shear Sheep in the Overworld or Collect Cobwebs in a Stronghold Library
* You wont have much Food (if any):
	* In the Nether: Craft [Mushroom Stews](https://i.imgur.com/FUo9nfP.webp) or Kill Burning Hoglins to get Pre-Cooked Meat
		* *if you looted carrots from the Shipwreck, you can Craft some [Golden Carrots](https://i.imgur.com/bWyYsaC.webp)*
	* In the Overworld: Kill Burning Animals to get Pre-Cooked Meat
	* Optionally: Suicide to Reset Hitpoints / Hunger
		* Nether: Craft a [Respawn Anchor](https://i.imgur.com/mo7y0XA.webp) → use a Glowstone Block on it → Suicide
		* Overworld: Craft and Place a Bed → Right-Click the Bed → Suicide
	* Suicide Methods: *make sure to dig down 2 Blocks and kill yourself in a hole so your Items don't fly everywhere*
		* [Fire](https://youtu.be/itqFlGfKvdk?t=460): Use either a Flint and Steel or Lava to set yourself on Fire
			* *douse the Fire before you die, so you don't accidently destroy your Items*
		* Ender Pearl: Throw Ender Pearls into a nearby Block, dealing 2.5 Hearts of Damage on impact
		* Fall Damage: 1/2 Heart per Block above 3 Blocks
			* *4 Blocks = 1/2 Heart | 7 Blocks = 2 Hearts | 15 Blocks = 6 Hearts, etc*
			* *While in the Stronghold, you can climb up the Starter Staircase to easily get some height*

## **Advanced+** | Pirate → Ocean Monument
**Ocean Monument Guides:* [T_Wagz](https://youtu.be/0dyHYkg_xIU) | [Silver](https://youtu.be/14FGC1eUHug) - [Silver, Part 2](https://youtu.be/-b7nQyXZkfw)**  
*Same start as [Pirate Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate-overworld), but you also Gather the guaranteed 8 Gold Blocks from an Ocean Monument*  
*sometimes allowing you to completely skip the Bastion while in the Nether*  
* Pirate Start → Shipwreck (Craft a Shield, since you wont have Fire Resistance for the Fortress) → Ocean Monument
	* As soon as you see an Ocean Monument, turn your Render Distance to 2 (RD2)
		* *this will usually result in the Elder Guardians not spawning, allowing you to avoid Mining Fatigue*
	* if you get Mining Fatigue
		* *Drink a Milk Bucket (use an Empty Bucket on a cow, mooshroom, or goat)*
		* *Set your Spawn at a Bed, and Suicide, (see Suicide Methods in [Pirate Overworld](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#advanced--pirate-overworld))*
			* *optionally: if you're close to the World Spawn, Suicide without setting your Spawn*
	* loot the 8 Gold Blocks from the Monument, following one of the guides linked above → Leave the Monument
	* Once you're a reasonable distance away from the Monument, set your Render Distance back to normal
* Continue with the normal Pirate strats → Ravine Nether Portal → Enter the Nether
	* The same Bed/Food limitations exist  

<br/>

* While in the Nether: Find a Fortress → Trade with nearby randomly spawned Piglins → Kill Blazes for Blaze Rods
	* *trap 2 Piglins in a Boat, or in a 2 Block deep hole → Throw them your Gold Ingots → Proceed into the Fortress*
		* *don't forget to return to the Piglins to collect your loot - if you didn't get enough → Find a Bastion*

## **Expert** | [Hypermodern](https://youtu.be/gAHMJfsrHe4) Overworld
*Combination of the most optimal strats, Resets are frequent, so having a very high Reset Efficiency is recommended*
* [Mapless Treasure](https://youtu.be/_dyD8ZwagDg), *if available* → [Pirate](https://github.com/Metacor/Minecraft_Speedrun_Guide#advanced--pirate-overworld) → [Ravine Nether Entry](https://youtu.be/H2fHDidyfJo?t=63) → 
	* *if you spot a Shipwreck from your spawn location, [prioritize that](https://youtu.be/CEG8oXyz9zc?t=257) over of Mapless Treasure*
* [Microlensing](https://youtu.be/jvTfMLPnMSw) → [Bastion](https://github.com/Metacor/Minecraft_Speedrun_Guide#bastions) → [Pie-Ray](https://youtu.be/Aq9qfHNEOHM) → Fortress, [Blazebed](https://www.youtube.com/watch?v=3TD4jkuT8QA) → [Blind](https://i.imgur.com/96KhbT2.webp) / [Divine](https://youtu.be/SXem01c44-I) Travel
	* if 20+ Obsidian: [Axis Calculated Travel](https://youtu.be/0LDj48fsRT8)
* [Triangulation](https://youtu.be/8c29j0We2VQ) → Stronghold Entry *(if Ocean exposed: Portal Room Entry,  else: Starter Staircase Entry)* → End Entry →
	* [Half-Bow](https://youtu.be/whwjNbIni58) + North / South Ground + [One-Cycle Dragon](https://youtu.be/aGMLHXnD6Bc) (~[4 Bed](https://youtu.be/R-9PGkSJU7g))  


*Optionally*   
* Village Start: if there is a close Lava Lake | Ruined Portal | Blacksmith, with 10+ Obsidian
	* if >= 7 Iron (Blacksmith + Golem): Iron Pickaxe + Bucket + Flint and Steel
		* *optionally, if 4+ Iron from the Blacksmith: skip the Golem → skip the Iron Pickaxe → get lucky*
	* if 4-6 Iron: Skip the Iron Pickaxe, hopefully get lucky with Iron from Bastion Chests
	* if 3 Iron: Reset *(or Flintless Portal, if you REALLY want to force the seed)*

<br/>

## The Nether
*Find a Bastion, Trade Gold to Piglins for Obsidian and Ender Pearls → Find a Fortress, Kill Blazes for Blaze Rods*

### **Microlensing**, *a.k.a. E-Ray*  
**Video Guides**: [k4yfour](https://youtu.be/jvTfMLPnMSw) - [k4yfour, Part 2](https://youtu.be/Ou58P7e-ZY0) | [Nuskapuska's Slide](https://i.imgur.com/98heFGq.webp)
* When you enter The Nether, open your F3 Menu *(if not already opened)*, and look at the **Right** [E: Value](https://i.imgur.com/w6WZlqf.webp)
	* *for example, in the image linked above, E: 32/**122**, you should be looking at 122*
	* *ideally, open your F3 Menu before entering your Nether Portal in the Overworld*
* if you notice the E: Value quickly raises, you likely just loaded a Bastion into your Render Distance
	* *if the sum of the M: & C: Values is ~30 higher than the E: Value, there is likely a Bastion*
		* *if [M + C = 113, while E = 122](https://i.imgur.com/w6WZlqf.webp), then there likely isn't a Bastion nearby*
		* *using 16 RD, Starting at (-77, 59, 58), the closest Bastion is at [(-128, ~, -288)](https://i.imgur.com/EVScDGC.webp), being ~350 Blocks away*
* To find the Bastion direction, change your Fov to 30 then slowly turn 360°, and look at the **Left** E: Value
	* *as opposed to the previous example, in the [image linked above](https://i.imgur.com/w6WZlqf.webp), E: **32**/122, you should be looking at 32 this time*
	* *High density Biomes can sometimes give false positives for Bastions, use (E + 30 ≈ M + C), for a better idea*

### **Bastions**  
[pncakespoon's Route Spreadsheet](https://docs.google.com/spreadsheets/d/1qLgp5uhMOKuerNZaec1dpoECpJI0-6YhztMqa_wZ8W0/edit#gid=1811348189) | [Bastion Resources](https://docs.google.com/document/d/1yuruZF575xvwOCB5t6ftfRY9OEtLDRQsWFJRD6YetU0/edit) | [Zolstice's Beginner Screenshot Guide](https://www.reddit.com/r/MinecraftSpeedrun/collection/a6121708-188c-43b9-8267-de61620456f1/)  
*ideally, locate and finish the Bastion before the Fortress, for the chance to get Fire Resistance Potions*  

**Identify the Bastion Type, and run the Route accordingly**  

* Bridge: [Structure Video](https://youtu.be/2pzMpX1RJGI?t=128) | [Screenshots](https://imgur.com/a/OHwW0tb) | [Strat Flowchart](https://i.imgur.com/S7Uqb6C.webp)  
*if buried left/right Triple, Craft a Gold Pickaxe*  
	* if Triple, *(Right Shoulder)*: [Dowsky](https://youtu.be/RAgYDi23Dww)
	* if Triple, *(Left Shoulder)*: [Reignex/Gus](https://youtu.be/aKxDbLTZ2f0) | [Buried](https://www.twitch.tv/videos/1056189431)
	* if Double Single: [Ela's Hole](https://youtu.be/3SHj_nm8mC0)
	* if Top Entry: [Lodestone Manhunt](https://youtu.be/n5HDxqNFe4s?t=593)
* Treasure: [Structure Video](https://youtu.be/A9GGUWwNcrY?t=132) | [Screenshots](https://imgur.com/gallery/U4FnQC5) | [Bottom Placements](https://i.imgur.com/bDQjaBL.webp)  
*highly recommended to Craft a Gold Pickaxe with the [Gold Blocks on the bridge](https://youtu.be/Y0DCoD6yhIc?t=9)*
	* [Ninjabrain](https://youtu.be/0YvGkSOJVmU)
* Housing: [Structure Video](https://youtu.be/BoNr-pbEITM?t=132) | [Screenshots](https://imgur.com/gallery/wyjWcli) | [Correct Direction](https://youtu.be/BoNr-pbEITM?t=853)
	* if Bot: [Manhunt]()
	* if Top: [Top Down Manhunt](https://youtu.be/55sRL0xsWe8)
		* Advanced: [Kuee Top Down](https://youtu.be/H2xy6q5Wp4Q)
* Stables: [Structure Video](https://youtu.be/TioQsF5ygOg?t=149) | [Screenshots](https://imgur.com/gallery/u91rHC4) | [Gap Identification](https://www.youtube.com/watch?v=AczOTF5QpZ4&t=164s)
	* if Triple: [Triple Chest Stables](https://youtu.be/AJxgbRma25Q)
	* if no Triple, w/ Good Gap: [Good Gap Stables](https://www.youtube.com/watch?v=ukyIkZMnw-w&t=357s)
	* if no Triple, w/ Double Bad Gap: [Better Luck Next Time](https://i.imgur.com/YxRxdhI.webp)

<br/>

**Required Items**  
* 10+ **Obsidian**, required to Blind Travel out of the Nether
	* *ideally, 20+ for Educated/Calculated Travel*
* 12+ **Ender Pearls**, required to fill the 12 [End Portal Frames](https://minecraft.fandom.com/wiki/End_Portal_Frame) in the Stronghold
	* *ideally, 16+, 2 for the Ender Dragon fight, 2+ for broken Eye of Enders*  

**Optional Items**  
* **Fire Resistance Potion**: Makes you immune to Lava / Fire Damage 
	* *makes you immune to blaze's fireballs, but not their melee attacks*
* **String**: Allows you to Craft 4:1 Wool in order to Craft 3:1 Beds 
	* *if you don't have enough Beds from the Overworld, this isn't optional*
* *Cross***Bow + Arrows**: Allows you to [Half-Bow](https://youtu.be/whwjNbIni58) while in the Ender Dragon fight
* **Fire Charge**: if you entered the Nether with a Flintless Portal method, this can substitute for a Flint and Steel
	* *if you gathered Flint while in the Overworld, you can also use Iron Nuggets to Craft a Flint and Steel*
		* *Piglins also Trade Gravel, so you can collect Flint in the Nether if you'd like*

<br/>

### **Pie-Ray**, *a.k.a. Piedar*

### **Fortress**

### **Travel**
* Blind
* Divine
* Educated
	* Calculated
		* Axis Calculated

<br/>

## The Overworld, Part 2
*Find the Location of a Stronghold → Enter the Stronghold, and Navigate to the Portal Room → Enter The End*

### **Triangulation**
* Axis Calculated for Triangulation

### **Stronghold Navigation**
* 4/x/4 (3-5/x/3-5)

Enter the End
			
<br/>

## The End
*Kill the Ender Dragon, Finishing the Game*

**Video Guides**: [k4yfour](https://youtu.be/-Ta_1R1aXvA) | [Hashten](https://youtu.be/aGMLHXnD6Bc) | [BoomerPlayz](https://youtu.be/1daiTbj1OiE) - [Part 2](https://youtu.be/uBp8uVbW1us)

* When you spawn in The End, get to the Fountain as soon as possible
	* *if you spawn above ground, Ender Pearl directly to the Fountain*
	* *if you spawn underground, Mine up along the West wall, ideally in a corner*
* Setup your preferred Bed Platform: [Obsidian]() | [Full Block]() | [Slab]()
	* *run away in your preferred Perch direction (N/S or E/W)*
		* *your Bed Platform position might need to change, based on your chosen Perch direction*
* Execute your preferred End Island method:
	* if you have a *(cross)* Bow and Arrows → [Half-Bow]()
	* if you have 2+ Pearls, and you don't plan on doing Half-Bow:
		* [Pearl up to the highest Obsidian Tower](https://youtu.be/-Ta_1R1aXvA?t=116) in the direction you chose, [build up until you reach y = 122](https://youtu.be/-Ta_1R1aXvA?t=128)
	* if you don't have 2+ Pearls, and you also don't plan on doing Half-Bow:
		* [Run as far away from the Fountain as possible](https://youtu.be/-Ta_1R1aXvA?t=519), while still being able to see if the Dragon is Perching
* Turn on Entity Hitboxes *(F3 + B)* to help with One-Cycling the Dragon
	* *hitboxes will also make it more obvious when the Dragon's head "snaps" to the center before Perching*
* When the Dragon begins to Perch, either Ender Pearl or run to the Fountain → One-Cycle the Dragon with Beds
* Once the Dragon is Defeated, stand inside of the Fountain - **Timing ends on the screen transition**
		
<br/>

# Tips & Tricks
### The Overworld
* [Shipwrecks](https://i.imgur.com/ws384ow.webp)
	* Front Side Chest: Food 
		* *if the Shipwreck is right-side up, you can loot this chest [from above](https://youtu.be/EUiU5MZt_7g?t=72)*
	* Back Side: *the back side is wider, and has a window on all 3 outer sides*
		* Top Chest: Iron Ingots, Gold Ingots
			* *if the Shipwreck is right-side up, you can loot this chest [from above](https://youtu.be/dX83N4q4YWU?t=57)*
		* Bot Chest: Buried Treasure Maps
			* Buried Treasure is always located @ 9/x/9 in the Chunk where the X is located 
* In Ocean Monuments, the Guardian's Lazer attack will kill you in: Hits Required (Damage Taken/20)
	* Easy = 5 (4) **|** Normal = 4 (6) **|** Hard = 3 (9)
		* *with Healing, Easy will almost always take 6 hits, and Normal will sometimes take 5*
	* *their lazer attack requires 2 seconds of uninterrupted line of sight, simply break LoS to take 0 Damage*
* [Desert Temples](https://youtu.be/gS6LxaNibWM?t=76)
	* To quickly collect all of the Chests, aswell as any surrounding Blocks
		* Collect all of the TnT → Place 1 TnT under you → 
		* Place 1 TnT in a Corner on the Top → 
		* Place a Pressure Plate next to it → 
		* Activate the Pressure Plate →
		* Break the TnT below you (don't activate it) →
		* Crouch in the hole under the active TnT, avoiding most of it's Damage
* if the Iron Golem is already in a good spot, you can build up next to it before you attack
* Mining Stone takes slightly less time than Mining Cobblestone, (typically found as part of Plains Village houses)
	* Wooden Pickaxe: Stone takes **1.15 Seconds** | Cobblestone takes **1.5 Seconds**
	* Stone Pickaxe: Stone takes **0.6 Seconds** | Cobblestone takes **0.75 Seconds**
* Lava Lakes tend to spawn underneath Water Lakes
	* *if you're unable to find a Lava Lake on the surface, try digging near small surface Water Lakes*
* When Searching for an Ocean Ravine, turn on Entity Hitboxes (F3 + B), and look out for Floating Kelp
	* *if you see floating Kelp in a Deep Ocean, there is [likely a Ravine below it](https://youtu.be/yGyMWYhHYoQ?t=471)*
* to avoid Glitchy Buckets while making Nether Portals, watch this [Video](https://youtu.be/EjwStTX4U3A)
* Buckets of Water don't actually work in the Nether, so when you finish your Nether Portal, fill the Bucket with Lava
* if you plan on Microlensing your Bastion in the Nether, turn on the F3 Menu before you teleport to the Nether

### The Nether
* Falling while in a Boat will negate all Fall Damage: [Video](https://youtu.be/REas9cmjlic?t=686)
* Killing Burning Hoglins is an easy way to get food in the Nether [Lava Bucket](https://youtu.be/wjbQyyHkr9M?t=110) | [Flint and Steel](https://youtu.be/REas9cmjlic?t=694)
* if you need more Blocks while in the Nether, Mine some Netherrack
	* Netherrack isn't flammable, and it's very fast to Mine (0.1s with an Iron Pickaxe)
* if there is a far away Ghast attacking you, quickly lower your Render Distance to 2
	* [This will usually despawn the Ghast](https://youtu.be/tWVrxt0G6r0?t=696)
	* *You can turn your Render Distance back up after it disappears*
	* *if the Ghast is close, just reflect its attack back at it*
* if you find Nether Gold Ore while travelling to a Bastion, consider Mining it and making [Gold Boots](https://i.imgur.com/7k7LTAL.webp)
	* *Boots only take 4 Gold Ingots (36 Gold Nuggets)*
	* *Wearing any Gold Armor will make it so Piglins don't auto-aggro you*
* Bastions cannot spawn inside of a Basalt Delta Biome
* Only 1 Structure *(Bastions and Fortresses)*, can spawn per *(432, 432)* MegaChunk, for example:
	* *if a Bastion spawns at (+x, +z), this will be the only Structure in that MegaChunk*
	* *in order to find a new Structure, you will need to go to a new MegaChunk*
	* *the remaining 3 inner Quadrants being: (+x,-z), (-x,-z), (-x,+z) | where x & z are < 432 (neg or pos)*
		* *directions can also be called: (pos, pos), (pos, neg), (neg, neg), (neg, pos)*
	* *Structures in MegaChunk beyond the inner 4 Quadrants are known as Extra-Regional Structures*
* All Bastion types (besides Treasure), can spawn a Triple Chest top section - to easily tell them apart:
	* if there are 2 Blocks between the Double/Single Chest, then it's Stables
	* if there are 3 Blocks, then it can be either Housing or Bridge
		* *Housing and Bridge are very different, so it shouldn't be too hard to Identify the correct one*
* Piglins have weird pathfinding around Lava
	* *when building bridges across Lava - while routing bottom side Manhunt Housing for example*
		* *build 1 block above Lava (instead of inside of it)*
			* *if forced to build inside, use stairs at the ends of your bridge*
			* *piglins seem to refuse to jump up/down a block at the edges of lava*
		* *build 3 Blocks wide, to make sure Piglins follow*
		* *piglins can't run across corners, so make sure there is a direct path over the Lava*
* Mobs spawn more often in Soul Sand Valleys, so if a Fortress is located in one, 5RD is pretty risky
* While trying to Pie-Ray, if you accidentally press the wrong button, press '0' to go back a page  
* Blazes will Target a Player if they have Line of Sight, and are within 48 Blocks
	* *once acquiring a Target, the Blaze will set itself... **ablaze**, for 3 seconds*
	* *at the end of this 3 second period, the Blaze will begin to shoot a Volley of 3 Fireballs*
		* *if the Blaze loses Line of Sight with its Target, the Volley will be paused*
		* *upon regaining Line of Sight, the Volley will be resumed, shooting any remaining Fireballs*
	* *after the final Fireball is shot, the Blaze will be unable to Target for 5 seconds*
	
### The Overworld, Part 2
* The Stronghold will spawn a minimum of 1400 Blocks from *(0, 0)*
	* *this distance is calculated triangularly, not linearly, (so a²+b²=c²), not (a+b=c)*
		* *(150x, 150z) would be ~212 Blocks away from (0, 0) -- not ~300*
	* *if you're just adding x + z: Stronghold ≈ 2000 - 2400 (Overworld), 250 - 300 (Nether)
* When travelling across Water, it is faster to use a Dolphin's Boost, than it would be to use a Boat
* if you find an underwater Stronghold, make sure to look around for the Portal Room before blindly entering
* Strongholds are extremely unlikely to spawn in Swamps ([supposedly](https://youtu.be/_rbWryJVEmw?t=1011))
* The Portal Room is usually within [5 = 7](https://youtu.be/u42bjqtq5-s) Rooms of the Starter Staircase
* In the Stronghold, Spiral Staircases always lead up, towards the Starter Staircase
* [Hidden Rooms Identification](https://www.youtube.com/watch?v=vztJNmUdyBY)
	* *generally, in 5-way rooms, if you see an indentation in the wall, there will be a hidden room on that side*
	* *for example, if there is an indentation in the top left, the bottom left wall will be a Hidden Room*
* Libraries lead nowhere, if you enter a Library from the Starter Staircase, turn around
	* if you need more Beds, you can Gather string from Library Cobwebs
		* *use either a Sword or Shears, (decreasing the Gather Time from 20s → 0.4s)*

### The End
* You always Spawn to the East, facing the Main Island
* The Dragon Perches faster the farther away you are from the Fountain, both height and distance
* The Dragon will Perch from the opposite side of you, in relation to the Fountain
	* *Diagonal Perches are a lot harder to One Cycle, so it's recommended to run away N/S/E/W*
	* *N/S Perch is faster than E/W, however it gives the player less time to react to the Perch*
* The Dragon's Fireball doesn't actually do damage, the AoE ground effect left behind is what damages you
	* *an easy way to avoid the damage, is to get hit on purpose, then Jump → place a Block below you*
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
*the Item(num) positions will assume that you have completed the previous methods as listed*  
	
<br/>

**Crafting Table + Sticks**: *used in practically every run*  
[Screenshot](https://i.imgur.com/pzABDu2.webp) | [Videos](https://youtu.be/lEdAMNweD7E): **[Half Split (8c)](https://youtu.be/lEdAMNweD7E?t=2)** - [Kuee (8c)](https://youtu.be/lEdAMNweD7E?t=8) - [Split 2 (10c)](https://youtu.be/lEdAMNweD7E?t=13) - [Double Split, Move (10c)](https://youtu.be/lEdAMNweD7E?t=20) - [Double Split, Throw (9c)](https://youtu.be/lEdAMNweD7E?t=28)  
*while Kuee's Method also only takes 8 Clicks, I personally feel that it doesn't flow as nicely as the Half Split Method*  
*this is by far the most common Craft you'll execute when speedrunning, so be sure to pick the one that feels best to you*  
* Gather 3 Logs, turn them into 12 Planks, then Craft a Crafting Table and 8 Sticks
	* Logs(1) → collect: sClick → Planks(9), bR → Half Split → Drag bR, bL, tL → lClick tR → collect: sClick x2  
	
<br/>

### **Standard Crafts** - *used in structureless and village overworlds*
**Wooden Pickaxe**:  
[Screenshot](https://i.imgur.com/k3vCKuq.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=37)
* Place the Crafting Table, Craft a Wooden Pickaxe → *Mine 6 Cobblestone*
	* Sticks(8), bM → Half Split → lClick mM → Planks(1), tL → Half Split → Drag tM, tR → collect: 8
		* *highly recommend to collect to your Pickaxe Hotbar Keybind, instead of shift + clicking*
			* *i have my hotkey set to 8, rebound to F, just collect to whatever yours is bound to*

**Stone Tools**: *if Hoe Skip: Mine 4 Cobblestone instead - the same movements can be used*  
[Screenshot](https://i.imgur.com/TCqDxat.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=45)
* Craft a Stone Axe, a Stone Hoe, and a Stone Shovel → *Pickup the Crafting Table → Chop 8+ Logs*
	* Sticks(2), bM → Half Split → lClick mM → Stone(3), tM → Half Split → rClick mL → lClick tL → collect: 7 → 4 → 5
		* *once again, i'd recommend collecting directly to your axe/hoe/shovel slots*
	
<br/>

### **Pirate Crafts** - *used in pirate overworlds*
**Wooden Axe**:  
[Screenshot](https://i.imgur.com/pZaExqe.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=53)
* Place the Crafting Table, Craft a Wooden Axe → *Chop 4+ Logs*
	* Sticks(8), bM → Half Split → lClick mM → Planks(1), tM → Half Split → Drag tR, mR → collect: 7
		* *highly recommend to collect to your Axe Hotbar Keybind, instead of Shift + Clicking*
			* *i have my hotkey set to 7, rebound to R, just collect to whatever yours is bound to*

**Doors + Boat + Bowls**:  
[Screenshot 1](https://i.imgur.com/Brr2zq1.webp) - [Screenshot 2](https://i.imgur.com/La90qWK.webp) | [Video](https://youtu.be/lEdAMNweD7E?t=60)
* Craft Doors, a Boat, and Bowls → *Pickup the Crafting Table → Boat on the Ocean*
	* Logs(3) → collect: sClick → Planks(1), bM → Half Split → Drag mM, tM, tR, mR, bR, bM → 
	* rClick bR → lClick mR → collect: 3 → Half Split, bM → rClick bL → lClick mL → collect: 4 → sClick
		* there are a few ways to do the Door Drag → Corner Drag, [they're all basically the same](https://i.imgur.com/ngH7DoB.webp)
		* and as always, change the Hotkey Keybinds to fit your specific setup

## Tasks  
*learn to efficiently complete these tasks*  

**Villages**  
* Kill the Golem → Craft an Iron Pickaxe and a Boat 
	* *if Bucket of Cod Trade: also Craft a Composter and a Barrel → Trade with Villagers*
* Identify which Houses have Beds in them, and which don't
	* *also identify which houses have Carpets in them, in case you need to do a Flintless Portal*

**Shipwrecks**  
* Identify each Shipwreck type from a distance *(full, front, front+map, back)*
* Practice entering through the back side windows → loot the Chest → get out
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
* [Identification and Optimal Routing](https://github.com/Metacor/Minecraft_Speedrun_Guide/blob/main/readme.md#bastions)
* Microlensing: Locate a Bastion from your Nether Portal

**Fortress**  
* Inside Navigation: Naviate to the Outside section of the Fortress, and locate a Blaze Spawner
* Blazebed: Learn to execute the correct technique for both enclosed and open spawners
* Consistently complete the Fortress without a Fire Resistance Potion *(can use a shield)*
* Pie-Ray: Locate the Fortress direction using the F3 Pie Chart *(also useful for finding Villages)*

**Stronghold**  
* Blind Travel: Try to remember the general Coordinates for atleast the First Ring
* Triangulation: Accurately turn 90°, and be able to consistently travel 17.5 Blocks
* Stronghold Navigation: Complete [Stronghold Trial Runs](https://pastebin.com/raw/aMGheVgQ), starting from random positions

**The End**
* Force a N/S Perch, and be able to tell when the Dragon is Perching
* One Cycle with <= 6 Beds - with both Obsidian, and either Full or Slab Block Setups *(no obby backup)*
	
<br/>

# Speedrun Cheatsheet  
*pebetedesame's [Cheatsheet](https://cdn.discordapp.com/attachments/405839885509984256/891800745760948224/finished3mdpi.jpg)*  
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
