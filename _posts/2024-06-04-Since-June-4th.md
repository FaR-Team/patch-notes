# Since June 4th

## FARMOXEL
+ The clock is not scene-dependant anymore
+ The bed no longer handles ending and starting the day; this is now managed by a `SleepHandler`. The bed only interacts with the `SleepHandler` and attempts to end the day, allowing the handler to always exist and be called from anywhere.
+ Adjusted all references to the bed to point to the `SleepHandler` (currently, the component is located in the `GameManager`).
+ The `SleepHandler` checks if it's 2 AM or 6 AM to sleep or wake up, using the functions `FinishDay` and `StartDay`. If it's 2 AM and you're already sleeping, it skips.
+ The bed had many references to components, objects, and dependencies; now, several of these are events triggered when sleeping or waking up.
+ Now the game saved after sleeping.
+ Cleaned up some debugging code.
+ Fixed the bug that caused carrots to duplicate when loading.
+ Fixed bugs left from last week.
+ Fixed weird lines on shader when reloading the scene.
+ Fixed shader's shadows.
+ Fixed chest slots not showing.
+ Fixed chests duplicating on load.
+ Fixed sun misplacement when changing scenes.
+ Fixed a bug that caused you to not be able to plow when reloading scenes.
+ Fixed commands losing references.
+ Fixed a few issues with the `ClockManager` and several object references in the scene.
+ Fixed a bug that allowed you to leave items on blocked slots.
+ Fixed an error when teleporting from one scene to another.
+ Fixed a bug that caused the user to plant two trees at once.
+ Fixed the save and load of each scene's last datetime.
+ Changed player's starting gold.
+ Added `GameStateData`,`GameStateLoader`, and `GameStateSaver`.
+ Added catching up when the player has slept for multiple days without going to the farm.
+ Added a command to delete the saves.
+ Added post-processing (Bloom, vignette, DoF).
+ Added stars at night time.
+ Added a fully functional farm map.
+ Added a functional skill tree, for now it's accessed with H.
+ Added a (Demo-use-only) skill fruit.
+ Added a new kind of item: Special.
+ Added soundclips to Items.
+ Added a debug menu.
+ Added global lighting to the water shader.
+ Added the new chest model + its animations.
+ Added back the date to the clock.
+ Added a command for testers to export their logs and saves.
+ Added F1 to toggle the UI.
+ Added F2 to take screenshots.
+ Imported a couple of models.
+ Reorganized some folders and added a new song.
+ Improved some aspects of the `MusicManager` so that when we use it properly, it works better, as well as the volume slider (I think it works better since it’s somewhat logarithmic, but I didn’t notice much difference lol).
+ Improved skill tree (Now it's actually tree-like), made it easier to set up.
+ Improved the lighting system.
+ Improved the shader to tint depending on the light.
+ Improved chest animation timing.
+ Improved the weather system, now each season has its own possible weathers.
+ Improved player location handling for scene transitions.
+ Improved player's gravity. (They were defying it.)
+ Updated discord logging.
+ Remade part of the saveload system.
+ Remade the Options Menu's backend.
+ Remade the Outline implementation, now it's tied to our shader.
+ Replaced the housse's model.

## ROOM MAKERS
+ Corrected doors price location.
+ Translated the game to spanish.
+ Improved the startup screen.
+ Startup parity.
+ Reduced the timer to half.
+ Added a reminder for players that don't read the tutorial.
+ Added a "Coming soon on google play" sign to the main menu. (Hand made by our best programmer, ofc, pinky promise i'm not biased)
+ Added flicking when there's only 30 seconds left in the timer.
+ Fixed the location of the combo popup.
+ Fixed a bug where the Coming soon sign would appear over the controls.
+ Fixed a bug where all the top items duplicated endlessly.
+ Fixed a bug where combo items would duplicate if done in rooms that aren't the main one.
+ Fixed a bug where the timer would become invisible when resetting it.
+ Fixed a bug where the combo star would not appear on items that already were part of a combo.
+ Fixed bug where you could use the same object multiple times in combos.
+ Fixed a bug mid-event, where the game would soft-lock if the player triggered the tutorial reminder while in edit mode.