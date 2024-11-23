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

> Characters: [[Player]], [[Dev]], [[Pyrrithian Guards]]
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
> Events: [[Entering Gravaris]], [[Meet the Terran King]], [[Earth Element Acquired]]

## Explore Gravaris
A day as part of Earth.

> Characters: [[Player]], [[Terrans]]
> Items: 
> Events: [[Hospitable Neighbor]]

## Dev's Return
Audio bug happened, Dev added Skyria and Nexus.

> Characters: [[Player]], [[Dev]]
> Items: 
> Events: [[Audio Bug]], [[Two New Regions]], [[Dev's Plan Onward]]

## King's Missive
Player gets Terran King's missive, allowing Player to visit Skyria, and Player teleports to Nexus.

> Characters: [[Player]], [[Terran King]]
> Items: 
> Events: [[King's Missive for Skyria]], [[Teleportation to Nexus]]

## Nexus
The prosperous city for all elements, player sees the treaty and understand world structure.

> Characters: [[Player]]
> Items: 
> Events: [[A Grandiose City around the Treaty]]

## History of the Treaty

## Skyria

## 
