# In memory storage 

---

![Image](https://blog.openreplay.com/static/27096561c1e10c6d47ac9fdb8f0eae9c/8537d/fa9d1bed19b548b3af7a90f0616b4916.png)

The JavaScript engine (which is found in a hosting environment like the browser), is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the `DOM`, `AJAX`, and `Timers`.


---
## questions

* What is a ‘call’?
 is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

* How many ‘calls’ can happen at once?
one call stack so that it only can do one thing at a time. When executing a script, the JavaScript engine executes code from top to bottom, line by line. In other words, it is synchronous. Asynchronous is the opposite of synchronous, which means happening at the same time.

* What does LIFO mean?
means last in first out, the same way as a stack of dinner plates or other types of the stack in the real world works—the most recent element added to the stack should be the first out.

* What causes a Stack Overflow?
 stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error The `callMyself()` will run until the browser throws a “Maximum call size exceeded”.

---

```
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```

When the code is run, we get an error. A stack is printed showing how the functions are stack on top each other. 

![Image](https://cdn-media-1.freecodecamp.org/images/zOINLHPC8E56ac8yyINYOFWeImsjM2Wk2rdU)

**summary**

The key takeaways from the call stack are:
1. It is single-threaded.
2. Code execution is synchronous.
3. A function invocation creates a stack frame that occupies a temporary memory.

---
* What is a ‘refrence error’?
`a reference error is thrown when a code attempts to reference a non-existing variable.`
* What is a ‘syntax error’?
`An exception caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while compiling or parsing source code. For example, if you leave off a closing brace when defining a JavaScript function, you trigger a syntax error`
* What is a ‘range error’?
`is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value.`
* What is a ‘tyep error’?
`The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type.`

