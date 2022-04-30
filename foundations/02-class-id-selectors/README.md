# Class and ID Selectors
Knowing how to add class and ID attributes to HTML elements, as well as use their respective selectors, is invaluable. It's important to practice using them.

There are several elements in the HTML file provided, which you will have to add either class or ID attributes to, as noted in the outcome image below. You will then have to add rules in the CSS file provided using the correct selector syntax. Look over the outcome image carefully, and try to keep in mind which elements look similarly styled (classes), which ones may be completely unique from the rest (ID), and which ones have slight variations from others (multiple classes).

It isn't entirely important which class or ID values you use, as the focus here is on being able to add the attributes and use the correct selector syntax to style elements. For the colors in this exercise, try using a non-keyword value (RGB, HEX, or HSL). The properties you need to add to each element are:

* **All odd numbered elements**: a light red/pink background, and a list of fonts containing `Verdana` and `DejaVu Sans` with `sans-serif` as a fallback
* **The second element**: blue text and a font size of 36px
* **The third element**: in addition to the styles for all odd numbered elements, add a font size of 24px
* **The fourth element**: a light green background, a font size of 24px, and bold

Quick tip: in VS Code, you can change which format colors are displayed in RGB, HEX, or HSL by hovering over the color value in the CSS and clicking the top of the popup that appears!

> ### Note:
> Part of your task is to add a font to _some_ of these items. Do not worry about the font of the rest of them. Your browser's default font might be different than the one displayed and that's OK for this exercise.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the odd numbered `p` elements share a class?
- Do the even numbered `div` elements have unique IDs?
- Does the Number 3 element have multiple classes?

### Learning points:
- Used font instead of font-family. Font can be used, but has more specifications than font-family, such as size and color. Use font-family when specifying multiple of just the font types.
- played around with the inline css before adding it as a class. It didn't seem necessary to add a whole new class for just one small change, but did it using a class in the end because it's what the assignment asked for. 
- classes are used for multiple elements you want to style with the same properties. IDs are used to style one specific element, usually when trying to distinguish them from other elements of the same type. 