# Refactoring UI
- **Author:** Steve Schoger, Adam Wathan
- **Genre:** Design

# Create a spacing and size system
Don't waste your time on deciding how many pixels should the margin and padding of an element be. Decide these values beforehand and limit yourself to only use them as they won't create any inconsistencies in your design.

For a system to be truly useful, it needs to take into consideration the relative
difference between adjacent values.

A simple approach is to start with a sensible base value, then build a scale
using factors and multiples of that value. 16px is a great number to start with because it divides nicely, and also happens to be the default font size in every major web browser.

This way you'll greatly increase your workflow and your designs will look more consistent.

#Books #refactoring-ui 