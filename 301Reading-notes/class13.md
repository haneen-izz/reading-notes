# CRUD

The HTTP specification defines many status codes we can use when responding to our clients. Some APIs only use the most basic codes and define their own error signaling mechanisms on top of it; others want to make full use of HTTPs collection of codes to tell their clients what’s going on. If you belong to the latter, this article is for you. This guide walks through the various CRUD operations and which status codes you should be using for clean API design.

![Image](https://www.dorusomcutean.com/wp-content/uploads/2020/03/crud.jpg)

*describe what each group of status code represents:*

100’s: they typically indicate the client that the header portion of the request has been received and that the server will attempt to meet the client's transmission requirement

200’s: They inform the client that their request has been accepted.In the situation of asynchronous request processing (202)

300’s: They inform the client that the requested resource is no longer accessible at the expected location.
This might be due to a variety of factors. 

400’s : They're all about incorrect requests submitted by a client to a server.
There are numerous reasons for this, including timeouts, incorrect URIs, and a lack of authentication. 



* What is a status code 202?
`The HyperText Transfer Protocol (HTTP) 202 Accepted response status code indicates that the request has been accepted for processing, but the processing has not been completed; in fact, processing may not have started yet`

* What is a status code 308?
 `308 Permanent Redirect redirect status response code indicates that the resource requested has been definitively moved to the URL given by the Location headers.`

* What code would you use if an update didn’t return data to a client?
`204 No Content - A proper code for updates that don't return data to the client`

---

![Image](https://codelabs.nyc3.digitaloceanspaces.com/contents/August2019/QmBAeDJsp7le2kBd4lrOJCDp3Xhcmksr.jpeg)


1. What is middleware?
`Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.`


2.  What does app.use(express.json()) do?
`express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.`


3. What does the /:id mean in a route?
`an object containing properties mapped to the named route “parameters”`