---
layout: post
title:  "Weekly Update #14 - Small things 23.5 - 29.5"
date: 2016-05-29 16:25:00
---
Exams started this week, so I finally had some time to spend developing GunHero. I did a bunch of small tweaks and additions this week, so let's roll!
The boss now has a health bar! This makes the boss fight feel better, as you can see the boss take damage and slowly die.
![Boss' new health bar.](/assets/WeeklyUpdates/14/BossBar.gif)
I also added speech bubbles to characters in cutscene dialogues. The implementation was really simple, dialog message instructions now simply allow the script to set a speaker entity, and a bubble is spawned above the speaker's head. The bubbles use similar graphics to the other bubbles in the game, so the visuals are still very consistent
![Intense dialogue going on in here.](/assets/WeeklyUpdates/14/Bubble.gif)
Another small tweak I made was applying trampoline physics to all characters. Now enemies that are panicking can bounce in a pretty awesome way into the skies and die. I simply had to move the trampoline code from the player class to the parent character class. With lucky bouncing caused by gravity, enemies can now randomly jump into pits, which is a really fun effect.
![*boing* *BOOM*.](/assets/WeeklyUpdates/14/DeathBounce.gif)
I also fixed water physics on dead bodies. The effect look pretty nice and makes water seem more authentic. I simply enabled water trigger checking while a character is dead.
![Poor player.](/assets/WeeklyUpdates/14/WaterDeath.gif)
In the beginning of the week I spent some time making new levels for the game, and in the result of a random thought I decided that it would be cool to make a timelapse video of me making a level using the level editor. The video turned out pretty well I think. I added the song I made to the background and sped up the footage 16 times. So here's the video, and the change list for the week. Have a nice week!

<div class="embed-responsive embed-responsive-16by9"><iframe allowfullscreen="allowfullscreen" class="video" frameborder="0" height="50%" src="https://www.youtube.com/embed/Ldv9QJke91E?showinfo=0&rel=0" width="100%"></iframe></div>

*   Fixed empty brush crash
*   Fixed pause menu not pausing music
*   Fixed music not restarting
*   Fixed trampoline vision block
*   Fixed door vision block
*   Fixed bazooka rocket positioning
*   Fixed dummy character hitbox size
*   Fixed level path crash
*   Added controller support to list menu items
