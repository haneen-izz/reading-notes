# layout
![LayoutImage](https://miro.medium.com/max/1024/1*XCZZZmhQN4rHLw2dW14BZQ.png)


## Building Blocks
Block-level elements start on a new line
Examples include:
`<h1> <p> <ul> <li>`

## containing Elements
If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

- fixed Positioning: This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

- floating elements: Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.

### position: static
```
body {
 width: 750px;  font-family: Arial, Verdana, sans-serif;  color: #665544;}
h1 { 
 background-color: #efefef;  padding: 10px;}
p {  
width: 450px;}
```

### position: relative
```
p.example { 
position: relative;  top: 10px;  left: 100px;}
```


### page sizes
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens).


## fixed width Layouts
### advantages:

1. Pixel values are accurate at controlling size and positioning of elements.

2. The designer has far greater  control over the appearance and position of items on the page than with liquid layouts.

3. You can control the lengths of lines of text regardless of the size of the user's window.

4. The size of an image will  always remain the same relative to the rest of the page.

## Css frameworks
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS 
framework code in your projects rather than writing the CSS from scratch.

## summary: 
+ Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

+ Grids help create professional and flexible designs. 

+ CSS Frameworks provide rules for common tasks.
 
+ You can include multiple CSS files in one page


&nbsp;

 click here to read more about css wireframe:
   [link](https://meyerweb.com/eric/thoughts/2017/11/27/generating-wireframe-boxes-with-css-and-html5/)









