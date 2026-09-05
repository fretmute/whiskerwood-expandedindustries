# Expanded Industries
A mod for customizing industry recipes and production.

## Overview

- Provides the ability to add or edit industry recipes.
- Provides the ability to add or edit recipes available at each industry.
- Provides the ability to add or edit tech unlocks.
- Edit files in `<YourSteamDirectory>\steamapps\workshop\content\2489330\3796266373` to customize.
  - Note: Use `FileConfig,txt` to specify custom file names for config files. Config file names are versioned by default, so any future changes will create new files, and you can merge edits from your previous files or configure it to ignore the new ones altogether.

  - You can specify alternate filenames for configuration files on a per file basis.
  - `FileConfig.txt` itself will still revert after updates, so be aware that future patches may require some intervention.

## Current Recipes
```
| Industry         | Input                         | Output       | Unlocks With             |  
| ---------------- | ----------------------------- | ------------ | ------------------------ |
| Bakery           | 2 Flour, 1 Fuel, 1 Table Salt | 5 Hardtack   | Custom research          |
| Charcoal Furnace | 2 Logs                        | 1 charcoal   | Custom research          |
| Charcoal Furnace | 1 Charcoal                    | 9 fuel       | Custom research          |
| Sifting Tower    | 52 Water                      | 2 Sea Salt   | Custom research          |
| Chemist          | 3 Sea Salt                    | 2 Table Salt | Custom research          |
```

## Settings
- Note that there is a setting to enable or disable the mod completely. This setting requires a restart to change.
- The other setting governs whether the custom recipes included with this distribution are gated behind research or not. Should you create your own custom recipes, note that this setting only affect them if the associated tech unlock name starts with [code]expandedindustries.unlock.[/code]

## Known Issues
- Should an industry from a save be producing a recipe that is no longer available due to an edit or update, that building may become soft locked to a blank recipe. The only recourse is to demolish the building and recreate it. Be careful about removing recipes.