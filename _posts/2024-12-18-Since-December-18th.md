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
+ Fixed a bug where the apples would fall through the ground.
+ Fixed the grid ghost disappearing instead of turning red when you couldn't place something.
+ Fixed mass selling with control.
+ Fixed the name display for tools.
+ Fixed carrot animations.
+ Fixed a bug that caused "bluetooth" watering of crops.
+ Added a catch up for the sell system.
+ Added a command to make the tick rate configurable.
+ Added functionality for crops to die and rot.
+ Added a multiply texture to the shader to use when the crops rot.
+ Added a loading screen.
+ Added Apple Tree Models.
+ Added Water Bucket Model.
+ Added Hoe Model.
+ Added an animation for harvesting the apple tree.
+ Added an animation for the "Tree Harvesting Basket" and implemented it with the tree's animation.
+ Added an animation for when the dirt is initially plowed.
+ Added the Hoe's animation when using the hoe.
+ Added a collider to the carrot's sell box.
+ Added a submenu in options for audio sliders.
+ Added idle animation for the Beet.
+ Added functionality on our logger, now we can individually toggle the logs of each script using the in-game console.
+ Added an in-game file manager from github to replace an issue caused by EditorUtility (https://github.com/yasirkula/UnitySimpleFileBrowser)
+ Added saving for the "Player Stats" (This includes most of the data from the skill tree).
+ Refactored scene loading to use a loading manager.
+ Refactored the sell system.
+ Refactored the sound system.
+ Changed the water shader a bunch.
+ Changed the compression of the project to avoid weird looking models.
+ Changed how the shovel works, now you can actually get rid of dirt by using it.
+ Modified HurryPotter command.
+ Modified DeleteSavve Command.
+ Modified the debug menu interface.
+ Updated House's Texture and Model.
+ Updated Beet's textures.
+ Updated the interactor, now you interact with right click.
+ Updated how the sensitivity workd, now using whole numbers in the UI.
+ We made an editor extension to make the process of adding new crops easier, altho it still needs further work to be fully automated.
+ Now the Gold UI updates using an event.
+ Moved a bit the house's spawn points.
+ Removed popibrine.

## Room Makers

+ Added the tag system, together with little icon indicators for the current room's tag.
+ Added the labeler, an item to change the current room's tag, together with its UI.
+ Added a sledgehammer, used to destroy and open locked doors
+ Added some feedback for the minimap. ("Map" text at the side, as placeholder, and blinking to the current room).
+ Added a popup that says Room Match! when you match the room's tag.
+ Added shops!
+ Added the ability to only place certain items next to walls.
+ Added a debug menu for the testing phase.
+ Added around 20 new items!
+ Added 3x1 furnitures to the system.
+ Added a "music tension" system.
+ Added the ability to place a little piece of tape over the speaker, muffling the sound.
+ Changed the gameplay music! Now we have three tracks that can loop up to three times each!
+ Balanced room's prices.
+ Balanced scoring in general.
+ Gym furniture set.
+ Fixed a transition bug.
+ Fixed a tutorial UI bug, there was an incorrect exclamation sign.
+ Fixed the probabilities of the 1%.
+ Fixed a bug occasionated by using the labeler in the shop.
+ Fixed the shop's rug colission.
+ Fixed a bug where the furniture would change languages when picking it back up.
+ Fixed a movement animation bug, the player would keep walking when you were in edit mode in some occasions.
+ Localization depending on the device's language.
+ Now objects shake a bit when you can't place them.
+ You can now put multiple top objects over a single Bottom object.
+ We made a tool to import and export the objects list as a csv for easier modifying.
+ We made a tool to create new furnitures easily.
+ We made an entire devtool webfront with:
  + An editor for the objects list, and their specifics (Price, Name, etc).
  + An editor for the probabilities per tag, also using an csv file.
  + A tool to create and edit 4-color palettes.
+ Revamped the spawn system, now using probabilities per tag.
+ Redone how the items work, an entire under the hood change.
