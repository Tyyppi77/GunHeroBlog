---
layout: post
title:  "Weekly Update #26 - Rotating things and desert 29.8 - 4.9"
date: 2016-09-04 11:51:00
---
I was sick the beginning of the week, but luckily I was able to work on the game quite productively at the end of the week. I have some cool stuff to show, so let's go!
I added spinning blades to the game. The entity simply uses a static blade, and spins that around in a circle while the spinner arm rotates behind the blade. All in all the implementation was quite easy. However, I had to add support for varying rotation origins to the engine. It seemed like a simple task at first, as SDL simply wants a point to rotate things around. Different rotations however change the appearance (in terms of location) of sprites a lot, and I had to change my renderer culling code quite a bit. It all works very smoothly and nicely now, and I'm happy that I got to do some cool programming.
![Nothing special, just a big blade, on an arm.](/assets/WeeklyUpdates/26/SpinningBlade.gif)
Now, while I thought that I was done with the winter environment, I had to make some cool levels with these blades, and I might even add more later on. I think these add a lot of variety to levels, and I just love how dangerous and deadly they look. They also nicely improve the platforming aspect of the game. Here are a few screenshots of the new levels.
![You get the best screenshots while jumping.](/assets/WeeklyUpdates/26/BladeLevel1.png)

![You get the best screenshots while jumping.](/assets/WeeklyUpdates/26/BladeLevel2.png)
After the blades, I started the work on the desert environment. After a good amount of fighting with the tiles, I ended up with quite nice looking structure tiles for the desert environment. I have big plans for the environment, and I'm super hyped about it! The current plan is to have all the levels of the environment happen inside one huge pyramid.
![Those columns took a long time.](/assets/WeeklyUpdates/26/Desert.png)
Then I wanted to get started on the gameplay mechanics for the desert theme. I had the idea for a ferris wheel a while back, and I thought that it would probably be a good fit for the desert environment. While it took a while to get the platforms behaving properly, the implementation for the wheel was surprisingly simple. I can't wait to use these in actual levels!
![It's a long gif, so I apologize for the color quality.](/assets/WeeklyUpdates/26/FerrisWheel.gif)
That's it for the new visual stuff this week. Thanks a lot for reading!

*   Fixed blades burning
*   Fixed cutscene dialog bubble not hiding on early exit
*   Removed unused debug code
*   Added player data saving over level restarts
