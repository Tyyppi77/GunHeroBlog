---
layout: post
title: "Weekly Update #32 - Flame Traps & Rain 10.10 - 16.10"
date: 2016-10-16 11:46:00
---

I had a pretty productive week. I both polished an old feature and added new stuff to make levels with.

Let's start with the polishing: I reimplemented rain to the game. The old particles were just blue pixels that I moved trough the screen and killed once they went off-screen. The new rain particles use a new type of a line renderer, and just looks a lot better than the old version. I'm super happy with how  the particles turned out. The implementation wasn't even too hard, the particles simply define a special property in their definition file, and then the particle class uses a line renderer implementation for the particles instead of a sprite. Here's a small video of the rain.
{% video /assets/WeeklyUpdates/32/Rain.mp4 %}

Then, let's get to the new level element! I added flame-thrower traps that I'll use in levels in the jungle environment. I simply took the flame particles from the flame thrower weapon (that I still need to find a use for) and added a few hardcoded new particle definitions for the different directions. Then I added a damage box that interpolates to full size when the trap emits flames. The basic implementation didn't take very long, but adding the different orientations took some time to polish. Positioning things is always a pain.

![I like my players nice and crisp, how about you?](/assets/WeeklyUpdates/32/FlameTraps.gif)

That's everything I have to show this week. As usual, I'll include a changelist of the fixes and tweaks I made this week. Next week is autumn-break, so I'll have plenty of time to dev. I hope you have a nice week!

* Fixed grenades not attaching to rockets
* Fixed ledge slipping getting applied in the level editor
* Fixed sound volume breaking
* Fixed level select grid offset