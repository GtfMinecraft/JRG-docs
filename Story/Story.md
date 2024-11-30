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
- **[[Early Game]]**
- **[[End Game]]**
- **[[Middle Game]]**
- **[[Story thoughts]]**
	- [[Elements' Territory]]
	- [[Outline]]
	- [[The War]]

%% End Waypoint %%

## Summary
#### [[Early Game]] (introduction to the game)
- Background story
- Gameplay mechanics
- Simple objective?
- Dev trust
- Introduce element world (big map)

#### [[Middle Game]] (element world exploration)
- Explore big map
- Stories with elements
- Upgrading tools
- Learning skills  

#### [[End Game]] (plot revelation and twist)
- Introduce wither
- Destroy other elements
- Bug culprit
- Sacrifice?