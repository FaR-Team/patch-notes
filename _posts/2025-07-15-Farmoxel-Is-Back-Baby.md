# Farmoxel's back, baby!

### Farmoxel - Since 15th July 2025

#### New Features & Content

+ Added a fishing minigame. :D
+ Added the spear's model.
+ Added the perch's model.
+ Added the fertilizer's model.
+ Added the fertilizer as a concept.
+ Added particles with physics to the fertilizer.
+ Added the Storage House's model.
+ Added the Storage Table's model.
+ Added the Storage Rack's model.
+ Added a multi-cell "Footprint" system (Basically grid size).
+ Added a debris spawn system.
+ Added per category weight for the spawn of debris.
+ Added rules to the debris' spawn system.
+ Added 10 debris models!
+ Added debris to the savesystem.
+ Added the possibility for debris to spawn when days pass by.
+ Added a selection tile when using the shovel.
+ Added a cute voxel explosion FX when using the shovel.
+ Added SFX to the chest.
+ Added the ability to rotate items held with telekinesis.
+ Added a new type of item that spanws an object in the world.
+ Now particles fall from the fertilizer depending on how you handle it with the telekinesis.
+ Now the fertilizer actually fertilizes the dirt if we throw particles over them.

#### Visuals, Shaders & Performance

+ Fixed a bug with the shader's vertical shadows, causing something called "Shadow Acne".
+ Fixed double sampling of the shadow cast in the shader.
+ Fixed the multiply texture's unused calculation.
+ Fixed a shadow misalignment bug in the tiny chunk path.
+ Changed all the dirt's textures.
+ Changed selling boxes models.
+ Changed all the animations to use FBX instead of .Blend to remove blender dependency. (And better linux compatibility)
+ Reworked the implementation of the models on hand.
+ Added pixel perfect shadows to our shader.
+ Added multi-compile instancing.
+ Now static objects don't cast shadows. (The map, for now)
+ Made some improvements to the game's day-night lighting calculation and overall sun arc.
+ Combined the meshes of each section of the map to heavily improve performance.
+ Updated the water's shader, and made it look more in line to our main shader, it still has a long way to go though.
+ Updated the game's icon.
+ Updated the shader's Cbuffer calculations.
+ Updated some placeholder materials.
+ Updated the lightning.
+ Updated the shovel's model.
+ Updated the shader with some improvements and additions.
+ Updated the outline to better fit the initial vision.
+ Updated the position of the chest and the cart.

#### UI, Controls & QoL

+ Changed the shopkeeper's item list from a scroll view to a page view.
+ Changed the functionality of the accept and reject buttons in the shopkeeper's UI.
+ Reworked the pause menu with new assets.
+ Now the multipliers (x5, x10) are accessible via shift and control respectively.
+ Now the game's UI disappears when you open the shop.
+ Now the character movement and camera locks when using a tool.
+ Now you can press esc while rebinding to cancel the rebind.
+ Now you can use the cart on slopes.
+ Deleted some unnecessary text from the cart's total.
+ Added some visual feedback for when you don't have enough money to buy what's in your shopping cart.
+ Added an inventory button to the Shopkeeper's UI.
+ Added display options.
+ Added a reset default bindings option.
+ Added a Mute on Background option.
+ Added sprites for the tools. (Hoe, Shovel & Bucket).
+ Added a carousel animation for the tool's hotbar.
+ Updated the hotbar's sprites.
+ Updated some player's controller settings.
+ Updated the third person camera (minigames).
+ Some spear and fishing minigame improvements.

#### DevTools & Systems

+ Reworked item's use implementation to be polymorphic.
+ Revamped the telekinesis' physics.
+ Completely remade the map's collisions.
+ Added a new devUtil developed by one of our ex members: Vlyx's notes - They are quite literally notes on the unity editor.
+ Added two new devUtils: FaR-Folders and FaR-Hierarchy.
+ Now the player is a prefab (About time).
+ Updated the debug console's commands to use names instead of ints.
+ Updated the range of the telekinesis ray.
+ Updated the entire system behind the grid and the grid ghost.
+ Updated the storage house's collision to an optimized one.
+ Updated the dirt detection.

#### Bug Fixes

+ Fixed the farm's door collision.
+ Fixed a bug that caused trees to deactivate once they grew a little.
+ Fixed a bug where the outline created a black line on the ground. (NOt really, old me, you just avoided it, it's still an issue...)
+ Fixed a bug where... There were two maps, just like, the entire farm was duplicated, for no real reason.
+ Fixed the shopkeeper's UI sizing.
+ Fixed the player's gold positioning on the shopkeeper's UI.
+ Fixed a visual bug on the multiplier buttons.
+ Fixed a bug where crops had a prompt UI when they shouldn't.
+ Fixed a bug where tree's rotation wouldn't stay when reloading the scene.
+ Fixed a bug where the shovel didn't cast a shadow (And replaced the placeholder model)
+ Fixed a bug where the hoe would animate and consume energy even when you weren't able to plow.
+ Fixed a weird rain bug where the droplets wouldn't render on some parts of the farm.
+ Fixed a bug where shift clicking an item in the hotbar wouldn't send it to the inventory.
+ Fixed a bug where you couldn't esc out of the binding menu.
+ Fixed the resolution drop-down not working.
+ Fixed the positioning of the house's model.
+ Fixed diagonal movement not being normalized.
+ Fixed the grid being misplaced (it had a 0.5 offset on both X and Z).
+ Fixed the underwater cliff's having collisions.
+ Fixed trees ignoring debris when spawning.
+ Fixed the [Big Mean Bug](http://blog.farteam.com.ar/2023/05/15/May-15th-The-big-mean-bug-update!.html) again!
+ Fixed the sun rotation.
+ Fixed a display bug with the gold.
+ Fixed the beet's sellbox sign position.
+ Fixed tools slot sprite not updating when using a joystick.
+ Fixed gridghost's position on screen by centering it using the screen size, and not the mouse.
+ Fixed a bug where the dirt wouldn't unregister from the grid when harvesting.
+ Fixed a bug where the fertilizer would randomly rotate and move on its own when dropped on the ground with a non-flat angle.