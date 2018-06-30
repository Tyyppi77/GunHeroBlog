---
layout: post
title: "Weekly Update #31 - Prison Levels & Blog 3.10 - 9.10"
date: 2016-10-09 14:37:00
---
I don't have a ton of new awesome stuff to show this week, but there are some things that got done.

First of all, you are reading this post on an updated blog site for the game! The new site uses Jekyll to build the site from markdown post-files. This is a big improvement; the old site had all the posts hardcoded into two HTML files. It took a good few days to set everything up, from mining the old posts and converting them to the markdown format to setting up the deployment scripts and such. All in all, I'm quite happy with the change, and the site is now a lot more maintainable.

I spent the beginning of the week designing levels for the prison environment. The polished missile launchers inspired some nice level designs, and with those levels I was able to rise the prison level count to the target 25! Here's a screenshot of the level that I'm most proud of.

![Awesome prison level with rockets.](/assets/WeeklyUpdates/31/PrisonLevel.png)

I also spent a few days tweaking the behavior of the game's cutscenes. The cutscenes now have some special instructions that ask the player to press a button to continue the cutscene. For skipping the cutscenes there's a fast-forward feature now. Also, cutscenes aren't replayed now on level restarts, which should prevent the player getting frustrated at the game.

Thanks for dropping by! Have a nice week!

* Fixed level editor crashing due to missing lightmaps
* Fixed entity trap beam length
* Fixed enemies seeing trough tile walls
* Fixed truck not starting if a player was already on it while disarming a bomb
* Fixed level resizing in the level editor
* Fixed lava beams
* Replaced missile launcher supports with proper piping tiles