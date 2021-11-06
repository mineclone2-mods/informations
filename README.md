# What is this project?

This project aims to port existing Minecraft mods (forge or fabric) to [MineClone2](https://git.minetest.land/MineClone2/MineClone2)

## Mod development process

Then someone wants to work on porting a minecraft mod or suggest it, a new issue should be created on [mineclone2-mods/mods-requests](https://github.com/mineclone2-mods/mods-requests/issues), in order to discuss about initial design and to find people interested into working on it.

After discution, some developpers should be assigned to the mod and given complete write access to a brand new repo generated from the [template](https://github.com/mineclone2-mods/template-mod).

The template will improve modder's life as it provides:
- luacheck code checking with GitHub actions
- automatic image optimisation using ImgBot

Developpers with write access should work on branches in order to prevent any breakage.

The mod should be released automatically to [ContentDB](https://content.minetest.net/) using webhooks to an organisation account, as soon as the mod provide enough stuff to be intresting. The 1.0 version number should not be given to the mod until all features are succesfully ported.

All original mod authors should be referenced in each mod's README.

Code style should fit [MineClone2 codestyle](https://git.minetest.land/MineClone2/MineClone2/src/branch/master/CONTRIBUTING.md#stick-to-our-guidelines).

All code should be licenced under GPLv3, but multi-licencing is fine if you take some perts of existing Minetest mods. 
