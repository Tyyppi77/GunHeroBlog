---
layout: post
title:  "Weekly Update #6 - Performance & Levels 29.3 - 3.4"
date: 2016-04-03 17:13:00
---
I spent most of the week trying to locate a performance issue that was bringing the FPS down by a lot. I was checking for collisions in the gun entities, which was not necessary. All characters have a weapon, so removing the checking was quite an improvement. I'm currently focusing on putting out a demo build, so the rest of the week was spent adding levels and improving the tutorial cutscene.
So I will share some of the thumbnails of the new levels I made. First, pictures of the prison levels I made.
![A new prison level.](/assets/WeeklyUpdates/6/PrisonBreakThumbnail.png)
These are actual thumbnail images that the game generates for each level. The thumbnails are used for an example in the level selection menu I showed a couple of weeks ago.
![A new prison level.](/assets/WeeklyUpdates/6/PrisonBreakHorThumbnail.png)
One more, this one has more vertical stuff!
![A new prison level.](/assets/WeeklyUpdates/6/PrisonBreakTowerThumbnail.png)
I also made a small introduction level to the jungle environment, that acts as a rebellion base in the jungle. There are no enemies in the level, only structures and supplies.
![A jungle introduction level. There's also a trampoline!](/assets/WeeklyUpdates/6/JungleThumbnail.png)
Yesterday I improved the HUD. I added a respawn timer to the player respawns in local multiplayer, so I needed a way to display the respawn time. I also tweaked the display so that the player sprite switches to a temporary skeleton sprite.
![It's a spooky skeleleleleton.](/assets/WeeklyUpdates/6/DeathHUD.png)
That pretty much concludes the visual progress of this week. I'll keep working on more levels for a demo along with fixing critical bugs. Here's the weekly boring change list. Thanks for dropping by!
*   Fixed minor performance bugs
*   Fixed framerate limiting not working in release builds
*   Fixed list box hovering
*   Fixed file dialog focus
*   Fixed camera zooming
*   Added renderer state stack
*   Added an installer file generator
