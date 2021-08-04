# Images, Color, Text

## choosing image for your site
A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

## adding images
``` 
<img src="images/quokka.jpg" alt="A family of quokka" title="The quokka is an Australian marsupial that is similar in size to the domestic cat." />
```

&nbsp;

![image](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML/alt-text.png)

### Where to place Images In Your Code
1. before a paragraph
2.  Inside the start of a paragraph
3.  In the middle of a paragraph

### three rules for creating images
 - save Images in the right format
 - save images at the right size
 - use the Correct resolution

 ## image dimensions
 The images you use on your website should be saved at the same width and height that you want them to appear on the page.

| image dimensions | example |
| --- | ----------- |
|Changing shape | If your image is 300 pixels square, you can remove parts of it, but in doing so you might lose valuable information|
|reducing Image size| If your image is 600 pixels wide and 300 pixels tall, you can reduce the size of the  image by 50%|
|Increasing Image size|If your image is only 100 pixels wide by 50 pixels tall, increasing the size by 300% would result in poor qualit|

### Cropping Images

When **cropping** images it is important not to 
lose valuable information. It is best to source 
images that are the correct shape if possible


### html5: figure and figure Caption

```
<figure>  <img src="images/otters.jpg" alt="Photograph of        two sea otters floating in water">  <br />
  <figcaption>Sea otters hold hands when they        sleep so they don't drift away from each        other.</figcaption>
</figure>
```
----

## Foreground Color
The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three way example:

```
/* color name */
h1 {  color: DarkCyan;}
/* hex code */
h2 {  color: #ee3e80;}
/* rgb value */
p {  color: rgb(100,100,90);}
```
 
 Color Computer monitors are made up of thousands of tiny squares called pixels so if you look very closely at your monitor you should be able to see them When the screen is not turned on, it's black because it's not emitting any light. When it's on, each pixel can be a different 
color, creating a picture.The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue just like on a television screen

![image](https://i0.wp.com/css-tricks.com/wp-content/uploads/2019/10/stripe-accessible-colors.png?fit=1200%2C600&ssl=1)

### Contrast
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.

* low Contrast
* high contrast
* medium contrast

### hsl Colors
+ hue 
+ saturation
+ lightness



## text 

### Typeface Terminology

1. Serif: its fonts have extra details on the ends of the main strokes of 
the letters. These details are known as serifs.
2. SanS-Serif: fonts have straight ends to letters, and therefore have a much cleaner design

### echniques of typefaces:
* font-family
* font-face
* Service-based font-face

### Type Scales
You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.

![image](https://utopia.fyi/images/golden-section-scales.png)

### bold
example:
```
.credits {  font-weight: bold;}
```

### leading
example: 
```
p {  line-height: 1.4em;}
```

### first letter 
`p.intro:first-letter {  font-size: 200%;}`

### attribute Selectors

- existence:  `[]` Matches a specific attribute whatever its value   `p[class]`
- equality:    `[-]` Matches a specific attribute with a specific value  `p[class="dog"]` 


## TL;DR

Use JPEG format for all images that contain a natural scene or photograph where variation in colourand intensity is smooth. Use PNG format for any image that needs transparency or for images with text and objects with sharp contrast edges like logos. Use GIF format for images that contain animations.

### Compression

Almost all forms of data that we see on the internet text and vedio and etc, are compressed to reduce the size of data and ensure faster transmission. Choosing the correct format and compression is a major factor that determines image size.

### Transparency
 
transparency indicates something that is completely invisible.




