# Class 1 Readings:
## Links:   
*Readings*  
[ How the Web Works ](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)  
[ Web Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)  
[ Java Script Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)  
[ Introduction to HTML ](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)  
[ Getting Started with HTML ](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)  
[Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)  
[ Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)  
[How to Design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Design_and_accessibility/Thinking_before_coding)  
[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)  
[What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)  
*Projects*  
[Link to Prompt Engineering Page](prompt-engineering.md)

## Things I want to Know More About
How do independent contractors get hired to "increase SEO"? I've come across these people in B2B spaces. Are they software engineers? 

## Section 1: Getting Started
1. Compose a short poem describing how HTTP sends data between computers.
(she:clients, he:servers)   
*she speaks to him*   
*translated in a language known by many,*  
*requesting his help,*
*in this moment it is special between them*  
*upon hearing her words he returns,*  
 *carrying in his arms everything she desires* 
2. Describe how HTML, CSS, and JS files are “parsed” in the browser.  
    1. HTML is parsed first
    2. Any linked files are recognized
    3. Requests for any CSS and JavaScript files are sent to the server
    4. Browser creates a DOM tree from CSS, generates CSSOM structure from CSS, and compiles/executes the JS
3. How can you find images to add to a Website?   
To find images that are not under copyright, use Googles license filters in tools and choose creative commons licenses.
4. How do you create a String vs a Number in JavaScript?  
* STRING: Sequence of text enclosed by ' '
* NUMBERS: No ' ' just type the number.

5. What is a Variable and why are they important in JavaScript? Variables are containers that store values. You declare a variable first, and then can replace that variable with other values as you continue coding. Variables allow for different types of data that can be reused and reexecuted throughout the code. They allow for dynamic changes in websites such as personalizing greetings or changing images to be displayed.

## Section 2: Introduction to HTML 
1. What is an HTML attribute?   
An attribute contains extra informstion about the element that will not appear in the content.
2. Describe the Anatomy of an HTMl element.  
opening tag <> the content </> closing tag
3. What is the Difference between article and section element tags?  
* Article: Encloses a block of related content that makes sense on its own
* Section: Grouping together a single part of the page that is one single piece of functionality. (Mini-map, set of article headings, etc.)
4. What Elements does a “typical” website include?  
` Elements within an HTML website may include: head tags, header, nav, main, paragraph (< p >) headings (< h1 >), article, main, footer, body, and link tags` 
5. How does metadata influence SEO?  
Within metadata, in the meta element is the descrtion of a website. By utilizing keywords relating to the content of your page in the descrption, one can appear higher in relevant search results.  
EX:  
 `<meta`  
   `name= "type of meta element"`  
    `content= "content description with SEO keywords"` `/>`
6. How is the <  meta > HTML tag used when specifying metadata?  
Meta tags may specify: 
* Document's character encoding `<meta charset="utf-8"/>`
* Name  and content: Help to define author of the page and concise description of the page. (See Above)
* Proprietary creations: Provide sites with specific pieces of information they can use.
* Custom Icons

## Section Three: Misc
Designing a Website:  
1. What is the first step to designing a website? 
    * The first step is to ask questions surrounding project ideation. Such as: What do I want to accomplish? How will a website help me reach my goals? What needs to be done and in what order to reach my goals.
2. What is the most important question to answer when designing a website?
    * What do I want to accomplish?

Semantics:  
1. Why should you use an h1 heading over a span element to display a top level heading?
    * Using H1 gives the title a meaning with semantic value, as it gives the text a role or meaning. Further it will render automatically as a larger font to give it the size of a heading.
2. What are the benefits of using semantic tags in our HTML?
    * Helps with SEO keywords
    * Screen readers can read them as signposts to increase accessibility.
    * Helps when looking for meaningfull blocks of code
    * Suggests to the developer the type of data to be populated
    * Mirrors proper custom element/component naming

What is JavaScript:   
1. Describe two things that require JavaScript in the Browser
    * Validation of user input: JavaScript can validate HTML forms to ensure correct data before data is submitted to a server. EX Emails, fields are filled out, etc.
    * Dynamic Page Content: JavaScript allows for interactive web pages and additions of things like image sliders, live chat, notifications, etc.
2. How can you add JavaScript to an HTML Document?
    * JavaScript can be added using internal script tags or you can link a js file in the head of the HTML document.

