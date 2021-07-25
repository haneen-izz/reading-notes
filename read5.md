# Expressions and operators

### Operators

JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence. 

* assignment operators
* Arithmetic operators

![pictures](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Operators-1200x720.jpg)


&nbsp;

#### assignmet operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x. 

| name  |  Description   | example  |
| ------------- |:-------------:| -----:|
| assignment    | x = y  |   x = y |
| addition assignment    | x += y    |   x = x + y |
| subtraction assignment | x -= y     |x = x - y|

&nbsp;

#### Arithmetic operators
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/).

| name  |  Description   | example  |
| ------------- |:-------------:| -----:|
|Remainder (%)     |Binary operator  |	12 % 5 returns 2. |
|Increment (++)     | Unary operator   |  If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.  |
|Decrement (--)  | Unary operator    |If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2.|


[click here to read more about Expressions and operators ](https://hepunx.rl.ac.uk/~adye/js10/expr.html)


### Loops and iteration

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript. 

```
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step'); } 
  ```

#### for statement

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

```
for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement
  ```

#### while statement

A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows: 

```
while (condition)
  statement
  ```

