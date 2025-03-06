# Since December 18th

## FARMOXEL
+ Fixed a weird issue caused by the new outline, that made every backface have it alpha replaced by the outline color.
+ Fixed a bug where the user could subtract items they didn't have in the basket from the basket, giving them a negative "bonus" of cash to use.
+ Fixed the explosion's materials.
+ Fixed a bug that caused the game not to recognize a change of day if the user blacked out.
+ Fixed a bug that caused dirt overlapping.
+ Fixed a bug where plants wouldn't save and load their dead state properly.
+ Fixed a bug where it subtracted items without selling them.
+ Fixed a bug on the apple's OnEnable.
+ Fixed a bug where you could still harvest the apples and carrot when they were dead.
+ Fixed a bug where using the multiplier while buying it would add the items no problem, but only remove 1, while removing the correct amount of money.
+ Fixed a bug where the game could add items to locked slots in your backpack.
+ Fixed a bug where the player's inventory would override itself internally when coming back to the main scene, causing several issues.
+ Fixed the grid ghost disappearing instead of turning red when you couldn't place something.
+ Fixed mass selling with control.
+ Fixed the name display for tools.
+ Fixed carrot animations.
+ Added a catch up for the sell system.
+ Added a command to make the tick rate configurable.
+ Added functionality for crops to die and rot.
+ Added a multiply texture to the shader to use when the crops rot.
+ Added a loading screen.
- Added Apple Tree Models.
+ Added a collider to the carrot's sell box.
+ Added functionality on our logger, now we can individually toggle the logs of each script using the in-game console.
+ Added an in-game file manager from github to replace an issue caused by EditorUtility (https://github.com/yasirkula/UnitySimpleFileBrowser)
+ Refactored scene loading to use a loading manager.
+ Refactored the sell system.
+ Changed the water shader a bunch.
- Modified HurryPotter command.
- Modified DeleteSavve Command.
- Updated House's Texture and Model.
+ We made an editor extension to make the process of adding new crops easier, altho it still needs further work to be fully automated.
+ Now the Gold UI updates using an event.
+ Moved a bit the house's spawn points.
+ Removed popibrine.
