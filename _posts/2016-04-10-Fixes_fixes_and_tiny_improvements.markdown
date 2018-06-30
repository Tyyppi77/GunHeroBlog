---
layout: post
title:  "Weekly Update #7 - Fixes, fixes and tiny improvements 4.4 - 10.4"
date: 2016-04-10 17:30:00
---
I was really busy with exams this week, so this week's progress isn't great. However, I fixed some bugs and made some small tweaks along with some preparations for a demo release in the coming weeks.
The coolest improvement I made was definitely the panic mode I added to the enemy AI. Now, when a grenade latches on an enemy, the enemy freaks out and starts running in panic, often times into other enemies, creating cool area explosions! You can see that happening in the image below.
![Boom! and they are dead.](/assets/WeeklyUpdates/7/PanicNade.gif)
I also made the grenades behave properly in water, and water splash particles spawn when a grenade hits water. It's the little things... :)
![That's some easy water physics for ya.](/assets/WeeklyUpdates/7/NadePhysics.gif)

![SPLOOOSH!](/assets/WeeklyUpdates/7/SplashParticles.gif)
I played the current levels trough a couple of times this week and started ironing out all the little bugs that I found. My tasklist expanded a lot, but I also got already a lot of bugs fixed. Here's the usual change list, have a nice week!
*   Fixed guns getting stuck to walls
*   Fixed memory crash caused by bubbles
*   Fixed level session menu tween time
*   Fixed grenade collisions
*   Fixed fade background not reaching target
*   Fixed missile launcher always choosing the first player
*   Fixed event manager crash on nested callbacks
*   Fixed local multiplayer using campaign order
*   Fixed local multiplayer returning to main menu instead of level selection
*   Fixed grenade throwing in water
*   Fixed giant enemy death sprite blood color
