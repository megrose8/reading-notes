# Dynamic Web Pages with JavaScript  
*Key Questions:*   
1. What are variables in Java Script?
2. What does it mean to `declare` a variable?
3. What is an assignment operator, and what does it do?
4. What is information received from the user called?     

**[Intro to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**
+ JS supports object-oriented, imperative, and declaritive styles.
+ Capabilities include:   
    + Dynamic Script Creation `eval`
    + Object intro spection `for...in`
    + Source-code recovery `toString()`
+ Javascript NOT ~~java~~   

**[Basic Output](https://code-maven.com/introduction-to-javascript)**  
3 Parts to JavaScript:
+ The language itself
+ DOM API: How language interacts with other parts of the webpage.
+ Server API: Provided by Node.js or other server side systems 

Input/Output:
+ Output: What the user will see displayed
+ Input: What JavaScript needs to receive to create a given output

Embed or include: 
+ Embed directly into HTML file
    + `<script> and </script>`  
+ Link to JS file in the HTML file  (include) 

*Examples*  
 
**alert.** Creates a new window with "hello world" when clicked on:  
` <script language="javascript">`  
`alert("Hello World");`  
`</script>`  
**document.write** Document write changes the content of the age inserting after the first line, but before the last line.
`First Line`  
`<script>`
`document.write("<h1>Hello World</h1>");`  
`</script>`  
`Last line`
**prompt** Shows a pop up window with text for first parameter and text box. Once okay is pressed, it reutnr the given prompt () function. Combined with document.write to update html.  
`<script>`  
`var name = prompt("Your name:", "");`  
`document.write("Hello", name);`  
`</script>`  
**confirm** Allows developer to ask a yes/no question. Translates into: If confirm returned true, print "Hello World", otherwise print "Ok, I won't print it."  
`<script>`  
`if (confirm("Shall I print Hello World?")){ `  
`document.write("Hello  World");`  
`} else {`  
`document.write("Ok, I won't print it.");`  
`}`
`</script>`

+ Variables are Containers for Storing Data, it can be declared four ways:
    + Automically
    + Using `var`
    + Using `let`
    + Using `const`


