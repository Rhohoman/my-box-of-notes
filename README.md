# My Useful tips

## JS/REACT

## Algorithms - personal solutions

Sock Merchant - finding pairs of socks
https://repl.it/@rhohoman/Sock-Merchant

Fisherman Yates - shuffling array elements randomly
https://repl.it/@rhohoman/Fisher-Yates-shuffle-Algorithm

Counting Valleys - counting valleys following a path
https://repl.it/@rhohoman/Counting-Valleys

Repeating Strings - string is repeated infinite number of times count a occurances
https://repl.it/@rhohoman/Repeating-String


## Flexbox notes

Justify Content

    flex-start: Items align to the left side of the container.
    flex-end: Items align to the right side of the container.
    center: Items align at the center of the container.
    space-between: Items display with equal spacing between them.
    space-around: Items display with equal spacing around them.

Align Items

    flex-start: Items align to the top of the container.
    flex-end: Items align to the bottom of the container.
    center: Items align at the vertical center of the container.
    baseline: Items display at the baseline of the container.
    stretch: Items are stretched to fit the container.

Center of Page

    justify-content: center;
    align-items: center;

Flex Direction

    row: Items are placed the same as the text direction.
    row-reverse: Items are placed opposite to the text direction.
    column: Items are placed top to bottom.
    column-reverse: Items are placed bottom to top.

** changing the flex direction via reverse would also change other attributes like 'flex-start' to act like flex end and vice versa **

** when the flex direction is a column, justify-content changes to the vertical and align-items to the horizontal. **

Order

    order: 1;
    order: -1;

** Sometimes reversing the row or column order of a container is not enough. In these cases, we can apply the order property to individual items. By default, items have a value of 0, but we can use this property to also set it to a positive or negative integer value (-2, -1, 0, 1, 2). **


Align Self

    flex-start: Items align to the top of the container.
    flex-end: Items align to the bottom of the container.
    center: Items align at the vertical center of the container.
    baseline: Items display at the baseline of the container.
    stretch: Items are stretched to fit the container.
** This property accepts the same values as align-items and its value for the specific item. **

Flex Wrap

    nowrap: Every item is fit to a single line.
    wrap: Items wrap around to additional lines.
    wrap-reverse: Items wrap around to additional lines in reverse.

Flex Flow

    flex-flow: column wrap;

** The two properties flex-direction and flex-wrap are used so often together that the shorthand property flex-flow was created to combine them. This shorthand property accepts the value of one of the two properties separated by a space. **

Align Content

    flex-start: Lines are packed at the top of the container.
    flex-end: Lines are packed at the bottom of the container.
    center: Lines are packed at the vertical center of the container.
    space-between: Lines display with equal spacing between them.
    space-around: Lines display with equal spacing around them.
    stretch: Lines are stretched to fit the container.


## CSS Tricks and Useful links

Negative margins on static elements

https://www.smashingmagazine.com/2009/07/the-definitive-guide-to-using-negative-margins/#:~:text=When%20a%20static%20element%20is,right%20as%20you%20might%20think.

Transitions and Transforms

https://thoughtbot.com/blog/transitions-and-transforms

Cubic Bezier

- helps manage the speed of transitions in 4 intervals

https://www.w3schools.com/cssref/func_cubic-bezier.asp