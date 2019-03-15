# Group Inventory - Customized Roll20 5e OGL Sheet
Custom edits to roll20's 5e OGL character sheet - includes "group inventory" setup.

![](https://i.imgur.com/27gRUIS.png)

![](https://i.imgur.com/1Y9zDZv.png)

Credit to the original creators of the 5e OGL sheet for roll20, their work made it possible to do this...

## Important Info
I'm locking this build to OGL's **2.7** because I wanted to make sure that the functionality is working properly and without any bugs before I commited it to the main branch. And also because I kind of want this to be a separate endeavour. I really respect the work that's being done to the 5e OGL sheet, but I find a lot of the features a little cumbersome. I also wanted to re-organize a lot of the features and add in even more options to give GMs the power to customize their game to some common homebrew rules; chief among them, double damage crit die.

## Installation
Simply edit the character sheet code on your roll20 campaign's settings and drop the relevant code from each of the files in this repo into the boxes.

index.html -> HTML tab  
sheet.css -> CSS tab  
en.json -> Translation tab  

Save, and you're done.

**NOTE:** Remember that if you were letting the character sheet decide which of your compendiums are shared on the game, you will need to manually set this to the relevant compendium.

## Using Group Inventory
When you wish to create a group inventory, create a new character as you would normally and give your player(s) access to the sheet like you would a PC. Under the General Options (cog on the character sheet) select "INV" next to the NPC toggle to switch the view to a full-page inventory.

Done.

For all intents and purposes, this sheet is a PC like your players, but the INV option removes all unnecessary facets to the character sheet and lets you view the inventory without the rest of the page cluttering up your limited screen-space.

* Compenidum Drag-and-Drop compatible
* Carry capacity as per usual - character's strength will be defaulted to 10. Raise STR score if you want to have an upper limit (cart horses, mules, etc)
* Currency now spread along the top for easier view

### TODO:
* Styling
* Weight limit customization
* Size restrictions (with images)
* "Bag of Holding" setting (removes weight limitations, etc.)
