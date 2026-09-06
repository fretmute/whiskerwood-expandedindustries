## Changelog

### 0.1.1.0
Renamed configuration files. Numbered versioning did not work out as I had hoped, since Steam still overwrites everything, and will remove old files that you don't include in the release. Manual backups is still the required way, and this is probably less confusing.

Added two new columns to my recipes that were evidently added in this patch and I didn't notice because of the nature of my PSV to table injector. My custom recipes are now consistent with the vanilla ones.

### 0.1.0.0
Renamed from `IndustryRecipes` to `ExpandedIndustries`.
Added option to mod settings to enable/disable tech unlock requirement for custom recipes.
This is the first release available on the Steam workshop.

### 0.0.5.0
Added new icons for new intermediate resources: charcoal and sea salt.
Removed table salt recipe from Sifter. Sifter now produces sea salt.
Removed potash recipe from sifter. I feel the guano ships fill this niche in a better way.
Added sea salt to table salt recipe at the chemist.
Removed wood to coal recipe at the charcoal furnace. It now produces charcoal instead.
Added charcoal to fuel recipe at the charcoal furnace. Overall it's 3x more efficient for wood than wood to fuel.
Gated all custom recipes behind technologies.
Added vanilla data to `GridActors.txt` and `IndustryRecipes.txt` to make it more accessible for folks to edit them.

### 0.0.4.2
Added missing `recipe.guanofertilizer` to `GridActors.txt`.

### 0.0.4.1
Minor change to properly detect mod options in the event that they have never been toggled.

### 0.0.4.0
Added custom research tasks for all of the custom recipes. Should you happen to upgrade and your save has an industry currently producing a recipe that became locked, that industry will continue to produce that resource, but shoud it be changed, you won't be able to switch back until the research is complete.

Changed GridActors.txt such that it only writes data necessary for the implementation of this mod, rather than entire GridActor objects.

### 0.0.3.0
Added one dumb execution wire that was missing and preventing mod options from being registered.

### 0.0.2.0
Removed inadvertent Fretlib dependency. 

### 0.0.1.0
Initial pre-release. 