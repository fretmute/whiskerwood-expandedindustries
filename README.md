# Expanded Industries
A mod for customizing industry recipes and production.

## Overview

- Provides the ability to add or edit industry recipes.
- Provides the ability to add or edit recipes available at each industry.
- Provides the ability to add or edit tech unlocks.
- Edit files in `<YourSteamDirectory>\steamapps\workshop\content\2489330\3796266373` to customize.
  - Note: Use `FileConfig.txt` to specify custom file names for config files. Config file names are versioned by default, so any future changes will create new files, and you can merge edits from your previous files or configure it to ignore the new ones altogether.

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


# 工业扩展
一个用于自定义工业配方和产出的模组。

## 概述

- 提供添加或编辑工业配方的功能。
- 提供添加或编辑各种工厂内可用配方的功能。
- 提供添加或编辑科技锁的功能。
- 编辑 `<你的Steam路径>\steamapps\workshop\content\2489330\3796266373` 处的文件以进行自定义。
  - 注意：本模组使用 `FileConfig.txt` 来为配置文件指定自定义文件的文件名。配置文件的文件名默认包含版本控制，即任何未来的模组更新都会创建新的文件，所以你可以把之前编辑好的文件合并进来，或者用完全忽略新文件的方式来配置。

  - 你可以为每个配置文件指定备用文件名。
  - 每次模组更新后，`FileConfig.txt` 本身会恢复原状，所以请注意，未来的每次版本发布后都可能需要进行一些干预。
 
## 当前增加的配方

```
丨工厂　　丨输入　　　　　　　　　丨输出　　　丨解锁自　　　　丨
丨－－－－｜－－－－－－－－－－－｜－－－－－｜－－－－－－－｜
｜烘焙坊　｜２面粉，１燃料，１食盐｜５压缩饼干｜自定义研究　　｜
｜木炭炉　｜２原木　　　　　　　　｜１木炭　　｜自定义研究　　｜
｜木炭炉　｜１木炭　　　　　　　　｜９燃料　　｜自定义研究　　｜
｜筛分塔　｜５２管道用水　　　　　｜２海盐　　｜自定义研究　　｜
｜化工作坊｜３海盐　　　　　　　　｜２食盐　　｜自定义研究　　｜
```

## 设置
- 请注意有一个完全启用或禁用本模组的设置。这项设置需要重启游戏来生效。
- 另一个设置决定了当前装入游戏的配方是否受研究限制。如果你创建了自己的自定义配方，请注意，只有当这些配方的“科技解锁名称”以[code]expandedindustries.unlock.[/code]开头时，此设置才会对其生效。

 ## 已知
- 如果某存档中的一个工厂正在处理已经不可用的配方（由于编辑或更新），则该建筑会软锁定在一个空白的配方上。唯一的办法就是拆除这座建筑并重建。请小心地移除配方。
