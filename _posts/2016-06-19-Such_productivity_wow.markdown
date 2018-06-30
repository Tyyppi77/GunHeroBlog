---
layout: post
title:  "Weekly Update #17 - Such productivity, wow! 13.6 - 19.6"
date: 2016-06-19 15:33:00
---
I had an awesomely productive week, both in terms of visual content and bugs fixed, so let's get straight to it!
The first big gameplay addition I made is the elevator crushing. Elevators now squish poor characters that get in between solid terrain and an elevator. Blood is everywhere and the character sprite is squished down. This is really makes the game feel more immersive and the interaction was definitely required. Here you can see the crushing in action:
![Poor guy!](/assets/WeeklyUpdates/17/ElevatorCrush.gif)
For a while I had felt that the guns in a game called GunHero were too lame. I found that I only played with the SMG gun, never picking up anything that enemies dropped. That's why I decided to improve the guns by adding more variety to them. Now I have awesome regular guns, one gun that shoots double bullets, and one gun that has a really cool burst mode. All the weapons have their own characteristics, and now I'm sure everyone will find a weapon suitable for their playstyle. Here are the new bullet modes, double and burst:
![Look at that bullet gap!](/assets/WeeklyUpdates/17/Double.gif)

![Burst mode!](/assets/WeeklyUpdates/17/Burst.gif)
While working on the weapons, I also improved their feel by playing a sound if the weapon's firerate limits bullet shooting and a bullet isn't shot when the player presses the shoot-button down. The firerate counter now also decreases while the weapon is inactive, which is something that should have been programmer in a long time ago.
I also added a small blinking animation to the bomb, and changed the bomb mode to explode the truck at the end of the level. That's why I needed to add an explosion sprite to the truck, and I find that the sprite turned out pretty well.
![BOOM!](/assets/WeeklyUpdates/17/TruckAndBomb.gif)
While clearing my tasklist, I finally added trigger moving and resizing to the level editor. Movement is implemented by dragging the trigger box around, and resizing is done by dragging sliders in the trigger property dialog.
![So slick UI, much UX!](/assets/WeeklyUpdates/17/TriggerSize.gif)
I also composed a quick menu background song. It's not my best song, but I think it will do fine atleast for now. You can listen it below.
<iframe class="soundcloud" frameborder="no" height="166" scrolling="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/269856856&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false" width="50%"></iframe>
I cleared my tasklist almost completely this week. I fixed a lot of long-persisting rare bugs that really broke the game feel. I'm extremely happy with this week's progress, and I'm definitely feeling the point of hitting Greelight approaching fast. Have a nice week!
*   Fixed light map shadows on level borders
*   Fixed level editor light map loading
*   Fixed thumbnail marker not hiding
*   Fixed tile spritesheet crash on new levels
*   Fixed tile rendering artifacts
*   Fixed input config menus accepting input from unwanted devices
*   Fixed scrollable menus breaking horribly
*   Fixed flame thrower working trough doors
*   Fixed screenshake on level boundaries
*   Fixed weapons falling trough ground
*   Fixed boss movement after player death
*   Fixed fullscreen screenshot capture crash
*   Modified view scale by a bit
*   Improved level time display readability with a background
*   Improved join menu time display readability with a background
*   Reduced boss firerate
*   Removed event block in cutscenes
*   Added install directory selection to installer
*   Added cancel button to new level dialog
*   Added cursor tile position display to level editor
