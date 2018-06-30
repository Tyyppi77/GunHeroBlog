---
layout: post
title: "Weekly Update #49 - Small Patches 27.2 - 5.3"
date: 2017-03-05 15:08:00
---

I have nothing fancy or new to show this week. I spent some time working on a press kit for the website and that is coming along quite nicely actually. Besides that, I did some fixes and patched a thing here and there. I guess it's a good thing that there's not a whole lot to do anymore?

I got a really weird bug report: if the player jumped just in the right way on to a crusher, the player would glitch through the crusher and end up in a weird position. It turned out that the player was resolved against the bottom side of the crushers which was caused by the fact that both the player and the crusher were moving up. It definitely took a good few hours of jumping against the crusher to figure this out... I'm really glad I figured it out though.

Next week I might trace some memory leaks and perhaps even get started on a trailer. Some playtesting also needs to happen. I hope you have a nice week!

* Fixed prison boss death
* Fixed grenadier throw direction
* Fixed health screen tint scale
* Volume now updates as it is changed
* Updated executable icon
* Player now moves to the next area when the previous area is completed
* Navigation help now scales on larger monitors