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
- [[Starting Cutscene]]

%% End Waypoint %%

## Background Story
played at the start of the game.

> Characters: [[Dev]], [[Player]]
> Items: 
> Events: [[Starting Cutscene]]

## Exploring Starting Chunk
Encounter Bot

> Characters: [[Player]], [[Bot]]
> Items: [[Basic Tools]]
> Events: [[Bot Encounter]], [[Chopping Wood]]

## Unlocking New Chunks
Dev return, added new chunks


## Combat Chunk
Gives player the belt, introducing to [[Health]] and [[Stamina]]