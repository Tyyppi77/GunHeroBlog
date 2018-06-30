---
layout: post
title:  "Weekly Update #1 - Winter break 22.2 - 28.2"
date: 2016-02-28 15:54:00
---
This is the first weekly update on the GunHero site! Let's get straight into business: the first thing I worked on this week was animated tiles. This feature was long due, and in the end it wasn't too hard to implement into the engine. In the following picture you can see the animated water tiles in action.

![Water tiles are now animated.](/assets/WeeklyUpdates/1/AnimatedTiles.gif)
While I was working on water, I also ended up adding water splash particles. The implementation for those was really trivial.

![Water splashes spawn from the lovely morning swim of GunHero.](/assets/WeeklyUpdates/1/WaterParticles.gif)
Next thing up on my tasklist were health kits. Currently the game had no way to regenerate the player's health. So I added in a health kit entity that restores health. The health kits have small waving movement on them to make sure they pop out from the environment. I also added health particles that spawn around the player when a health kit is consumed.

![Healing is received from the health kits.](/assets/WeeklyUpdates/1/HealthKits.gif)
The biggest improvement I made on the winter break was definitely the code refactor I made to the weapon system. The old system was hardcoded to assume that all weapons were guns that shot simple bullet projectiles, one at a time. The new system uses the factory pattern to allow different behaviours to be implemented for weapons. Using the new system, I added really cool weapons to the game, and I will definitely keep on adding more as the development process continues. Here you can see the new flame thrower and in the following picture you can see the fire spreading mechanics I coded for the boxes.
![GunHero uses the new flame thrower.](/assets/WeeklyUpdates/1/FlameThrower.gif)

![Fire spreads from box to box. (The quality of this gif is a little worse because I had to use GifCam due to a threading bug in the custom gif tool I normally use.)](/assets/WeeklyUpdates/1/FireSpread.gif)
I also got around and added a sword weapon. The close-up melee fighting is really fun, and I spent a lot of time just smashing boxes with the sword.
![GunHero demonstrates sword usage.](/assets/WeeklyUpdates/1/SwordWeapon.gif)
Along with these gameplay features I cleaned a lot of code and made minor tweaks to different kinds of things I had on my tasklist. Lots of bugs also got fixed during the week. All in all, I had a really productive week. Next week is school again, so the updates in the future won't likely be as stuffed as this one.
