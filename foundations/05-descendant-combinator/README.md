# Descendant Combinator
Understanding how combinators work can become a lot easier when you start playing around with them and see what exactly is affected by them versus what isn't.

The goal of this exercise is to apply styles to elements that are descendants of another element, while leaving elements that *aren't* descendants of that element unstyled.

You can use either type or class selectors for this exercise; use whichever you may feel you want to practice with more. The HTML file is set up (so no need to edit anything in it) such that any combination of selectors will work, so if you're feeling adventurous you can even try combining a type *and* class selector for the descendant combinator.

The properties you need to add are:

* Only the `p` elements that are descendants of the `div` element should have a yellow background, red text, a font size of 20px, and center aligned.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the elements that contain the text "This should be styled" have the correct styles applied?
- Do the elements that contain the text "This should be unstyled" have no styles applied?

### Things I learned
- This lesson didn't even need to use a combinator to style the things that needed to be styled, which tells me that child elements probably inherit their ancestors' properties. I still used the combinator though because it's what the assignment asked for. 
- Classes weren't even needed for this assignment because it could've been done simply using "div p {}" 