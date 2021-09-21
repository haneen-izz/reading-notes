# FUNCTIONAL PROGRAMMING




---
**questions**

1. What is functional programming?

`is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects. Functional programming is declarative rather than imperative, and application state flows through pure functions. Contrast with object oriented programming, where application state is usually shared and colocated with methods in objects.`


2. What is a pure function and how do we know if something is a pure function?
`The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.`

3. What are the benefits of a pure function?
`One of the major benefits of using pure functions is they are immediately testable. They will always produce the same result if you pass in the same arguments. They also makes maintaining and refactoring code much easier.`

4. What is immutability?
Immutable data cannot change its structure or the data in it. It's setting a value on a variable that cannot change, making that value a fact, or sort of like a source of truth — the same way a princess kisses a frog hoping it will turn into a handsome prince.

5. What is Referential transparency?
`Referential Transparency emphasizes that an expression in a JavaScript program may be replaced by its value or any other variable having the same value without changing the result of the program. As a result, methods should always return the same value for the given argument without any side effects.`
---


![Image](https://softwarebrothers.co/blog/content/images/2020/02/funtional-js.png)

---
**questions**

* What is a module?
are a major new feature, or rather a collection of new features. You may have used a userland JavaScript module system in the past.All of these module systems have one thing in common: they allow you to import and export stuff.

* What does the word ‘require’ do?
The basic functionality of require is that it reads a JavaScript file, executes the file, and then proceeds to return the exports object.

* How do we bring another module into the file the we are working in?
To include functions defined in another file in Node.js, we need to import the module.

---



 click here to read more :
[link](https://dev.to/thomas_hoadley/functional-programming-basics-before-you-learn-react-and-redux-the-how-part-2-1212)