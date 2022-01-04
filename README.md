# What is this project?

This project aims to port existing Minecraft mods (forge or fabric) to [MineClone2](https://git.minetest.land/MineClone2/MineClone2)

## Mod development process

Then someone wants to work on porting a minecraft mod or suggest it, a new issue should be created on [mineclone2-mods/mods-requests](https://github.com/mineclone2-mods/mods-requests/issues).
An organisation member should now check if the request is valid, decide for a priority and add it the the [Management Project](https://github.com/orgs/mineclone2-mods/projects/2).

Then commes the discussion part about the design and to find people interested into working on it.

Then a developper wants to be the manager of a mod development, he should assigned to the respective issue and given complete write access to a brand new repo generated from the [template](https://github.com/mineclone2-mods/template-mod).

The template will improve modder's life as it provides:
- luacheck code checking with GitHub actions
- automatic image optimisation using ImgBot

Developpers with write access should work on branches in order to prevent any breakage.

A [ContentDB](https://content.minetest.net/) package should then be created by an admin on an [organisation account](https://content.minetest.net/users/mineclone2-mods/), with automatic releases (webhooks).
The project maintainer should be added as maintainer on the package.

All original mod authors should be referenced in each mod's README.

Code style should fit [MineClone2 codestyle](https://git.minetest.land/MineClone2/MineClone2/src/branch/master/CONTRIBUTING.md#stick-to-our-guidelines).

All code should be licenced under GPLv3 or later, but multi-licencing is fine if you take some perts of existing Minetest mods. 
