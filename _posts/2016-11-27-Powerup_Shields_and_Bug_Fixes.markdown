---
layout: post
title: "Weekly Update #38 - Powerup Shields & Bug Fixes 21.11 - 27.11"
date: 2016-11-27 10:28:00
---

I had a very productive week! I reworked the powerup system and fixed a ton of bugs.

The old powerup system was quite awful: the player was awarded immunity to damage and explosive bullets when the powerup point bar filled up. This meant that the player had no control over when the powerup would be activated. In the new system, the player gets powerup points the exact same way: from killing enemies and releasing prisoners. However, the player can now use the powerup points whenever he wants. The powerup also doesn't suck in the new system: the player gets a shield that protects him from most of the incoming damage. The shield also heals the player while active.

![The shield is really fun to use.](/assets/WeeklyUpdates/38/Shield.gif)

I don't really have anything visual to show besides the shield this week. I did fix a ton of bugs and that really showed on my Saturday-evening playthrough. Thanks a lot for reading!

* Fixed bombs not getting removed from the level
* Fixed camera targetting in the tutorial cutscene
* Fixed player exit shaking the camera
* Fixed level editor not relocating tiles in containers
* Fixed bullets colliding with ladder tops
* Fixed grenades and bullets colliding with ladder tops
* Fixed blood particles spawning when player dropped out of level
* Fixed grenades behaving oddly with electricity beam emitters
* Fixed bullet trail particles not changing sprite rotation
* Fixed level exit trigger behaviour in multiplayer
* Fixed trigger editing dialog losing position values in the level editor
* Fixed tank driving in multiplayer
* Fixed bullet velocities on the winter boss elevator
* Fixed prisoners not walking out of level
* Fixed player being able to glitch through crushers
* Fixed Fixed desert entrance cutscene villain orientation
* Fixed player direction flipping after strafing
* Fixed hostage lagging behind players
* Fixed label sprite not updating position fast enough
* Fixed ice triggers being too tall
* Fixed level resizing not applying offset to triggers
* Fixed crash on clicking level properties on an empty level
* Fixed tooltip positioning at the bottom of screen
* Fixed world map not unlocking first node
* Fixed grenades attaching to rockets
* Fixed grenades crashing the game randomly
* Fixed grenadier attack bubble not hiding
* Fixed players getting crusherd if they jumped from a platform
