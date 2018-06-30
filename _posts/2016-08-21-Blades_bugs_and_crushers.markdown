---
layout: post
title:  "Weekly Update #24 - Blades, bugs and crushers 15.8 - 21.8"
date: 2016-08-21 14:29:00
---
I've had a quite productive week, both in terms of game content and bug fixes. Let's got to all of it!
The winter environment uses blades a lot as environment hazards, and I spent some time tweaking the blades. Mainly, now the blades turn red if the player hits them. The effect isn't perfect, but I think it looks quite nice, and makes the blades look cooler and more dangerous.

![There was blood everywhere!](/assets/WeeklyUpdates/24/BladeEdge.gif)
While working on the big blades, I got an idea to add smaller blades that are shot by cannons introduced to the game a while ago. So, a few sprites and few lines of code later I had cannons launching spinning blades to the levels!

![There was blood everywhere!](/assets/WeeklyUpdates/24/CannonBlades.gif)
I also added an arrow that points to hostages in levels. I realized that it's frustrating if the player hops on to the truck at the end of a level, and then noticed that the level was failed, because he failed to pick up the hostage. Now it should be more obvious when there is a hostage in a level.

![The arrow is rotated and all that jazz!](/assets/WeeklyUpdates/24/Arrow.png)
Finally, I added crusher entities, that look like giant hammers. The crushers drop from the ceiling, and as their name says, they crush anything that gets in their way. I reused the crushing code from the elevators. I am also quite proud of the crusher sprite, it turned out really well.

![There was blood everywhere!](/assets/WeeklyUpdates/24/Crusher.gif)
All in all, I have a pretty nice set of obstacles and hazards to use in level creation for the winter environment. I've already made a few levels, but there is still some missing. The winter environment is coming along nicely though.
While tweaking the blades, I noticed that I had run out of entity type flags. I use a bitflag approach for types, which makes collision masking very easy and nice. However, a 32-bit integer couldn't hold my entity types anymore, and I decided that the most sustainable approach would be to switch to using std::bitset, which works like an array of booleans. Now, my entity types simply refer to an index in the array, and the class offers utilities for and-ing and or-ing values together. The change only ended up taking about 20 minutes, which was a pleasant surprise to someone who was prepared to spend the whole day refactoring the type system!
Next week I want to keep on working on the winter environment and probably fix more bugs too. I also should start thinking about ideas for the winter boss. That's it for this week, thanks for dropping by!

*   Fixed controller vibration
*   Fixed decal clearing
*   Fixed player jump and animation states
*   Fixed character force friction on ice
*   Fixed NPC movements on ice
*   Fixed a few SDL warnings
*   Fixed particle clearing in level editor
*   Fixed brush list boxes getting focus while hidden
*   Fixed terrain brushes on top rows of levels
*   Fixed entity property dialog showing even if there isn't a property
*   Fixed entities getting placed at the end of an area selection
*   Fixed entity property dialog popping to weird places at weird times
*   Fixed area selection not working of the property text entry was selected
*   Fixed list boxes reporting false positive hover values
*   Fixed player walking out of bounds if hoving on a brush listbox
*   Fixed bullets not colliding with crumble blocks
*   Fixed bullets colliding with dead pilots
*   Fixed editor crashing when the selected entity is deleted
*   Fixed scrolling in listboxes
*   Fixed dead players being able to pick up health and ammo kits
*   Fixed crushing spawning multiple entities
*   ...and a bunch of other smaller tweaks and fixes
