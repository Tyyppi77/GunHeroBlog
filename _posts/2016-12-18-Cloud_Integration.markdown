---
layout: post
title: "Weekly Update #41 - Cloud Integration 12.12 - 18.12"
date: 2016-12-18 12:54:00
---

Christmas break is approaching fast, so I was extremely busy with school work this week. I did however manage to do some Steamworks integration at the end of the week.

As a nice and small introduction to the Steam API I decided to implement cloud syncing to the game. After figuring out how the Steam Remote Cloud system works the implementation was quite straight forward. Basically, I just download the content from the cloud and overwrite the local files with the cloud data. This worked just fine, but I also had to take the case where the user plays the game offline into account. It would be extremely annoying if I were to overwrite the user's progression with an earlier save file. So, I also need to do a save date check with the files, and only overwrite if the date on the cloud is more recent than the local data.

That's it again, these weekly updates just keep on getting shorter and shorter... Maybe it means that the game is getting more and more ready? Anyways, I'm not sure if I'll write an update next week or if I'll save my Christmas break stuff for a larger post. We'll see. Thanks for dropping by, and happy holidays!

* Fixed game config not saving on config menu exit
* Fixed game saves not changing properly
* Fixed right mouse button not decrementing value selectors
* Fixed interpolating menus accepting input
* Renamed all levels to have more interesting names