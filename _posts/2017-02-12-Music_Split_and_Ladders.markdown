---
layout: post
title: "Weekly Update #46 - Music Split & Ladders 6.2 - 12.2"
date: 2017-02-12 12:18:00
---

This week I got some nice progress done! Let's get right into it!

In the beginning of the week I split up the soundtrack of the game and made it so that each level of the game campaign has a song dedicated to it. I think this nicely splits up the game progress and displays campaign advancing with the background music. The implementation required some minor tweaks in the campaign management but for the most parts it was a really clean transition.

I've also made ladders behave a lot nicer. First of all, I added a helper entity to the top of the ladders, that guides the player that's slightly offset from the ladder opening to the ladder from above. This makes ladders feel a lot better, as going down ladders was quite tricky.

![The player is slid towards the opening in the floor.](/assets/WeeklyUpdates/46/Helper.gif)

I was also requested to support jumping on ladders. At start I was a little sceptical but after the first rough implementation I was really satisfied with the end-result. I can't believe I didn't implement it before. It did require some tweaks in the scary and messy player logic code but the end result is just really awesome and makes the ladders feel a lot more satisfying.

![Hop, climb, hop, climb, hop, climb...](/assets/WeeklyUpdates/46/Jumping.gif)

That's pretty much all I wanted to write about this week. The game is coming together really nicely!

* Fixed loot box weapon spawn layer
* Fixed boss bullets not destroying on death
* Fixed player weapon in the final cutscene
* Fixed forest entrance cutscene trigger
* Fixed burst weapon cooldown
* Normalized soundtrack volume