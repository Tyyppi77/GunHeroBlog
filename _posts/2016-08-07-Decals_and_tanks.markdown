---
layout: post
title:  "Weekly Update #22 - Decals & tanks 1.8 - 7.8"
date: 2016-08-07 14:32:00
---
I had a pretty productive week, so there's some cool stuff to show! Let's get to it!
I continued working on the decals, and I got those looking pretty awesome. They definitely add more depth to the environments. Currently I spawn decals for blood and explosions, but I'm still looking for other uses. I've also toyed around with the idea of making the blood decals drip. Here's a screenshot with the decals in place.

![Aren't they pretty?](/assets/WeeklyUpdates/22/Decals.png)
Next up, the most badass feature of this week: Tanks! These deadly vehicles are controlled by enemies... unless you shoot the driver and take control of the tank yourself! I had a ton of fun drawing the sprites and implementing the tank behaviour. Because the player needs to control the tank, I had to also refactor the input listening code, which is a big improvement to the codebase. Take a look of the tank!

![Vroom vroom!](/assets/WeeklyUpdates/22/Tank.gif)
That concludes the visible features of this week. I also fixed some bugs and cleaned some code. Next week I want to make some new levels utilizing the tanks, and perhaps keep on implementing gameplay features. School starts on Thursday, so I'm not sure how much I can get done before that. School will definitely slow down the progressing. I hope you have a nice week!
*   Fixed weapons burning
*   Fixed decal rendering order
*   Fixed bullet collision bug
*   Removed AI dependencies on character entities
