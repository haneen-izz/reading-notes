# js and html 
## domain modeling 
it is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

*how to Define a constructor and initialize properties*
To define the same properties between many objects, you'll want to use a constructor function.

| Property |    Data       |  Type |
|----------|:-------------:|------:|
|epicRating| 1 to 10       | Number|
| hasAnimals|true or false | Boolean|

    



Here's an implementation of the `EpicFailVideo` constructor function:
```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail);
console.log(corgiFail);
```

### Generate random numbers

```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail.generateRandom(1, 5));
console.log(corgiFail.generateRandom(1, 5));
```

## table
A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

```
<table>
  <tr>
    <td>15</td>
    <td>15</td>
    <td>30</td>
  </tr>
  <tr>
    <td>45</td>
    <td>60</td>
    <td>45</td>
  </tr>
  <tr>
    <td>60</td>
    <td>90</td>
    <td>90</td>
  </tr>
</table>
```

![image](https://cdn.educba.com/academy/wp-content/uploads/2019/10/Create-Tables-in-HTML.png)


## spanning rows

```
<table>
  <tr>
    <th></th>
    <th>ABC</th>
    <th>BBC</th>
    <th>CNN</th>
  </tr>
  <tr>
    <th>6pm - 7pm</th>
    <td rowspan="2">Movie</td>
    <td>Comedy</td>
    <td>News</td>
  </tr>
  <tr>
    <th>7pm - 8pm</th>
    <td>Sport</td>
    <td>Current Affairs</td>
  </tr>
</table>
```

 click here to read more about tables:
   [link](https://www.educba.com/create-tables-in-html/)

### summary 

- nside each row there are a number of cells represented by the `<td>` element (or `<th>` if it is a header).

- You can make cells of a table span more than one row  
or column using the rowspan and colspan attributes.

- For long tables you can split the table into a `<thead>`, 
`<tbody>`, and `<tfoot>`.


## object 
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names

**this keyword**
he keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates. 

### A FUNCTION IN GLOBAL SCOPE 
When a function is created at the top level of a script (that is, not inside another object or function), then it is in the global scope or global context.

![image](https://ringojs.org/documentation/images/scriptscope.png)

### WHAT ARE BUILT-IN OBJECTS? 
Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages. 

WHAT DOES THIS SECTION COVER? 
You have already seen how to access the properties and methods of an object, so the purpose of this 
section is to let you know: 

1. What built-in objects are available to you 
2. What their main properties and methods do


### THE BROWSER OBJECT MODEL: THE WINDOW OBJECT
+ `window . innerHeight`
+ `window.innerWidth`
+ `window.pageXOffset`


### USING THE DOCUMENT OBJECT
```
var msg = '<p><b>page title: </b>' + document.title + '<br /> ' ; 
msg += '<b>page address: </b>' +document.URL+ '<br />'; 
msg += '<b>last modifi ed : </b> ' + document. l astModified + '</p>' ; 
~var el = document .getElementByld('footer'); 
~el erHTML = msg ; 
```

### GLOBAL OBJECTS: STRING OBJECT 
`var saying = home sweet home;`

### DATA TYPES REVISITE
1. String 
2. Number 
3. Boolean 
4. Undefined (a variable that has been declared, but 
no value has been assigned to it yet) 
5. Null (a variable with no value - it may have had 
one at some point, but no longer has a value)

## summary:
- Web browsers implement objects that represent both 
the browser window and the document loaded into the 
browser window. 
- JavaScript also has several built-in objects such as 
String, Number, Math, and Date. Their properties and 
methods offer functionality that help you write scripts. 

- Arrays and objects can be used to create complex data 
sets (and both can contain the other).