---
layout: post
title:  "Weekly Update #29 - Desert Features & Level Selecting 19.9 - 25.9"
date: 2016-09-25 17:22:00
---
I had a pretty productive week, and now that my Swedish final is over I have more time to spend on the game!
First off all, I have some new desert stuff to show. I made a new level in the beginning of the week, and today I added rising platforms that will allow me to make some small jumping challenges. Here you can see a screenshot of the new level and the rising platforms in action.
![The new level uses a combination of ferris wheels and moving platforms.](/assets/WeeklyUpdates/29/DesertLevel.png)

![Time your jumps carefully!](/assets/WeeklyUpdates/29/Platforms.gif)
I spent most of the week fixing bugs, mainly bugs related to elevators. As I had gotten vertical moving platforms working very smoothly, I wanted to translate that behaviour onto the elevators. I was able to do that very nicely, and now elevator riding is a lot smoother! And the crushing code is a lot cleaner! To test the elevators, I had to play a level with an elevator, that happened to be quite far in the level selection menu. So, I got this idea of somehow improving the level selection menu. I decided to implement a grid based menu screen, that will allow faster navigation. To accomplish this, I had to do a small refactor on the code that managed menu selection movement, but all in all I was able to implement the menu in a clean way. In the future, I should be able to reuse this menu screen for custom levels!
![Look at the beautiful grid!](/assets/WeeklyUpdates/29/LevelMenu.png)
That's it for this week! Thanks for reading!

*   Added an item to the pause menu that allows opening the current level in the level editor
*   Increased the main menu logo size
*   Fixed temple doors at narrow roofs
*   Fixed character's dying in lava crashing the game
*   Fixed ice sliding
*   Fixed god mode health state
*   Added support for different scale origins
