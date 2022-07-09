# Refactoring UI
- **Author:** Steve Schoger, Adam Wathan
- **Genre:** Design

# Establish a type scale
If your design team doesn't have a design system which defines the font-faces, weight, and size of the text in your UIs you are going to have a hard time deciding how should should text look like in your design which leads to inconsistent designs and slow workflow.

A linear scale won't work when selecting font-sizes.  Sixteen pixels is the default font size for modern web browsers, start with it and multiply it to effectively get the perfect font-size for your headings and other text. Or you can just hand pick font-sizes for each text element in your UI.

When you’re building a type scale, don’t use em units to define your sizes. Because em units are relative to the current font size, the computed font size of nested elements is often not actually a value in your scale.

You can use pixels or rem units instead.

#Books #refactoring-ui 


