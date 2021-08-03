# js and css, HTML


Links are created using the `<a>` element. Users can click on anything 
between the opening `<a>` tag and the closing `</a>` tag. You specify 
which page you want to link to using the href attribute.

&nbsp;

![image](https://www.copahost.com/blog/wp-content/uploads/2019/07/html-link.jpg)

### linking to the other sites
links are created using the `<a>` element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.

```
  <ul><li><a href="http://www.empireonline.com"> 
   Empire</a></li></ul>
   ```

 ![image](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks/navigation-example.png)

 ## Directory structure

On larger websites it's a good idea to organize your code by placing the 
pages for each different section of the site into a new folder. Folders on a 
website are sometimes referred to as directories.
- structure
- relationships 
- homepages

| relative link type | example |
| --- | ----------- |
| same folder |`<a href="reviews.html">Reviews</a>`|
| child folder |`<a href="music/listings.html">Listings</a>`|

&nbsp;

### opening links in a new window
**like this:**

 ```
 <a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```

### summary of this: 
1. you can create links to open email programs with an email address in the `to` field.
2. You can use the id attribute to target elements within a page that can be linked to.


## layout

![image](https://media.geeksforgeeks.org/wp-content/uploads/layout.png)

* Building Blocks
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

Block-level elements start on a new line
Examples include:
`<h1> <p> <ul> <li>`

inline elements flow in Between surrounding text
Examples include:
`<img> <b> <i>`

### Controlling the position of eLements:

CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning.

+ normal flow
+ relative Positionin
+ absolute Positioning


### fLoating eLements

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

```
blockquote {   
     float: right;        
     width: 275px;        
     font-size: 130%;        
     font-style: italic;        
     font-family: Georgia, Times, serif;  margin: 0px 0px 10px 10px;  padding: 10px;       
    border-top: 1px solid #665544;        
    border-bottom: 1px solid #665544;
}
```
![image](https://miro.medium.com/max/1400/0*0Jt6AoXxmN0n0qhN)

#### creating multi-column layout with floats
```
.column1of2 {  float: left;  width: 620px;  margin: 10px;}
.column2of2 {  float: left;  width: 300px;  margin: 10px;}
```

### screen sizes

Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to 
work on a range of different sized screens.

### screen resolution
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

![image](https://1.bp.blogspot.com/-UOptUFoXC50/VuY04WTtF4I/AAAAAAAABHo/JiwHGIcwcgMt9tGRhrBTzX4vk3zKnP9cw/s1600/responsive_design_breakpoints.png)

### page sizes
* fixed width Layouts
* Liquid Layouts

## Css frameworks
SS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

### summary of this:
+ Grids help create professional and flexible designs. 
+ CSS Frameworks provide rules for common tasks. 
+ You can include multiple CSS files in one page.

## functions, method and objects
in java script: 
Functions let you group a se ries of statements together to perform a specific task.  If different  pa rts of a script repeat the same task, you can reuse the function (rather than rep eating the same set of st atements)

```
var  msg =  'Sign up to  receive  our  newsletter  for  10% off!'; 
function  updateMessage() { 
var  el = document.getElementByld('message'}; 
el .textContent  = msg; } 
updateMessage(}; 
```

**variable scope**
- local variable
- global varibale 


### pair programming 

Why pair program?

While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful.
 1. Greater efficiency
 2. Engaged collaboration
 3. Social skills















