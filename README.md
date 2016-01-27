# Computer Science
 Created for my "Exploring Computer Science" class for Mr. Z. 
 Website can be found @ http://spencer.ga/sandbox/ and http://spencer.ga/throne/.
 First time using PHP for anything 'real', so it's not the cleanest or most advanced code there is.
 Experimented a bunch with CSS Animations (new to me) as well, and some jQuery stuff along with it.

#Throne
Created because this game receives frequent updates and I have some old versions saved that I want to be able to find or play again. The game is called "Nuclear Throne" and is created by Vlambeer.

/throne/ reads off of a local database to get everything in that table; version number, an icon (if it's not the default icon, which is "patience.png" and is a clock), the name of the update, a downloadUrl (if it's different from the version number, which is default), and extra notes about the build. The information is echoed into a table.

#Sandbox
The sandbox was originally created to experiment with CSS Animations, since I've wanted to do that for a while (my original goal was to learn how to make snow on a website without doing something like creating a gif and tiling it, I have not done it yet but plan to pursue that in 2nd semester). After learning how to do CSS Animations, I combined that with some jQuery/JS to create page loading animations, then I realized I could use it to make a menu. I made the hamburger (three lines on the top left) menu, animated it with css animations, and handled opening/closing in the JS. 

After finishing animations/the menu, I wanted to do more. I was looking into using PHP after completing the throne website, and after being annoyed that I had to update an element on my page multiple times so that it was consistent across all pages, I realized I could automate the process with PHP. I made a file require a bunch of other files that echo information that is always consistent across all pages, but customize some things like the active tag (which was a lot more work to get working than I thought it would be) and the content of each page. 
