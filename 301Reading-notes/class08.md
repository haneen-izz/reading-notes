# APIs

![Image](https://cdn.tiempodev.com/wp-content/uploads/2020/07/28052914/managing-third-party-apis-01.jpg)

Most modern web applications expose APIs that clients can use to interact with the application. A well-designed web API should aim to support:

1. Platform independence. Any client should be able to call the API, regardless of how the API is implemented internally. This requires using standard protocols, and having a mechanism whereby the client and the web service can agree on the format of the data to exchange.

2. Service evolution. The web API should be able to evolve and add functionality independently from client applications. As the API evolves, existing client applications should continue to function without modification. All functionality should be discoverable so that client applications can fully use it.




---
**questions**


* What does REST stand for?
`representational state transfer`

* REST APIs are designed around a *resources*

* What is an identifer of a resource? Give an example

 `which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:`

**HTTP**
```
https://adventure-works.com/orders/1

```

* What are the most common HTTP verbs?
`POST, GET, PUT, PATCH, and DELETE`

* What should the URIs be based on?
`A Uniform Resource Identifier`
* Give an example of a good URI.
`URIs should be short in length. URIs should be case-sensitive. HTTP verbs should be used instead of operation names in URIS. Use spaces when designing a URI.`
 

---


|  Resource | POST  |
| ----------- | ----------- |
| /customers   | Create a new customer |
| /customers/1 | Error |

click here to read more :
[link](https://www.redhat.com/en/topics/api/what-is-a-rest-api)