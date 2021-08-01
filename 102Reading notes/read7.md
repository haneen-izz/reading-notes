# Expressions and operators

*This chapter describes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.*

#### Bitwise operators

A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values. 

![js pictures](https://www.javascript.ba/system/posts/images/000/001/163/original/1_1gByVzAtW0myl9e9CsGqhw.jpeg)

| name  |  Description   | example  |
| ------------- |:-------------:| -----:|
| Remainder (%)    | Binary operator. Returns the integer remainder of dividing the two operands.  | 12 % 5 returns 2. |
| Increment (++)     | Unary operator. Adds one to its operand. If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one.    | If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.  |
| Decrement (--)  | Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator.    |analogous to that for the increment operator. 	If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2. |

#### Logical operators

Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the (and) and operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table. 


| name  |  Description   | example  |
| ------------- |:-------------:| -----:|
| Logical AND (&&)   |expr1 && expr2 | Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.  |
| Logical OR     | expr1 or expr2   | Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values,  returns true if either operand is true; if both are false, returns false.  |
| Logical NOT (!)  | !expr |returns false if its single operand that can be converted to true; otherwise, returns true. |

#### The following code shows examples of the && (logical AND) operator.

```
var a1 =  true && true;     // t && t returns true
var a2 =  true && false;    // t && f returns false
var a3 = false && true;     // f && t returns false
var a4 = false && (3 == 4); // f && f returns false
var a5 = 'Cat' && 'Dog';    // t && t returns Dog
var a6 = false && 'Cat';    // f && t returns false
var a7 = 'Cat' && false;    // t && f returns false
```
### Functions

Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

#### Function expressions

While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name. For example, the function square could have been defined as:

```
const square = function(number) { return number * number }
var x = square(4)
```

#### Control flow

The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

#### Function Invocation

The code inside the function will execute when "something" invokes (calls) the function:

  * When an event occurs (when a user clicks a button)
  * When it is invoked (called) from JavaScript code
  * Automatically (self invoked)

### JavaScript Arithmetic Operators

| operator | Description |
| --- | ----------- |
| + | addition|
|-  |  Subtraction |
|* | Multiplication |
|-  |  Subtraction |
| %  |  Modulus (Division Remainder) |

[useful website](https://www.tutorialsteacher.com/javascript/javascript-operators)

