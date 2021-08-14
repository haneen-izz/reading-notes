# html

![Image](https://miro.medium.com/max/600/1*OFsc0SD55jhi8cjo7aCA4w.jpeg)

## images 
Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.

## controlling sizes of Images In css

```
<img src="images/magnolia-large.jpg"     class="large" alt="Magnolia" /> 
<img src="images/magnolia-medium.jpg"     class="medium" alt="Magnolia" /> 
<img src="images/magnolia-small.jpg"     class="small" alt="Magnolia" />
```
## Background Imagesbackground-image

`body {  background-image: url("images/pattern.gif");}`

### repeating Images

+ repeat: The background image is repeated both horizontally and vertically (the default way it 
is shown if the background-repeat property isn't used).

+ repeat-x: The image is repeated horizontally only (as shown in the first example on the left).

+ repeat-y: The image is repeated vertically only

## Background positIonbackground-position

```
body {  background-image: url("images/tulip.gif");
  background-repeat: no-repeat;  
  background-position: center top;}
```

### contrast of Background Images

If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

1. high contrast

2. low contrast 

3. screen

## summary 

- Background images can appear just once or be repeated across the background of the box.

- You can create image rollover effects by moving the background position of an image.

- To reduce the number of images your browser has to load, you can create image sprites.


### Practical information

To wrap up the book we are going to look at some practical information that will help you launch a successful site.

## search engine optimization (seo)
 is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines.




| seo     | Description |
| ----------- | ----------- |
| the Basics      | Search engine optimization (or SEO) is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers  |
| on-Page techniques | are the methods you can use on your web pages to improve their rating in search engines |
| off-Page techniques |Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours  |

&nbsp;

### how to identify keyWords and Phrases
Determining which keywords to use on your site can be one of the hardest tasks when you start to think about SEO. Here are six steps that will help you identify the right keywords and phrases for your site.

* Brainstorm
* organize
* research

### analytics: learning about your visitor
As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by 
Google called Google Analytics.

+ signing up: The Google Analytics service relies on you signing up for an account at: www.google.com/analytics.
+ how it Works: Every time someone loads a page of your site, the tracking code sends data to the Google servers where it is stored.
+ the tracking code: A tracking code is provided by Google Analytics for each website you are tracking.

## how many People are coming to your site?
The overview page gives you a snapshot of the key information you are likely to want to know. In particular, it tells you how many people are coming to your site.

- Visits: This is the number of times people have come to your site. If someone is inactive on your site for 30 minutes and then looks at another page on your site, it will be counted as a new visit.


### What are your Visitors looking at?
The content link on the left-hand side allows you to learn more about what the visitors are looking at when they come to your site.


### FTB and third Party tools
to transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol.

## Here is a list of some popular 
third party tools:

### Blogs
1. wordpress
2. tumpler
3. posterous

### e-commerce
1. shopify
2. bigcartel
3. magento



## summary
+ To put your site on the web, you will need to obtain a domain name and web hosting.
+ FTP programs allow you to transfer files from your local computer to your web server.
+ Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website 
tools (to save you writing them from scratch).

---


### Video and Audio APIs
HTML5 comes with elements for embedding rich media in documents — `<video>` and `<audio>` — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.

ex:

```
 <video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

![Image](
https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content/simple-video.png)


## How Flash works
Since the late 1990s, Flash has been a very popular tool for creating animations, and later 
for playing audio and video in websites.

click here to read more about video :
   [link](https://www.w3schools.com/html/html5_video.asp)
