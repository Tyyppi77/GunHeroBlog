---
layout: post
title:  "Weekly Update #30 - Lasers, levels, missiles and cutscenes 26.9 - 2.10"
date: 2016-10-02 11:57:00
---
Once again I had a really productive week. I added new features to the game, polished old ones and designed new levels.
Last Sunday I started working on lasers for the prison environment! While getting the laser beams positioned correctly required hours of fighting with the unit circle, it was super fun to work on the laser wheel, and I think it turned out awesome. I had a blast making levels with the laser beams, and I think they add nice challenge to the prison levels. They also bring the theme together, as the prison boss uses a laser beam as its weapon.


![Much deadly, wow.](/assets/WeeklyUpdates/30/LaserWheel.gif)

![And this is just the start...](/assets/WeeklyUpdates/30/LaserLevel.png)
Many weeks ago I showed bomb levels, where a bomb was spawned at the truck at the end of the level. This introduced a time limit to the levels, and added variety to the gameplay. I really liked the feature, but I never actually made any levels using the bomb level. So that's what I did this week. I added a few small levels with the bombs. I wanted to let the player to know what to do with the bombs, so I also had to write a few cutscene scripts that show the player that a bomb is dropping down. I fixed a bunch of bugs related to the cutscene scripting, and I ended up with a more polished cutscene feel.

On Friday, I decided to rework my level thumbnail generation system. The thumbnails are now captured at half the resolution, which over halved the game's RAM footprint. I also now have the ability to recapture all the thumbnails. So, if I end up changing the sprite of the enemy for an example, I can just type in a command in the in-game dev console, and wait for a couple of minutes while the game recaptures all the thumbnails. The rewrite turned out to be way easier than I expected, and I faced hardly any issues. Initially I wanted to render the thumbnails at native resolution (480x270), but it turned out that the resolution was way too small for the rotating objects I have around here and there. The rewrite was very successful!

Yesterday I decided to polish the missile launcher. The old version just used a static sprite and spawned rockets randomly around it. The new version actually looks like a missile launcher, and it spawns rockets at correct positions with the correct rotations. It is definitely a huge improvement over the old one.

![Much polish, wow.](/assets/WeeklyUpdates/30/MissileLauncher.gif)
I also fixed a bunch of bugs this week. I don't actually know what I'll be working on next week at all. Anyways, thanks for reading, I hope you have a nice week!
*   Fixed entity depth layering
*   Fixed bullets burning
*   Fixed zoom camera positioning
*   Fixed player input releasing on game over and cutscenes
*   Fixed sprite bounding box calculations
*   Fixed particle alpha clamping
