# Star Wars Scroll Text

We have a black background with multiple "stars" which are actually tiny divs colored a translucent white. They have randomized sizes, placements and opacities. The code for this is fairly straightforward.

The real meat of the code is the **Scroll Text**. A div is placed in the middle of the screen, with some yellow text scrolling vertically upwards every few seconds.

An **overlay** is played over the scroll text div. It has a gradient background, from solid black to fully transparent, then back to solid black. This provides the illusion that the yellow text is fading in and out.Lastly, the scroll text div is rotaed by the Z-axis.
