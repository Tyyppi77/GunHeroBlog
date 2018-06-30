---
layout: post
title: "Weekly Update #39 - Sound Effects and Bug Fixes 28.11 - 4.12"
date: 2016-12-04 12:02:00
---

This week I spent most of my time fixing bugs. I also added a bunch of sound effects to the game. This means that there's nothing visual to show, sorry about that.

My sound "engine" needed a rework. The old system had two modes: play a sound at the player's position or play a sound at a specific position. Sounds with specific position took in a distance, over which the volume of the sound would be interpolated. Outside of the distance the sound would not be heard at all.
The new system is a little different, and a lot better. It allows playing sounds at specific positions and at the position of an entity (which will of course be updated if the entity moves). Also, instead of supplying a maximum sound distance to the engine, I now specify the distance under which the sound will be heard at 100% volume, and a factor that is used to determine how quickly the sound fades away after the minimum distance has been exceeded. This creates a much better feel and doesn't require me to make sounds incredibly loud when the player is standing next to them!

So that's it for this super quick write-up. Have a nice week!

* Fixed player shield and hostages
* Fixed world map zooming
* Fixed shallow lava pools
* Fixed crush trap crushing
* Fixed save menu behaviour
* Fixed ice shard decals
* Fixed truck dust particles
* Fixed line particle death
* Fixed character liquid depth layering
* Fixed parachute initial position
* Fixed roof tile layers
* Fixed villager head crushing
* Fixed parachute position updating
* Tweaked various levels
