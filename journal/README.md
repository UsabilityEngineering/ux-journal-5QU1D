# Drawing Vectors on a Tablet
### By Syd Ainsworth

I am, if nothing else, a huge nerd who happens to like digital art. It would make sense, then, that my senior project combines those two things: a map renderer, which I would draw the tileset for. The project did, however, drive me out from my art program of comfort and in search of something that was 1) able to produce vector image files of good quality, and 2) *free*. [Enter Inkscape]( https://inkscape.org/).

![app launch screen](assets/Picture1.jpg)

From launch, Inkscape mimics the familiar interface of Adobe’s Photoshop. So when I got to the canvas and was greeted by such a familiar interface: art tools on the left, program tools up top, menus above that, and panels (such as layers and advanced color and brush tools) on the right. I figured I was in for a smooth transition between programs. Not so!

I drew a quick test scribble to get the feel for the default pen. I trusted a combination of **convention** (aka **consistency and standards**), as well as **matching the system to the real world**, [two of the ten usability heuristic principles] (https://www.nngroup.com/articles/ten-usability-heuristics/), in identifying the pen by its icon and making some assumptions about how it would behave.

![image of an s-like shape and two lines coming off it, the left line and s with a black fill](assets/Screenshot4.jpg)

When you’re expecting a line starting where you first put your pen tip down on the screen and ending where you lifted your pen, getting something like the above animation might be cause for minor alarm.  The is doubly true because all of what I wanted to draw in this program was line art, which is to say nothing was meant to have a fill.

My first instinct was to assume that I had perhaps chosen the wrong tool. As I was using my stylus, and not the trackpad, I hovered my stylus tip over the screen at the tool to see details in the tooltip, similar to how I would mouse over it to get details; this is a common feature of most applications, regardless of application purpose. So my **mental model** didn’t fully match the **conceptual model** of the application’s feedback. (I later discovered that mousing over tools *does* produce a descriptive tooltip, so this is a tablet-specific issue.) However, no tooltip appeared. And as I didn’t have a mouse connected to my tablet at the time, it appeared that I had no way of getting information about the tools. The app was absent some rather important and relevant **feedback**.

It took me five or six minutes of poking around the right-hand side panels to determine that the issue was a fill setting, and not that I had chosen an entirely incorrect tool.

The learning curve of the app wound up being higher than anticipated, with additional features responding differently than I anticipated. I spent an hour attempting to draw simple line art for mountains and a simple tent-based settlement (tiles I need for my project) but was unhappy with the results of every attempt. I ended up switching back to my original art program, saving a PSD (Photoshop document), and using Photoshop to convert the layers into individual SVG files.

I might come back to Inkscape another time, but at current, I found the product unsatisfying to use.
