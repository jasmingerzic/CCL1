11.02.2025
Today I started the project,I set up my gitlab. Set up HTML, CSS, and JS files and got a basic canvas working. 
Made a green square that moves with WASD keys. Tomorrow I'll work on grid-based movement like the original snake game.

12.02.2025
Today I got the grid movement working - snake now moves in 40x40 squares instead of smooth movement. Added a timer so 
it moves every 0.2 seconds. Also made the snake body work as an array of segments. Tomorrow I'll add the vitamins.

13.02.2025
Created the Vitamin class and got them spawning randomly on the grid. Collision detection works but it is buggy, collision 
gets detected even if snake is away 80px from the vitamin square- snake eats vitamins and they respawn. Started the
color-changing mechanic. Tomorrow I'll  try to fix collision and implement grow/shrink based on matching colors.

14.02.2025
I fixed the collision bug by making the vitamin smaller but visually it remained the same. Implemented the main mechanic: matching 
colors = grow + 10 points, wrong colors = shrink - 10 points. Added scoring display. Had some bugs with the tail removal but fixed 
it. Tomorrow I'll add speed increase and edge wrapping.

15.02.2025
Added speed increase, snake gets faster every 2 correct vitamins that she eays. Implemented edge wrapping so the snake appears on 
opposite side when going off screen. Took a while to get the grid alignment right. Tomorrow I'll work on collision and game over.

16.02.2025
Got self-collision working, snake dies if it hits itself. Made a game over screen with final score and restart button. Fixed a bug 
where pressing keys too fast made the snake turn 180° and die instantly. Tomorrow I'll add walls.

17.02.2025
Created Wall class and added 2 walls. Snake dies when hitting them. Fixed the double-key bug with a direction lock flag. 
Tomorrow I'll start drawing the actual graphics.

18.02.2025
Spent the day in Photoshop making snake head graphics for all 4 directions in green. Made body and tail too. Got the images loading 
and displaying in the game instead of colored squares. Not too happy with how it turned out but if I have extra time I will try to redraw it.
Tomorrow I'll make graphics for the other colors.

19.02.2025
Drew all the snake graphics for red, blue, and black - took forever but used color replacement to speed it up. Also made pulsating apple images 
for vitamins. Everything switches colors properly now. I have 2/4 vitamins drawn. Tomorrow I'll add the background and mouth animation.

20.02.2025
Made a grass background in Photoshop. Created open-mouth versions of the green snake heads. Mouth now opens when the 
snake gets close to vitamins.(Only works for green snake, didn't draw for other colors yet) Tomorrow I'll work on the tongue animation.

21.02.2025
Made the tongue animation - drew 9 images total (small, medium, and long versions). Animation plays when eating vitamins. Had some trouble 
with positioning but got it working by changing offset to 40. Tomorrow I'll make the main menu and more fruit images.

22.02.2025
Created main menu with a background image and start button. Made pulsating red fruit images like the green apples. Updated vitamins to use fruit 
images instead of squares. Tomorrow I'll clean up the code and test everything.

23.02.2025
Went through all my code adding comments and removing old stuff I wasn't using. Did a lot of testing to find bugs. Adjusted the speed increase to 
feel better. Tomorrow I'll do final testing.

24.02.2025
Final day - tested everything multiple times to make sure it all works. Fixed minor bugs and adjusted the game over screen styling. Made sure 
all animations work smoothly. Few things are missing but bcz I was short on time, and didn't plan it properly, few things are missing, but basic things 
are done.
