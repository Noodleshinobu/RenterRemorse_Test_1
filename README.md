# RenterRemorse_Test_1
Game for Capstone Group

-----------
| Credits |
-----------
Welcome to Renter's Remorse, a That'll Do Games production.
This game serves as our collective Capstone project for COSC-4375, COSC-4395, and CSCI-4385.
The team behind this project is composed of:
- Joseph Peery (CS major)
- Joshua Jones (CS major)
- Spencer Myers (CIS major)
- Justin Nguyen (IT major)
- Sasha Scott (IT major)

Also, special thanks to Mr. Propaganda (Jacob Moellenbeck) for making the game's music.
This game was created using Unreal Engine 4.27.2.

-------------
| Main Idea |
-------------
Renter's Remorse follows the story of a landlord who needs to kick his tenants out of their leased property one way or another.
Asking nicely won't work and there is no feasible way to legally evict them. At this point, the landlord is left with no choice...
He must scare them out. 

In order to scare the tenant into cancelling their lease early, the landlord must employ psychological warfare through the use
of placing gadgets throughout the house while the tenant is supposed to be asleep. The landlord must careful, though, since the
best-case scenario of being caught in someone else's home is a 15-year extended vacation in the county jail!

------------
| Gameplay |
------------
Once the game has successfully booted up, you will be presented with the main menu, where you can either start a new game, enter the
options menu, or quit the game. 
In the options menu, you can change the sound volume and pick the window resolution you would like your game to run in.
Once you start the game, you will take control of the landlord, starting in his bedroom, beginning the gameplay loop.

There are 2 phases that compose the gameplay loop: R&D (Research and Development) and B&E (Breaking and Entering).
The R&D phase takes place during the day in the landlord's bedroom, where he can purchase gadgets and learn more about the tenant.
Gadgets bought from the computer can then be picked up on a table in the opposite corner of the room.
The landlord can buy gadgets and view facts about the tenant by using the landlord's computer near the corner of the room.
The landlord can leave the R&D phase and enter the B&E phase at any time by walking to the bedroom door.
The B&E phase takes place during the night outside of the tenant's house. Here, the landlord can sneak into the house to place previously 
bought gadgets around the house for the tenant to eventually find. 
The landlord can leave the B&E phase and enter the R&D phase at any time by walking up to the van parked on the street.
The gameplay loop countinues until the player wins or loses. 

The player wins if the landlord is stressed or scared enough before the deadline. 
The player loses if the landlord is either caught by the tenant during the B&E phase or if the tenant is not stressed or scared enough before the deadline.

Gadgets can have various effects on the tenant, with most invoking stress and/or fear. 

There are currently 3 gadgets to choose from:
- Bucket o' Blood (when used, spills blood on the ground for the tenant to see and experience fear)
- Bag of Bric-Blocs (when used, spills building block toys for the tenant to step on and suffer stress)
- Audio Tape Recorder (when used, plays spooky sounds that can startle the tenant)

------------
| Game HUD |
------------
During gameplay, there are a number of elements that will stay on-screen, either in the corners or on the sides of the game's window.
These HUD elements include:
- Stress/Fear Meter
- Phase Indicator/Day Counter
- Inventory Menu

The Stress/Fear Meter located in the top-left corner of the game's window shows the player's current progress on scaring the tenant. Once
the meter is full, the player wins.
The Phase Indicator/Day Counter located in the top-middle portion of the game's window displays an icon (sun or moon) that represents the 
current phase of gameplay (R&D or B&E). It also displays the number of days that have passed in-game since the landlord's mission has started.
The Inventory Menu located in the top-right corner of the screen displays all the gadgets the landlord currently holds. It is important to note
that some gadgets can only be stacked a certain number of times in each inventory slot.

The Action Prompt HUD element will appear when they are able to perform an action, such as when they are close enough to an item that they can pick up.
This displays both the action and the keyboard key the player can press in order to execute that action. For example, when the player selects an item
from their inventory, the Action Prompt will show the button the player can press to use that item.


------------
| Controls |
------------
**Menu navigation:**

Left-click (Mouse) on the desired buttons that display.

**During gameplay:**

*Player movement*

Left-click (LMB Mouse) on a valid location on the map to move your character to that location.

*Entering the pause menu*

Pres Esc (Escape key) to enter the pause menu.

Other controls are presented via the Action Prompt.

---------------------
| View Source Files |
---------------------
To view source code of the project please install Unreal Engine Version 4.27 using the instructions given in Unreal Documentation found [here](https://docs.unrealengine.com/4.27/en-US/Basics/InstallingUnrealEngine/). Once downloaded, unzip the source code and start the RenterRemorse_Test_1.uproject file.
