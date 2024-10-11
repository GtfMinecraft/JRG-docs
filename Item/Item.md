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
- **[[Axe Inventory]]**
- [[Basic Tools]]
- **[[Food Inventory]]**
- **[[Gear Inventory]]**
- **[[Hoe Inventory]]**
- **[[NPC Item]]**
- **[[Pickaxe Inventory]]**
- **[[Rod Inventory]]**
- **[[Storage Inventory]]**
- **[[Weapon Inventory]]**

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