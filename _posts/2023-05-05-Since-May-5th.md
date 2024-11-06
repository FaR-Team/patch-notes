## FARMOXEL
+ Replaced some flawed models
+ Blocked the hotbar scroll for a couple of seconds after moving an object with telekinesis to avoid janky controls
+ Updated several textures to fit more the final game's art style
+ Now you can harvest in area!
+ Added a water bucket!
+ When watered, dirt will chage it's color
+ Added a new inventory system that will allow us to expand it in the future.
+ fixed bug where you could harvest different crops in area
+ fixed bug where dirt's ghost appeared over already placed dirts
+ Completely remade player's controller.
+ Added some dev commands:
    + SetAreaHarvestLevel: In the final game, you will be able to level up ypur abilities, as of now, the skill tree is your parents in disguise, so, we need this to test out the feature.
    + GivePants: Your character is naked, sorry to give the news like this.
    + GiveShirt: Actually, both of this commands give the player an expansion of the inventory, and, in the final game, they will be some sort of clothing item you'll have to buy.
+ Fixed an error that caused game's input to stop working completely, remaking GameInput's script to not depend on an object in scene, making it just a class to be called/accessed by other scripts.
+ Fixed lots of bugs related to changing the character controller to a new one:
+ Added the ability to move the selected hotbar with the upper triggers of a gamepad.
+ Added the ability to look around with a gamepad (Thanks to the remade controller).
+ Added random rotation when planting crops.
+ Now you can hold to plow and plant!
+ Changed bed's placeholder model to the final one!
+ Fixed bug where the interaction key wouldn't register.
+ Fixed tree's GridGhost.
+ Fixed trees (Yes, we broke them, let us be.)
+ Fixed bug where your camera started moving like crazy after deactivating noclip, our tester called it "Drunk Camera".
+ Fixed Wet Dirt Model.
+ Splitted Dirt in the Dirt class and DirtHarvest class.
+ Energy variables now are Static.
+ TimeManager variables now are Static
+ Added base class for tubers, trees, bushs.
+ Refactorized apples and strawberry bush.
+ Añadí el sistema de pooling para las dirts.
+ Added an ability hotbar, now you have to hold cntrl and scroll in the eleventh slot to change the tool you're using, instead of picking it up from the ground, and wasting precious crop-related space.
+ Finished the node+ based Dialogue System, the only remaining part is to make it usable in+ game (Like, showing the text and stuff, this is hard, let me be.)
+ Changed GridGhost's color and texture
+ Changed Energy's inner-workings.
+ Changed TimeManager's inner-working, making crop's growth non-update-dependant!
+ Improved greatly most of Crop's Growth scripts.
+ Added a variable for ToolItemData to know it's own energy usage.
+ Added a command called "imsleepy", that speeds up time until you can sleep.
+ Updated Ability's Hotbar to work with gamepad.
+ Fixed Hotbar's Slot width and height.
+ Fixed regrow and strawberry's growth to make it wait a while before instanciating the fruits.
+ Fixed a bug that caused the scroll wheel not to function after buying something.
+ Fixed trees (Yes, again.)
+ Fixed a bug where you could plow over trees.
+ Modified commands:
         +HurryPotter now also makes dirts switch to "Testing" mode, making it so you don't need to water them while it's active.
+ You can now water crops!
+ Lots of backend stuff regarding bushes and trees.
+ Now bushes drop their fruits on the ground when they are harvested.
+ Now trees drop their fruits on the ground when they are harvested.
+ Now gridghost turns red while hovering over a tree.
+ Replaced all of the strawberry's models.
+ Fixed Carrot's explosion.
+ Fixed a bug that caused strawberrrys to implode.
+ Fixed dirt's invisibility
+ Fixed tree's interaction. (AGAIN)
+ Removed Herobrine.