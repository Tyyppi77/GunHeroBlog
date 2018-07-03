---
layout: post
title:  "Weekly Update #16 - Lighting & fixes 7.6 - 12.6"
date: 2016-06-12 14:52:00
---
It's time for another weekly update! It was the first week of summer holiday, and I think I got some nice progress done. Plenty of bugs got fixed, and the look of levels got improved by a lot. Let's roll!
Last week I showed content from the new bomb level mode. I continued to work on the bomb mode in the beginning of the week, and I recorded some footage from the bomb level. Check the video out below.

<div class="embed-responsive embed-responsive-16by9"><iframe allowfullscreen="allowfullscreen" class="video" frameborder="0" height="50%" src="https://www.youtube.com/embed/sjIMctBBako?showinfo=0&rel=0" width="100%"></iframe></div>
The biggest addition to the game this week is definitely the lighting. I now generate a tile-based light map for each level, and render the lightmap with interpolation on to achieve smooth lighting. It's not perfect, but it's probably the best result I can reasonably achieve with SDL2, as it sadly lacks support for shaders. The actual lighting implementation was pretty easy, the hardest part was to get the light value calculations correctly. Here you can see the lighting, first in a new level I made this week, with complete underground action, and then in another level. I especially like the lighting in these cave like terrain areas.
![What's going on in these tunnels?](/assets/WeeklyUpdates/16/Lighting1.png)

![Kinda spooky, isn't it?](/assets/WeeklyUpdates/16/Lighting2.png)
Finally, I made a pretty cool gif, that works pretty well as the thumbnail of the game. Something like this would be an awesome box art image for the game's Greenlight campaign that I hope to launch soon. That concludes the update of this week, thanks for dropping by!
![How long is this level?!?](/assets/WeeklyUpdates/16/Thumbnail.gif)
Here's the changelist:
*   Fixed multiple switches not syncing with their door
*   Fixed gun direction based position lag
*   Fixed cutscene cleaning
*   Fixed camera positioning after level completion
*   Fixed sprite bounding box not accounting for scale
*   Fixed elevator roofs
*   Fixed trampoline bouncing when walking over
*   Fixed level selection menu positioning
