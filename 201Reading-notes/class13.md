# The Past, Present & Future of Local Storage for Web Applications
![Image](https://www.exeideas.com/wp-content/uploads/2016/02/Use-HTML5-Local-Storage.jpg)

## Diving In

persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files.

Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

    
- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
    
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
    
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful 

## A Brief History of Local Storage Hacks Before HTML5
In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData. 

## Introducing HTML5 Storage

What I will refer to as **“HTML5 Storage”** is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter. 
```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```
&nbsp;

```
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```
## Using HTML5 Storage

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. 

```
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
```


| Property    | Description  |
| ----------- | ----------- |
| key      | 	the named key that was added, removed, or modified   |
| oldValue | the previous value (now overwritten), or null if a new item was added |
| newValue | 	the new value, or null if an item was removed   |

## Limitations in Current Browsers

In talking about the history of local storage hacks using third-party plugins, I made a point of mentioning the limitations of each technique, such as storage limits. I just realized that I haven’t mentioned anything about the limitations of the now-standardized HTML5 Storage. I’ll give you the answers first, then explain them. The answers, in order of importance, are “5 megabytes,” `“QUOTA_EXCEEDED_ERR”` and “no.” 

## HTML5 Storage in Action
The most important part of this function is the caveat that I mentioned earlier in this chapter, which I’ll repeat here: Data is stored as strings. If you are storing something other than a string, you’ll need to coerce it yourself when you retrieve it

1. `localStorage["halma.game.in.progress"] = gGameInProgress;`
2. `gGameInProgress = (localStorage["halma.game.in.progress"] == "true");`

click here to read more about video :
   [link](https://www.techopedia.com/definition/27674/html5-local-storage)
