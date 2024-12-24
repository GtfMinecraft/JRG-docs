## Overview
```dataviewjs
let currentFilePath = dv.current().file.path;
let grandparentFolder = currentFilePath.split('/').slice(0, -2).join('/');
let grandparentFolderName = grandparentFolder.split('/').pop();
let grandparentFolderNotePath = grandparentFolder + "/" + grandparentFolderName + ".md";
if (dv.page(grandparentFolderNotePath)) {
	dv.span("[[" + grandparentFolderNotePath + "|" + grandparentFolderName + "]]");
}
else { dv.span(grandparentFolderName); }
```
%% Begin Waypoint %%
- **[[Basic Tools]]**
- **[[Crafted Items]]**
- **[[Element Tools]]**
- **[[Food]]**
- **[[Gear]]**
- **[[NPC Items]]**
- **[[Resrouces]]**

%% End Waypoint %%

## Inventory Type
- Storage Inventory
- Weapon Inventory
- Axe Inventory
- Pickaxe Inventory
- Hoe Inventory
- Rod Inventory
- Food Inventory
- Gear Inventory

## Item Type
- Basic
- Sword
- Bow
- Axe
- Pickaxe
- Hoe
- Rod
- Armor
- Accessory
- Food?
- Potion
- Fish
- Bait
- Crop
- Seed
- Ore
- Quest
- Wood