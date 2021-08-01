# HTML and js
## Text
When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.

1. Headings and paragraphs 
2. Bold, italic, emphasis 
3. Structural and semantic markup

![js picture](https://images.techhive.com/images/article/2017/02/16258492451_3a097a932a_k-100707389-large.jpg)

### heading 

```
<h1>This is a Main Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<h4>This is a Level 4 Heading</h4>
<h5>This is a Level 5 Heading</h5>
<h6>This is a Level 6 Heading</h6>
```
### Paragraphs

```
<p>A paragraph consists of one or more sentences    that form a self-contained unit of discourse. The    start of a paragraph is indicated by a new    line.</p>
<p>Text is easier to understand when it is split up    into units of text. For example, a book may have    chapters. Chapters can have subheadings. Under    each heading there will be one or more    paragraphs.</p>

```

### Bold & iTalic
```
<p>This is how we make a word appear <b>bold.</b>   </p>
<p>Inside a product description you might see some     <b>key features</b> in bold.</p>
```

### semantic markup

There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.


### summary 

|number of sentence| Description |
| --- | ----------- |
| 1 |HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs). |
| 2 |They also provide semantic information (where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).|

## css
CSS allows you to create rules that specify how the content of an element should appear.For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface. 


![css picture](https://media.geeksforgeeks.org/wp-content/cdn-uploads/CSS.png)

+ using external css
```
<!DOCTYPE html>
<html>
  <head>    
<title>Using External CSS</title>  
  <link href="css/styles.css" type="text/css"       rel="stylesheet" />  </head> 
   <body>    <h1>Potatoes</h1>   
    <p>There are dozens of different potato varieties. They are usually described as  early, second early and maincrop.</p>  
</body>
</html>
```

+ using InternaL css
```
</html>
<!DOCTYPE html>
<html>  <head>   
 <title>Using Internal CSS</title>   
  <style type="text/css">    
    body {   font-family: arial; background-color: rgb(185,179,175);}      
    h1 { color: rgb(255,255,255);}    </style> 
     </head>  <body> 
        <h1>Potatoes</h1>   
    <p>There are dozens of different potato varieties. They are usually described as early, second early and maincrop.</p>
  </body>
</html>
```


### summary 
* Different types of selectors allow you to target your  
rules at different elements.
* Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
* CSS rules usually appear in a separate document, although they may appear within an HTML page.

## Basic JavaScript Instructions
### LINKING TO A  JAVASCRIPT FILE  FROM AN  HTML PAGE
When you  want to use JavaScript with a web page, you  use the HTML 
`<script>` element to tell the browser it is  coming across a script. Its s re attribute tells people where the JavaScript file is  stored. 

```
<!DOCTYPE html> 
<html> 
<head> 
<title>Constructive  &amp; Co. </ title> 
<link  rel =" stylesheet "  href="css/ cOl.css"  /> 
</ head> 
<body> 
<hl>Constructive  &amp ; Co. </ hl> 
<script  src="js/ add-content.js"></ script> 
<p>For  all  orders  and i nquiries  please  cal l 
<em>SSS -3344 </ em></ p> 
</ body> 
</html>
```
### STATEMENTS 
A script is  a series of instructions that a computer can  follow one-by-one. 
Each  individual instruction or step is  known as  a statement. 
Statements should end with a semicolon.

+ Each  of the lines of code in gree n is a statement. 
+ The pink curly braces indicate the start and end 
of a code block. (Each code block could contain 
many more statements.) 
+ The cod e in purple determines which code should run.  


### COMMENTS 
You  should write comments to explain what your code does.They help make your code easier to read  and understand. 
two types of comments: 

* MULTI-LINE comments: 
`/* characters and ending with the * /`


* SINGLE-LINE comments: 
`//`

## DATA TYPES 
JavaScript distinguishes between numbers, strings, and true or  false values known as Booleans. 
- NUMERIC  DATA TYPE 
- STRING DATA TYPE 
- BOOLEAN DATA TYPE 

### USING A  VARIABLE TO STORE A  NUMBER: 
like this: 
```
var  price; 
var  quantity; 
var  total; 
```

### ARRAYS
an array is  a special  type of variable. It doesn't just store one value; it stores a list of values
how you can create an array: 
```
var  colors; 
colors ['white',  'black', ' custom ' ]; 
var  el document.getElementByld('colors'); 
el.textContent  = colors[O];
```
|INDEX | VALUE  |
| --- | ----------- |
| 0 | 'white' |
| 1 | 'black' |
| 2 | 'custom '|


### EXPRESSIONS 
An expression  evaluates into a single value.  Broadly speaking there are two types of expressions.

### OPERATORS 
Expressions rely on  things called operators; they allow programmers to 
create a single value from one or more values.
example

#### ASSIGNMENT OPERATORS A ssign a value to a variable 
`color =  'beige';`


## decesion and loop 
* EVALUATIONS : You can analyze values in your scripts to determine whether or note they match expected results. 

* DECISIONS &  LOOPS DECISIONS: Using the results of evaluations, you can decide which path your script should go down. 

* LOOPS:  There are also many occasions where you will want to perform the same set of steps repeatedly.

### evaluating conditions and conditional statements: 
`if(score > 50)`

### comparasion operators: evaluating conditions 
+ is equal to: `==`
+ is not equal to: `!=` 
+ strict equal to: `===`
+ greater than: `>`

## COMPARING TWO EXPRESSIONS:
``` 
var  scorel  = 90; var  score2  = 95; 
var  highScorel 75; 
var  highScore2 = 95; 

var  comparison= (score!+  score2) > (highScorel  + highScore2); 
var  el = document.getElementByid( ' answer'); el . textContent  =' New high  score:'+ comparison; 
```

 click here to read more about loops:
   [link](https://www.w3schools.com/js/js_loop_for.asp)
 
