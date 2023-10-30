# # Class Three Readings
## Links  
[Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)  
[Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)


## Things I want to Know More About
*I would like to explore all of the possible bullet styles. Can you create your own style?*  
*How can we use CSS box models to apply to JS controlled elements like buttons? Can we use these properties to determine where prompts and alerts appear?*


## Section 1: Learn HTML
1. When should you use an unordered list in your HTML document?  
* You should use unordered lists when you would like the elements in a document to be listed in (default) bullet points. They will not be ordered numerically. Use these if the order is not meaningless.
2. How do you change the bullet style of unordered list items?  
* To change the bullet style in HTML utilize the CSS file associated with the HTML file. Use the `list-style-type` property.
3. When should you use an ordered list vs an unorder list in your HTML document?  
* Use ordered lists when the order is meaningful. To determine if the order matters, mix the lists items around in an unordered list and see if it changes the meaning you wish to convey.
4. Describe two ways you can change the numbers on list items provided by an ordered list?
* To change the numbers you can utilize the `type=` specification  
    * To use Roman Numerals use `<ol type="i">`
    * To choose the number for which the list begins (Instead of starting at one) use the start attribute: `<ol start="[insert number to start counting with]">`
## Section 2: Learn CSS
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”? 
#### The Box Model
Once upon a time there lived a royal family in a great castle. They lived within the kingdom of Cascade in the Northernmost part of Europe. Their castle was surrounded by a great forest (*margin*), full of scary creatures, a place that no one dared to journey into alone. To protect themselves from the forest, the castle lay in the middle of a walled off city (*border*). However, they didn't know if these monsters could climb, and worried of the possibility that they may be able to scale the outer wall. So, the royal family created a great moat (*padding*) surrounding the innermost part of the city where the townspeople and royalty resided. Within the moat were great serpents. They reasoned that these monsters couldn't possibly fight in the water, AND climb walls.   
2. List and describe the four parts of an HTML elements box as referred to by the box model  
* Content Box: This is where content is displayed and has properties such as inline size and block size, along with height and width properties.
* Padding Box: This element sits around the content and serves as whitespace. Use the `padding` property to determine this size.
* Border Box: The border box wraps the content *and* the padding. This border can be specified using `border` and related properties.
* Margin Box: The margin box is the outermost part of the box model and wraps all the other boxs. This controls how the entire box is in relation to other boxes/elements on the page. Use the `margin` properties to specify this.
## Section 3: Learn JS
Array: List like objects that can store multiple values in a single object 
* Stored in vartiables and dealt with same as values, but can access singular values.
* Within arrays we can mix data types.
* To add items within an array use `push`  

Example Array Code: 
  `const cities = ["Manchester", "Liverpool"];`
`cities.push("Cardiff")`;
`console.log(cities)// would return "Manchester, Liverpool, Cardiff`  
*Note multiple items can be added withibn a single push for example* `cities.push("item 1", "item 2")`

