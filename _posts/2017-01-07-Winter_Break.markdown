---
layout: post
title: "Weekly Update #42 - Winter Break 19.12 - 7.1"
date: 2017-01-07 18:56:00
---

It's been a few weeks since my last weekly update. I did manage to get a bunch of stuff done during the winter break and overall I'm quite happy with my progress! I'll write about some stuff in more detail, but I also feel like there has just been a lot of systems-level work, so the changelist is probably going to be quite long this time.

First I improved the tutorial of the game. The old tutorial level was just a level, and while it did have some taughtful obstacles for the player to overcome, my playtesters had some trouble learning the basics of the game. That's why the new tutorial system displays help texts at the top of the screen. Here's a screenshot of the tutorial level:

![The new tutorial.](/assets/WeeklyUpdates/42/Tutorial.png)

Continuing with Steamworks support, I added achievements to the game. Most of the achievements were implemented using stat-tracking that is provided in the Steamworks API. The game basically increment some stats, such as enemies killed using a specific weapon, and I can link and achievement to that stat that will be awarded once the counter reaches a specific value. This made adding achievements quite pleasant. Some achievements were added as level triggers and the final few are awarded by specific entities in the game source.

Finally, the game got not one, not two but three new tracks! The tracks probably need another pass at mixing but I'm really proud of the melodies I was able to put out. I think they match the tone of the game really well.

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/300733153&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/301033992&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/301388418&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

Finally, I got some feedback that the transitions in the game felt lame. So, instead of boring fade ins and outs, states and screens are now swapped with a cool sliding animation!

{% video /assets/WeeklyUpdates/42/Slide.mp4 %}

A bunch of other stuff probably happened but I don't remember it right now, so just take my word that I had a productive winter break! I'll get back to writing these updates weekly now. Thanks for dropping by!

* Added suicidal behaviour to grenadiers
* Added powerup point management to the difficulty system
* Removed cutscenes from bomb levels
* Fixed input devices getting removed at the join screen, world map and level finished dialog
* Added settings menu to the pause menu
* Fixed zero-division errors
* Improved explosion collisions
* Improved the final cutscene
* Fixed controller deadzones
* Fixed bullet trails under rooftops
* Added a special decal layer for roofs
* Fixed elevator boss exploits
* Fixed restart crashes