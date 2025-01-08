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

## [[Spawn in Flamora]]
Player teleports to the element world.

## [[The Great Desert]]
Entered the Great Desert.

## [[Enter Gravaris]]
Player saw the King and became part of Earth.

## [[Earth Blessing Acquired]]
Player acquired Earth element from Earth Temple.

## [[Explore Gravaris]]
A day as part of Earth.

## [[Nexus and Water Territory]]
Audio bug happened, Dev added Marisol and Nexus.

## [[King's Missive]]
Player gets Terran King's missive, allowing Player to visit Marisol, and Player teleports to Nexus.

## [[A Tour in Nexus]]
The prosperous city for all elements, player sees the treaty and understand world structure.

## [[History of the Treaty]]

## [[Skyria]]
