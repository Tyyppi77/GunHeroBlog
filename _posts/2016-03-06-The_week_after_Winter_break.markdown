---
layout: post
title:  "Weekly Update #2 - The week after Winter break 29.2 - 6.3"
date: 2016-03-06 16:54:00
---
A week has passed and it's time for another weekly update. As this week was school again, the progress is not as impressive as last week's, but I think I still made some very nice progress on the game.
In the beginning of the week I worked on improving the prison theme. I added new structure and dirt tiles for the terrain, and I also added some prop tiles, such as fences and a new ladder type.
![The new prison theme.](/assets/WeeklyUpdates/2/PrisonTheme.png)
I had already though that adding new brushes to the editor had been a little too tedious, as even the most simple single-tile brushes had required a separate class to be created, I decided to refactor the brush system in the level editor. For an example the new pipe brush that uses 4-bit tile masking underneath to create smooth pipelines can be created with the following (long) line of code:
{% highlight c++ %}
AddBrushData("PrisonPipeBrush", "Prison Pipe", new SLevelEditorBrushInfoMasker(ELevelEditorTileType::FOREGROUND_PIPE_PRISON, ELevelEditorTileLayerType::BACKGROUND_PROP, 1170));
{% endhighlight %}
I also added level resizing to the level editor. At first implementing resizing seemed quite a hard task, but in the end I only really had to implement a few small utility methods to the tile layer and to the QuadTree classes. GunHero uses QuadTrees for managing pretty much everything in the levels, mainly because they allow for fast querying of data from them. Here you can see the level resizing in action:
![A test level gets resized really quickly.](/assets/WeeklyUpdates/2/LevelResizing.gif)
The next bigger feature I worked on was adding tooltips to the level editor, hence making it a little more user-friendly. The tooltip implementation is simply a modified label with a timer setup to display it.
![Hovering on buttons in the level editor now displays more or less helpful tooltips.](/assets/WeeklyUpdates/2/EditorTooltips.gif)
Saturday was as expected the most productive day for me. I spent the morning improving the horrible in-game GIF-recorder UI. The old one only allowed selecting an area to record by manually clicking the two corners of a rectangle. The new design removes unnecessary buttons from the top-left corner that obscured the game view with a simple draggable box. I enjoy the new UI a lot more and it is way easier to capture cool gameplay gifs with this new interface.
![The new interface allows resizing and moving the clip area.](/assets/WeeklyUpdates/2/GifClipEditor.gif)
After I was finished with the recording interface I started drawing an elevator for the prison levels. While I got a cool sprite drawn quite quickly and the basic elevator movement was nothing hard to program in, I really struggled with getting the player move smoothly with the elevator platform. I continued working on that today (Sunday), but currently I have been unable to get a glitch-free implementation working. I had to add support for multiple collision volumes per entity to be able to collide with both the top and the bottom of the elevator. Here you can see a tall animation of the elevator:
![Currently the elevator moves between the floor and the roof with a small pause at each end.](/assets/WeeklyUpdates/2/ElevatorMovement.gif)
I will also include a list of smaller tweaks and bug fixes I did this week for those interested.
*   Fixed camera shaking out of level bounds on explosion shakes
*   Fixed unwanted entities showing in thumbnails
*   Fixed tile cursor showing behind UI in the level editor
*   Fixed player movement stopping when keys are pressed and released almost at the same time
*   Fixed a critical crash on rect objects
*   Fixed player getting stuck on ladder tops
*   Added level session time label to level view
*   Added code to load circle colliders from XML data-files
*   Added a quicksave keybinding (Ctrl-S) to the level editor
*   Improved the animation system accuracy
*   Changed loading progress bar text from "Progress" to the more descriptive "Loading"
Thanks for your interest. I hope you have a nice week ahead!
