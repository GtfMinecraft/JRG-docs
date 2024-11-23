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
- [[Entering Gravaris]]
- [[Meet the Terran King]]
- [[Narrow Escape]]

%% End Waypoint %%

## Spawn in Flamora
Player teleports to the element world.

> Characters: [[Dev]], [[Player]], [[Pyrrithian Guards]]
> Items: 
> Events: [[Narrow Escape]]

## The Great Desert
Entered the Great Desert.

> Characters: [[Player]], [[Dev]]
> Items: 
> Events: 

## Enter Gravaris
Player saw the King and became part of Earth.

> Characters: [[Player]], [[Terran King]], [[Terrans]]
> Items: 
> Events: [[Entering Gravaris]], [[Meet the Terran King]]

## Nexus

## Skyria

## 
