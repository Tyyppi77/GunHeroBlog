---
layout: post
title: "Weekly Update #43 - Weapon Bubbles 8.1 - 15.1"
date: 2017-01-15 12:27:00
---

I don't feel like writing an intro paragraph, so right into the action: Each weapon in the game now has an unique bubble. I received feedback about how the weapons aren't really distictive enough, and given my very limited weapon sprite resolution, I thought I'd make it easier to spot which weapon you're about to pick up with a bubble sprite!

![The new tutorial.](/assets/WeeklyUpdates/43/Weapon.gif)

I also composed a new song, an alternative winter theme. The names of the tracks are mainly for keeping track of what's done, as I plan to just play all the tracks on a nice level based loop. Given that I've planned basically two tracks per environment, I think that's too few to keep those two tracks for a single environment. Anyways, here's the track:

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/302672333&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

I also did some code cleaning this week. I fixed some errors pointed out by a static analyzer. I also replaced my old filesystem code that was implemented using WinAPI calls with the new and shiny std::filesystem. It was a really pleasant experience and the whole conversion took maybe ten minutes!

Anyways, thanks for dropping by and sorry for the short post. 

* Improved slow-motion & fast-forwarding
* Added transparency to weapon bubbles
* Tweaked credits