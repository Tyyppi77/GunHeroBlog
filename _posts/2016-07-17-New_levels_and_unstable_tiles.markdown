---
layout: post
title:  "Weekly Update #19 - New levels & unstable tiles 11.7 - 17.7"
date: 2016-07-17 12:47:00
---
There aren't a ton of new awesome gameplay features to show this week, but I got some nice progress done this week in terms of making actual playable content for the game. So let's see what got done this week!
I added a red tint to the game screen when the player's health is low and added a flashing effect to the HUD's health label. I really like this addition as it makes you actually feel that you're low on health. You easily notice it now and realize that it might be a good idea to search for a health kit.
![The tint is a radial gradient with tons of transparency.](/assets/WeeklyUpdates/19/Tint.png)

![Linear interpolation is the key to everything.](/assets/WeeklyUpdates/19/HealthFlash.gif)
I'm a little embarrassed about this week's new feature. It seems like such a basic platformer game element that it's weird that I hadn't implemented it until now. Anyways, the game now has blocks that fall down after the player has walked ontop of them. I already had a ton of fun making levels with these new blocks, getting enemies to walk on them and then walking over the blocks, dropping enemies into the dark void below the levels.
![The blocks are destroyed after a small delay.](/assets/WeeklyUpdates/19/CrumbleBlocks.gif)
Lastly, the game got a bunch of new levels this week, and currently the jungle environment is only missing a boss fight. Here is a picture of my favorite new level:
![The blocks are destroyed after a small delay.](/assets/WeeklyUpdates/19/Cliff.png)
That's it for this week, thanks for dropping by!

Changelist has made a return:
*   Added save date to save files
*   Fixed player's collecting health kits at full health
*   Fixed boss bubble scale bug
*   Fixed boss level camera bug
*   Fixed elevator crushing on large enemies
*   Fixed weapon bubbles showing on equipping
*   Fixed cutscene camera commands
*   Fixed prisoner gravity
*   Fixed horrible crash on font metrics
*   Improved enemy positioning
*   Improved text dimension calculation performance
