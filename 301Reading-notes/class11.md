# Authentication


![Image](https://bezkoder.com/wp-content/uploads/2020/02/node-js-mongodb-jwt-authentication-architecture.png)


1. What is OAuth?

`OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.`

2. Give an example of what using OAuth would look like.

 `when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.`


3.  How does OAuth work? What are the steps that it takes to authenticate the user?

```
* The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

* The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
* The first site gives this token and secret to the initiating user’s client software.
* The client’s software presents the request token and secret to their authorization provider (which may or may  not be the second site).
```

4.  What is OpenID?

`began life in 2005 as a means for logging into the then-popular LiveJournal blogging site but quickly spread to other sites. The idea, in the early days of Web 2.0, was that rather than having multiple logins for multiple websites, OpenID would serve as a single sign-in, vouching for the identities of users.`

---

What is the difference between authorization and authentication?

```
Authentication, in the form of a key. The lock on the door only grants access to someone with the correct key in much the same way that a system only grants access to users who have the correct credentials.
Authorization, in the form of permissions.
```

What is Authorization Code Flow?

`Authorization in system security is the process of giving the user permission to access a specific resource or function. This term is often used interchangeably with access control or client privilege.`

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

`is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange`

What is Implicit Flow with Form Post?

`is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.`

What is Client Credentials Flow?

`s a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. `

