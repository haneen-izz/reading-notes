# Chart.js, Canvas

**Charts** are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

![Image](https://cdn.mos.cms.futurecdn.net/S5bicwPe8vbP9nt3iwAwwi.jpg)

## Setting up

The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```
### Drawing a line chart

To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page:

 `<canvas id="buyers" width="600" height="400"></canvas>`

### Creating a Chart

It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

## The `<canvas>` element

`<canvas id="tutorial" width="150" height="150"></canvas>`

## Fallback content

The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

### Drawing paths

Now let's look at paths. A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.

Here are the functions used to perform these steps:

+ beginPath()
    Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
+ Path methods
    Methods to set different paths for objects.


## Colors

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use:


- fillStyle = color
    Sets the style used when filling shapes.
- strokeStyle = color
    Sets the style for shapes' outlines. 

## A fillStyle example

 ```
 function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  for (var i = 0; i < 6; i++) {
    for (var j = 0; j < 6; j++) {
      ctx.fillStyle = 'rgb(' + Math.floor(255 - 42.5 * i) + ', ' +
                       Math.floor(255 - 42.5 * j) + ', 0)';
      ctx.fillRect(j * 25, i * 25, 25, 25);
    }
  }
}
```

## Drawing text

The canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`

`strokeText(text, x, y [, maxWidth])`

## Styling text

the canvas:

+ font = value
    The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

+ textAlign = value
    Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

+ textBaseline = value
 Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

*Advanced text measurements*

In the case you need to obtain more details about the text, the following method allows you to measure it.

`measureText()`
    Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style. 

```
    function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  var text = ctx.measureText('foo'); // TextMetrics object
  text.width; // 16;
}
```

click here to read more about video :
   [link](https://www.w3schools.com/ai/ai_chartjs.asp)
