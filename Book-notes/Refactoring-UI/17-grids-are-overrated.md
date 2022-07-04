# Refactoring UI
- **Author:** Steve Schoger, Adam Wathan
- **Genre:** Design

# Grids are overrated
Using a grid system will keep your UIs simple and clean but not all elements should be designed with a grid system.

The problem with treating grid systems like a religion is that there are a lot of
situations where it makes much more sense for an element to have a fixed
width instead of a relative width. 

If you make the screen wider the sidebar gets wider too, taking up space that could’ve been put to better use by the main content area. Similarly, if you make the screen narrower, the sidebar can shrink below its minimum reasonable width, causing awkward text wrapping or truncation.

Don't unnecessarily shrink your elements and don't be a slave to the grid system. If your elements need 600px of space to look good then give it the required space.

#Books #refactoring-ui 