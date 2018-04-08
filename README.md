# Discord Action Bars

Create customized button bars. This project was abandoned after Vanilla.

## Installation

Although functionally one AddOn, Discord Action Bars technically is a collection of three separate AddOns:

* DiscordActionBars
* DiscordActionBarsOptions
* DiscordLibrary

To install, copy each of the three directories listed above to your _Interface/AddOns_ folder.

## Original Notes

Discord Action Bars gives you 10 hotbars and 120 buttons to play with. It also hides the default interface art. Here's some of what you can do with the bars:

* Drag a bar to where you want it.
* Set the number of buttons per bar
* Set the number of rows in which to display the buttons
* Set the amount of space between each button on the bar
* Set the size of each button on the bar
* Set the transparency of the bar
* Configure a background behind and border around the bar
* Lock buttons to prevent you accidentally dragging actions off them
* Hide empty buttons
* Define a default target to use when you have no target and click a button
* Define other actions to use when right-click or middle-click a button
* Collapse the bar to the left to fill in empty buttons
* Configure the shapeshift bar, bag bar, pet bar, and micro bar
* Set the colors for out of range, not enough mana, and unsuable displays
* Define bars to be shown when you switch into a certain stance/aura/stealth/animal form. Define a main bar to have those bars switch with it when you change forms.
* Set bars to display when you're in combat, you're not in combat, you have friendly target, you have a hostile target, you're holding down a key you defined, or you move the mouse over where the bar is hiding.
* Define macros to be run in response to game events. These macros do not use any of your base 18 macros and have a limit of 7500 characters.
* Configure control boxes that you can click or mouseover to show/hide bars. They can be used to build a menu that controls bar display and doesn't use any of your macros.
* Configure solo buttons (referred to as 'floaters') that aren't attached to any bar.

### Important 

1. This mod _does not use the default UI's keybindings_ for the action bars. Scroll down in the keybindings menu until you see the _Discord Action Bars_ header. Beneath that is where you set your keybindings. The pet and shapeshift bars still use the default keybindings.
2. Do not set the _Use For Shapeshift Form_ option on the Main Bar to any form. Why did you think the mod was spamming a warning at you when you tried to do so?
3. Discord Action Bars is not compatible with _CT_BarMod_ or _CT_BottomBar_. CT_BarMod is the mod making your pet/shapeshift bar disappear and probably the one causing your bag bar to display empty buttons. CT_BottomBar is the mod causing the default UI's art to pop back up when you zone. Either one of them can causes crashes when used with this mod.
4. Setting up bars that switch when you shapeshift. It's easy. There's a section in the readme devoted to it. For those too lazy to read the readme, here it is again simplified somewhat:
    1. Misc Options -> Main Bar For Shapeshifting -> choose a bar number
    2. Go to that bar's options. Set its appearance options and place it where you want it on-screen. All bars that switch with this bar will use those appearance options and be placed there.
        * If you're a warrior, go to Num Buttons and remove all but 1 button from the bar you set as the Main Bar.
    3. Press ESC. Click Key Bindings. Scroll down until you see the Discord Action Bars header. Scroll down to the BUTTON KEYBINDINGS header. Find the bar you set as the Main Bar. Set its keybindings. All bars that switch with the main bar will use those keybindings.
    4. Choose another bar. Set the Use For Shapeshift Form option to the animal form / stance / stealth you want this bar to use. Set the When I Shapeshift option to Swap With Main Bar. Check the Hide option. That's it. You don't have to set a single other option.
    5. Repeat step 4 for all your shapeshift forms.
