# Class Two Readings
## Links  
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)  
[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)  
[ How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)  
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)  
[Making Decisions in Your Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)  
[Bookmarks and Review](https://cbea.ms/git-commit/)

## Things I want to Know More About


## Section One HTML: 
1. Why is it important to use semantic elements in our HTML?  
Semantics allow for increased accessibility for people using screenreaders and increase readibility of the code itself.
2. How many levels of headings are there in HTML?  
There are 6 levels of headings in HTML `<h1>` through `<h6>`
3. What are some uses for the `sup` and `sub` elements?
* Sub: Superscript text for example the periodic element for water "h2O" would need subscript. HTML would appear `H<sub>2</sub>O`  
* Sup: Superscript or something above the baseline. This could be used for mathematical exponents or to denote footnote citations. For example of a mathematical equation: E=MC2 would need to use `E=mc<sup>2</sup>`
4. When using the `abbr` element, what attribute must be added to provide the full expansion of the term?  
The `abbr` element is used to wrap around acronyms or abbreviations. Add a full expansion of the term in plain text with abbr to markup the abbreviation. To provide a full expansion use `<abbr title= [full]> [Abbreviated.]</abbr>`

## Section Two: CSS
1. What are ways we can apply CSS to our HTML?   
Both in head: 
    * Linking External Style Sheet `<link rel="stylesheet" href="style.css"/>`
    * Internal stylesheet:   
    `<style>`  
    `h1{`  
        `color": blue;`  
        `}`  
    `</style>`
2. Why should we avoid using inline styles?  
Inline is the least efficient way to use CSS when maintaining a page. Further, it makes reading code in HTML more difficult.
3. Review the block of code below and answer the following questions:  
    * What is representing the selector? `h2{ `
    * Which components are the CSS declarations? `color & padding`
    * Which components are considered properties? `black and 5px`

## Section 3: JavaScript
Basics:  
1. What data type is a sequence of text enclosed in single quote marks? *string*
2. List 4 types of JavaScript operators. 
    * `+` Addition or combining two strings
    * `=` Assigns a value to a variable
    * `===` Strict equality. Returns a true/false result
    * `!` Not. Initial expression is true, but comparison is false.
3. Describe a real world Problem you could solve with a Function    
    * Training a dog with commands. In this situation you teach the dog the command "sit" so that the dog eventually knows what action to execute when you call "sit"

Making Decisions in Your Code: 
1. An if statement checks a *condition* and if it evaluates to *true*, then the code block will execute.
2. What is the use of an else if?   
`Else...if` is used when one wants more than two outcomes. Each additional choice has an additional block to put between if and else.
3. List 3 different types of comparison operators.    
    * `===` Tests if a value is identical to another
    * `< and >` Tests if a value is less than or greater than 
    * `<= and >==` Tests if less than/greater than or equal to
4. What is the difference between the logical operator && and ||?
    * `&&` represents AND and is used to chain expressions together to ensure *all* evaluates to true for entire expression to be true
    * `| |` represents OR and allows to chain expressions and reutrn true if there is *one or more* to return true. 
