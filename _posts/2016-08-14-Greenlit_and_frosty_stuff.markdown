---
layout: post
title:  "Weekly Update #23 - Greenlit, and frosty stuff 8.8 - 14.8"
date: 2016-08-14 13:28:00
---
As you've probably read already, GunHero was Greenlit on Tuesday! Also, school started on Thursday. I do however have a few things to show from this week. Let's get to it!
Probably the coolest feature added this week is the ice shards. These shards are randomly positioned to the areas wanted, and they drop down in a deadly manner once the player walks past them. It was not very tricky to implement them, however due to the high amount of these shards, I still have some sound issues that I need to figure out.

![Looks cold and awesome, doesn't it?](/assets/WeeklyUpdates/23/IceShards.gif)
As the current focus is to work on the winter environment, I also wanted to add a basic ice terrain type to the level editor brushes. Now I can place slippery ice terrain to my lovely winter levels!

![Oh man, where are my skates?](/assets/WeeklyUpdates/23/IceTerrain.gif)
While adding those ice shards, the entity list box got so tall in the level editor that the entities couldn't fit to the screen anymore. So adding scrollbars to those listboxes became my top priority, as I was unable to make proper levels since I couldn't select from all the available entities. I fixed that this morning, and also ended up widening the listboxes a little, so that the brush names now properly fit to the listboxes.

![Pretty pretty scroll bars with hacky UI code!](/assets/WeeklyUpdates/23/ListBoxes.png)
I also fixed a bunch of bugs this week, and tweaked the player's animation state system a little. I want to keep on working the winter environment next week, and keep on creating awesome content for it. I already have some plans in mind, but I am not really sure if they will fit the winter environment properly. Anyways, thanks for dropping by!

*   Fixed tank pilot positioning in level editor
*   Fixed explosion decal positioning
*   Fixed decals not clearing on level restart
*   Fixed player sliding animation
*   Fixed crashes on empty editor levels
*   Improved deltatime accuracy
*   Added game over timer tweaking to console commands
