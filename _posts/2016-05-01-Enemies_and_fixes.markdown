---
layout: post
title:  "Weekly Update #10 - Enemies and fixes 25.4 - 1.5"
date: 2016-05-01 17:02:00
---
It's already the 10th weekly update! Wow! I got some nice visual progress done this week, at least compared to last week's. So let's dive into it!
I added a new enemy type to the game. The new general enemy wears a cool big hat and he calls for backup when he notices the player. The general holds a pistol. When the general sees the player, a parachute enemy is spawned right outside the view.
![BACKUP! NOW!](/assets/WeeklyUpdates/10/General.gif)
I also tweaked the generic enemy AI so that they now panic when they are set on fire. The panic mode was also tweaked a little, so that the enemy doesn't always drop his weapon. There's a chance that he keeps on firing randomly and unexpectedly, making him extra dangerous.
![FIIIIIIREEEEEEE!](/assets/WeeklyUpdates/10/Panic.gif)
That's all the visual progress from this week. I continued to add more sounds to the game, and the sound world definitely is starting to slowly feel more complete. I also improved the controller deadzones. The game now determines the controller force dynamically and is all around much better. Thumbsticks now also work better in the menus. The controller deadzone is exposed to the config file, but a settings menu entry will not be provided for it due to the lack of usage I assume.
I also made a little improvement to the web site. I added the [Features](#Features) portion to the header text with a nice gameplay gif next to it.
Thanks for dropping by! And here's finally the complete changelist!
*   Fixed player explosive attacks on weapon switch
*   Fixed input manager trying to access invalid controllers
*   Fixed flame thrower damage targets
*   Fixed level selection menu offset
*   Fixed flame thrower damage box
*   Fixed a couple of major memory access crashes in release
*   Added a sound to the prisoner escapes
*   Added a sound to the flame thrower
