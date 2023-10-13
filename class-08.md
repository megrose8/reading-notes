# Operators and Loops
*Key Questions*
1. What is an expression in JavaScript?
2. Why would we use a loop in our code?
3. When does a for loop stop executing?
4. How many times will a while loop execute?

*Focus on Comparison Operators and Assignment Operators*

**Expressions** are units of code that resolve to a value.  
Two types:
    + Asign Values. EX: `x = 7`. Uses = operator to assign value 7 to the variable x.
    + Purely evaluate. EX. `3 + 4` Adds 3+4, and does not produce any effects.  

**Operators**  
*Asignment Operators*:  Asssigns value to left operator based on the value of the right operator. EX: `x= f(x)` assigns the value of f(x) to x. 
[See Table.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

*Comnparison Operators* Compares operators and returns a logical value based on whether the comparison is true. Operands can be numerical, string, logical, or object values. [See Table.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators)

**Loops and Iteration**  
*Loops* offer an easy and quick way to do an action repeatedly. Loops essentially repeat an action some number of times.  
Statements include: for, do...while, while, labeled, break, continue, for...in, for...of.  
+ `For` when executes it repeats until a specified condition is false. (Initialization > Condition Evaluated > Conditions True? Loop Executes OR Condition False? Loop Terminates > Statement executed > *if present* afterthought is executed. )   
`for (initialization; condition; afterthought)`  
`statement`
+ `While` executes as long as a specified condition evaluates as true. Condition test occurs before statement loop is executed. If condition is true, statement is executed and condition is tested again.   
`while (condition)`  
`statement`