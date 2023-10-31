# CSS Layout

## What I want to know more about:  
* Can you use flex properties on images as well?  
* Does flex generally solve many of the problems that come with different screen sizes and display of web pages?   
* How can the concerns about accessibility be relieved?

## Flexbox [Flexbox Guide](https://web.dev/learn/css/flexbox/)
*Flexible Box Layout Model* (Flexbox): excels at taking a bunch of items with different sizes and returning the best layout for those items. Allows for flexibile boundaries when viewport size may vary.  Can display as a row or column.
* Main Axis: Set by `flex-direction` property. Flex items move as a group along this axis.
* Cross Axis: Runs in the other direction to the main axis.  
**Utilizing the Flex Box**  Example:  
1. Create a container with multiple items in an HTML Document
2. To declare the flexbox declare using `.container` and change the display property to '`flex`
* To control the direction of items, add the `flex direction` property and one of the values: `row`, `row reverse`, `column`, `column-reverse.`
* Note when using row and column reverse, that reordering the visual display may make the logical order inaccessible if the content is jumbled, and someone is using a screen reader to read the content aloud.  

## CSS Layout [MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
* Flexbox allows for tasks such as vertically centering a block inside of a parent, allowing equal width/height within children of containers, and making columns in multi-column layouts the same height regardless of content.
* Flex Direction `row` makes the main axis run in the default direction the browser language works in (left to right in english broswer).
* Flex wrap: Ensures children are not overflowing parent element. `flex-wrap: wrap;`  
*  Flex: `flex` declarations detail the minimum width for each element. Example: `flex: 200px` would mean that the content has to be at least 200px wide.
