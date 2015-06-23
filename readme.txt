This is just an example, not a HowTo !!!

What is cfgCrafting ?
- Players can craft Items, Magazines, Vest or Guns.

Download:
- cfgCraftinglist by GBR Suppe (Custom Part is marked in the cfgCrafting.hpp)
https://github.com/GBR-Suppe/cfgCrafting-Master

Install:
- Add the cfgCrafting.hpp in your epoch.Mission
- Add to your description.ext: #include "cfgCrafting.hpp"

Install optional:
- Add to your briefing:

player createDiarySubject ["menu88","Custom Crafting"];

player createDiaryRecord ["menu88",
["Custom Crafting","<br/>

On our Servers you have the possibility to craft more Objects or Items.<br/>

Example: Double click on ItemScrap or ElectronicComponent.<br/><br/>

Craftlist:<br/>
NVGs =    ItemScraps 1 + Binocular 1 + ElectronicComponent 1 + near Fire<br/><br/>

optic_LRPS = ItemScraps 2 + Binocular 1 + near Fire<br/>
optic_tws = ItemScraps 2 + Rangefinder 1 + ElectronicComponent 1 + near Fire<br/><br/>

Vest 10 = Pelt_EPOCH 1 + ItemRope 1<br/>
Vest 30 = Pelt_EPOCH 2 + ItemRope 2 + ItemScraps 1 + near Fire<br/>
Vest 39 = Pelt_EPOCH 2 + ItemRope 2 + ItemCorrugated 1 + near Fire<br/><br/>

Binoculars and Rangefinder must be in the inventory, not equipped.<br/><br/>

It is only the beginning, we will add more.<br/><br/>
"]];

Info:
- Craft a Backpack, Vehicle or Objekt dont work ! Only Items,Guns,Vests or Magazines are craftable !
- For an example ingame: Double click on ItemScrap or ElectronicComponent.

In this Craftlist are:
NVGs =    ItemScraps 1 + Binocular 1 + ElectronicComponent 1 + near Fire

optic_LRPS = ItemScraps 2 + Binocular 1 + near Fire
optic_tws = ItemScraps 2 + Rangefinder 1 + ElectronicComponent 1 + near Fire

Vest 10 = Pelt_EPOCH 1 + ItemRope 1
Vest 30 = Pelt_EPOCH 2 + ItemRope 2 + ItemScraps 1 + near Fire
Vest 39 = Pelt_EPOCH 2 + ItemRope 2 + ItemCorrugated 1 + near Fire

- Binoculars and Rangefinder must be in the inventory, not equipped.


GBR Suppe