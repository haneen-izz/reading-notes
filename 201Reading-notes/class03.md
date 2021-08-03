# introduction
![image](https://images.pexels.com/photos/930530/pexels-photo-930530.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500)


## lists
in html there are: 
+ Ordered lists: are lists where each item in the list is 
numbered, for example:

```
ol> 
<li>Chop potatoes into quarters</li>
  <li>Simmer in salted water for 15-20 minutes until tender</li>
  </ol>
```

+ Unordered lists: are lists that begin with a bullet point 
(rather than characters that indicate order).
Definition lists for example:


```
<ul> 
<li>1kg King Edward potatoes</li> 
 <li>100ml milk</li>  
 <li>50g salted butter</li> <ul>
```

### nested lists
You can put a second list inside an `<li>` element to create a sub-list or nested list.

```
<ul> 
 <li>Mousses</li>  <li>Pastries  
   <ul>     
 <li>Croissant</li>    
   <li>Mille-feuille</li>    
     <li>Palmier</li>    
       <li>Profiterole</li>    
       </ul>  </li> 
        <li>Tarts</li>
</ul>
```


### summery lists
1. There are three types of HTML lists: ordered unordered, and definition. 
2. Ordered lists use numbers. 
3. Unordered lists use bullets.


 
## Box Dimensions width, height

default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties.

```
<div> 
<p>The Moog company pioneered the commercial manufacture of modular voltage-controlled analog synthesizer systems in the early 1950s.</p>
</div>
```

* limiting Width
* limiting height

&nbsp;

Every box has three available properties that 
can be adjusted to control its appearance:

|properties | Description |
| --- | ----------- |
| Border |Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another|
| Margin |Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.|

### centering content
if you want to center a box on 
the page (or center it inside 
the element that it sits in), you 
can set the left-margin and 
right-margin to auto.

### summary of boxes:

- CSS treats each HTML element as if it has its own box. 
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding for each box with CSS.


## accessing & changing values in  an array
The first lines of code on the left create an array containing a list of three colors. (The values can be added on the same line or on separate lines as shown here.) 

## arrays
An array is  a special  type of variable. It doesn't just store one value; it stores a list of values. 

```
var  colors; 
colors ['white',  'black', ' custom ' ]; 
var  el document.getElementByld('col ors'); 
el . textContent  = colors[O]; 
```


## expression 
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.
 
1. expression that just assign a value to variable
2. expression that us OR more values to return a single value

### operators 
Expressions rely on  things called operators; they allow programmers to 
create a single value from one or more values

### arithmetic operators
example 

```
var  subtotal (13 +  1) *  5; 
var  shipping 0.5  *  (13 +  1) ; 
var  total subtotal  +  shipping ; 
```
### if else statement
Here you can  see that an if ... e1se statement al lows you to provide two sets of code: 

1. one set if the condition evaluates to true 
2. another set if the condition is false 

### switch 
example

```
var  msg; 
var  level  = 2; 
II Message 
11 Level 
c04/js/switch-statement . js 
/ I  Determine  message  based on level 
switch (level)  { 
case  1: 
msg = 'Good luck  on the  first  test ' ; 
break; 
case  2: msg = 'Second of  three  - keep going!'; 
break; 
case  3: 
msg = ' Final round, al most  there!'; 
break; 
default : 
msg = 'Good l uck!'; 
break; 
var  el = document.getE l ementByld('answer ' ); 
el . textContent  = msg;  
```

### truthy and falsy 
- Truthy values: are treated as if they are true. Almost everything that is  not in  the falsy table can be treated as  if it were true

- Falsy values: are treated as if they are  fa1se. The table to the left shows a hi ghScore variable w ith 
a series of va lues, all of which are falsy.

### for loop 
```
for  (i = O; i  <  arraylength; i++) {
```


### while 
```
while  (i  < 10) { 
msg += i + ' x 5  = ' +  (i  *  5) + '<br  I >'; 
i++;
``` 
### summary 

- Conditional statements allow your code to make decisions about what to do next. 
- Comparison operators (===,  ! ==,  ==,  ! =,  <,  >,  <=,  =>) are used to compare two operands. 
- Logical operators allow you to combine more than one set of comparison operators.

 click here to read more about loops:
 [link](https://www.w3schools.com/js/js_loop_for.asp)
 
