---
layout: post
title: "Weekly Update #40 - Steam Contracts & Lost Device Handling 5.12 - 11.12"
date: 2016-12-11 12:02:00
---

This wasn't my most productive week ever, but some substantial stuff did happen!

First of all, I finally just got to it and signed the Steam contracts. It wasn't easy, but I was able to fill in the quite complex forms. Even the tax interview passed, which was the part of which I was most nervous about. On Saturday I even got my first build uploaded to Steam and I was able to initialize Steamworks in the game engine!

On the actual game side, I actually only worked on one thing this week: I added a system that handles controllers (or other input devices) getting removed during gameplay. The game now stops the level, and displays a dialog that will either allow you to ignore the lost device and remove the player that was controlled by it or to rebind the device. After that the level will continue just where you left off. It's not a huge change but who knows, it might save someone's day when their controller dies in the middle of a boss fight or something.

![The new device lost system.](/assets/WeeklyUpdates/40/Device.png)

Anyways, I don't really have anything else to write about, so this post is yet another quick one. Thanks for dropping by!

* Fixed certain sounds playing too loud
* Fixed sound pausing
* Fixed hostages dying after level completion
* Fixed ice shard collision with tile boxes
* Fixed lava height