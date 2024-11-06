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
- [[Bot Encounter]]
- [[Chopping Wood]]
- [[Dev Return]]
- [[Starting Cutscene]]

%% End Waypoint %%

## Background Story
Played at the start of the game.

> Characters: [[Dev]], [[Player]]
> Items: 
> Events: [[Starting Cutscene]]

## Exploring Starting Chunk
Encounter Bot, introduce potion and item wheel, chop wood

> Characters: [[Player]], [[Bot]]
> Items: [[Basic Tools]]
> Events: [[Bot Encounter]], [[Chopping Wood]]

## Unlocking New Chunks
Dev return, added new chunks, introduce to inventory, chunk unlocking, and tool wheel 

> Characters: [[Player]], [[Dev]], [[Bot]]
> Items: [[Ring]]
> Events: [[Dev Return]]

## Combat Chunk
Give player the belt, introduce to [[Health]] and [[Stamina]]

> Characters:
> Items:
> Events:

## Mining Chunk
mine

## Farming Chunk
farm

## Fishing Chunk
fish

