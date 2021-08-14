# js 

## forms
JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

&nbsp;

![Image](https://javascript.info/article/debugging-chrome/chrome-sources-debugger-trace-1.svg)


## ORDER OF EXECUTION 
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:

1. The greeting variable gets its value from the 
`greetUser()` function. 

2. `greetUser()` creates the message by combining the string `He11o` with the result of `getName()`
3. `getName ()` returns the name to greetUser().

## EXECUTION CONTEXTS 
The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new execution context. They correspond to variable scope. 

VARIABLE SCOPE 
The first two execution contexts correspond with the notion of scope (which you met on p98): 

- GLOBAL SCOPE 
If a variable is declared outside a function, it can be used anywhere because it has global scope. If you do not use the var keyword when creating a variable, it is placed in global scope. 

- FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.


### EXECUTION CONTEXT and HOISTING 
Each time a script enters a new execution context, there are two phases 
of activity:

The following would would fail because `greetuser()` is created within the `getName ()` function's context: 
```
var greeting= greetUser(); 
function getName() { 
function greetUser() 
II Create greeting 
} 
II Return name with greeting 
```


### UNDERSTANDING SCOPE 
In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object.

## ERROR OBJECTS 
Error objects can help you find where your mistakes are and browsers have tools to help you read them. 

| Error      | Description |
| ----------- | ----------- |
| error      | Generic error - the other errors are all based upon this error  |
| Syntax Error | syntax has not been followed  |


### HOW TO DEAL WITH ERRORS 
Now that you know what an error is and how the browser treats them, there are two things you can do with the errors. 


### BROWSER DEV TOOLS and JAVASCRIPT CONSOLE 

The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be

- TRY
- catch 
- FINALLY 
