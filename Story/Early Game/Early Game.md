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
- [[Background Story]]
- [[Chunk Exploration]]
- [[Exploring Starting Chunk]]
- [[Unlocking New Chunks]]

%% End Waypoint %%

## Main Quest
- [[Background Story]]: Played at the start of the game.
- [[Exploring Starting Chunk]]: Encounter Bot, introduce potion and item wheel, chop wood.
- [[Unlocking New Chunks]]: Dev return, added new chunks, introduce to inventory, chunk unlocking, and tool wheel.
- [[Chunk Exploration]]: Player is allowed to explore combat, mining, farming, and fishing chunks.

## Side Quest
