# Class 7: Programming with Java Script
*Key Questions*  
1. What is control flow?
2. What is a JavaScript function?
3. What does it mean to invoke - or call - a function?
4. What are the parenthesis () for when you define a function?

**Control Flow**: The order in which the computer executes statements in a script. Example code is run first to last in lines, **except** when computer runs into things such as conditionals and loops. (*Example* Conditional structure of if...else.) Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.

**Functions in JavaScript**: A block of code designed to perform a particular task. It is executed when it is called. Code snippet that can be called by other code or itself, or a variable that refers to a function.
+ Function name: Identifier included as part of function declaration/expression. 
+ When functioned called, arguments are passed to it as inputs and can optionally return a value.
    + To *Call* the function means to trigger the function when "something" (the user perhaps) invokes it- triggering the operation of said function. 
    Functions may be invoked when...
        + When an event occurs (user clicks a button)
        + Called (invoked) from JavaScript code
        + Automatically (self invocated)
    + Syntax of JS Functions: `Function key word` **name** `(parameter 1, parameter 2, parameter 3)`
        + *Parameters:* Names listed in the function definition. 
            + *Arguments* are the real values passed to/received by the function. 
+ Functions wrapped with paranthesis are called "Immediately Invoked Function Expressions" or "Self Executing Functions." Purpose of wrapping is to namespace and control visibility of member functions, wraping code inside creates a function scope and decreases clashing of libraries