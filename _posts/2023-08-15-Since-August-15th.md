## FARMOXEL
+ Replaced placeholder trash bin model for a lower quality placeholder that won't burn our CPU.
+ Added a placeholder pickup sound.
+ Added a Weather system.
+ Added a fullscreen toggle.
+ Added a resolution dropdown.
+ Replaced old apple model  (Last growth stage).
+ Added first growth stage model for the apple.
+ Added mouse Shortcuts:
        +Click derecho: Dividir a la mitad el Stack que está en el slot.
        +Si apretás click derecho con un item en el mouse, dejás un objeto en el slot. 
        +Shift + click derecho transfiere el item sobre el que estás al cofre y viceversa.
        +Apretar del 1 al 0 sobre un item lo transfiere al respectivo slot de la hotbar.
+ Now crops get watered when it rains.
+ Now you can't plow dirt nor plant in a 3x3 grid below the tree.
+ Made a bunch of improvements performance-wise:
    + Updated to URP (and rewrote shaders)
    + Updated the map to use chunks instead of individual tiles, lowering the amount of gameobjects in scene.
+ Fixed a bug where you could see through cliffs.
+ Finished reworking the Save-Load system! Now;
    + Dirts Save & Load.
   + Tubers Save & Load.
    + Player inventory and Chest inventories Save & Load.
+ Finished the dialogue system!
+ Positioned strawberry's spawnpoints.
+ Updated Discord's Rich presence to show the actual build of the game.
+ Fixed the game's shader.
+ Fixed bug where the dialogue skipped instead of autocompleting when pressing a key.
+ Fixed a weird sensitivity bug.
+ Fixed bug where strawberrys couldn't be harvested on a build.
+ Fixed a bug where all harvested crops looked like your mom. (I mean, hoes.)
+ Fixed a pickup sound related bug.
+ Fixed "Al dividir un objeto por la mitad dentro del inventario (apretando shift) sin hacer click en el objeto antes, una de las mitades desaparece a menos que se vuleva a hacer click en el grupo de objetos."

## ROOM MAKERS

+ Changed all input to the new input system.
+ Changed the font, and made it pixel perfect.
+ Math stuff. something about local and global position.
+ Updated the combo UI.
+ Made a functional mobile version.
+ Worked through the hassle of making an UI for the mobile version.
+ Slightly moved the clock one pixel upwards.
+ Changed the font to one that adapts better to the game boys' style.
+ Added an error logger that automatically sends a webhook to our discord.
+ Added a version indicator on screen. (For testing)
+ Added vibration to the controls.
+ Added an icon to identify top objects that have been on a comb