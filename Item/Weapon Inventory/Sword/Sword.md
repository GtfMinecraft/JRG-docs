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
- [[Ancestral Katana]]
- [[Blade of Air]]
- [[Blade of Dark]]
- [[Blade of Earth]]
- [[Blade of Element]]
- [[Blade of Eternal Legacy]]
- [[Blade of Fire]]
- [[Blade of Water]]
- [[Celestial Blessing]]
- [[Description]]
- [[Enhanced Sword]]
- [[Fractured Sword]]
- [[Refined Sword]]

%% End Waypoint %%

