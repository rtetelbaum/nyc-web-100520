# Intro to Mod 2 & the Internet


## Recap Mod 1:
Some of the things we Learned last Mod
* **Ruby** - OO Programing Language- Dynamic language - User friendly
* **Objects** - Collections of data & behavior  - how represent real world concepts in code
* **Domain Modeling** - relationships between objects
* **SQL** - query language
* **ORM** - query with Ruby- Object Relational Mapping
* **Active Record** - an ORM
* **CRUD** - CREATE, READ, UPDATE, DELETE





## Overview Of Mod 2:
By the end of this Mod you should be able to create a fullstack web application

* HTTP 
  * Request & Response
  * REST 

  * MVC
    - Models
    - Views
    - Controllers
  * ERB - Embeded Ruby
  * How RESTful routes map to CRUD actions 

Rails Helpers
  * Routes helpers
  * ActionView helpers
  * Generators

* HTML/CSS



## Introduction to the internet

* What is the internet?

  Internet - hardware
  Web -   software


  * How is data sent over the internet?
  * TCP - Transmission Control Protocol -> how data gets sent
  * IP - Internet Protocol, IP Adress -> where
  * HTTP - HyperText Transfer Protocol - what kind of data
  * HTML - HyperText Markup Language



* How can I find out the IP address of www.google.com using a terminal command? What kind of server makes this lookup possible?
  * DNS (Domain Name System)
  * `nslookup`
  * https://iplocation.com/

  * What's the difference between static and dynamic websites? What are some of the benefits of a dynamic website?







  * https://en.wikipedia.org/wiki/ARPANET
  * https://en.wikipedia.org/wiki/Tim_Berners-Lee
  * http://info.cern.ch/hypertext/WWW/TheProject.html




* What is a server? What is a client?
- Browser
- server - computer internet connect devise

* With a client and server, which makes the request? Which sends the response?
- client sends a request
- server sends a response

* What is the request / response cycle?
  - Anatomy of Request:
   - URL/domain - GET/POST/PATCH/DELETE
   - Body
   - headers
 
  - Anatomy of Response:
    - Body
    - status code
    - headers
  


* What is a HTTP request? Make a few, using at least two of these tools: Google Chrome, Postman, curl

* What are the parts of a HTTP request
  * Use a web browser to find the headers for an HTTP request. What do you think these headers do?
  * What is usually in the body of an HTTP _response_?
  * What is a HTTP status code? What do the codes 200, 404, 500, 503, 302, 422 and 418 mean?
    * https://http.cat/
  * Why do we use HTTP verbs? What is the difference between what GET, POST, PUT, PATCH, and DELETE requests do?
  * What is a URL? Which part of a URL is the scheme (protocol)? Where is the host? The port? The path? Query string?  What is the purpose of each of these parts? 
    * https://docs.google.com/presentation/d/1no3yw_Vw4hBzGDlsEDcubvFnowi-Exjg9FW_VJid_U0/edit#slide=id.g378a2b8862_0_5




* Google query


https://www.google.com/search?
q => cute+doggos
oq => cute+doggos
aqs => chrome.0.69i59j0l2j0i10i433j0i10j0i10i433j0i10l2.3081j1j7
sourceid => chrome
ie => UTF-8