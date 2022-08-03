# API - Application Programming Interface
A collection of information on API's

## Interface
Let's control you the way it works thorugh the exposed options (e.g. a radio)

An API is giving you access to data. They safe you from needing to create everything yourself.

## A little refresher - How the web works

Your computer uses a browser
the browser = web client and is used to connect to a server

To connect to that server, you're putting in an address in the address bar

address in this case = URL (Universal Resource Locator)

The scheme portion inside the URL is usually http (Hypertext Trasfer Proticol) 

The server then generated to resulting webpage and sends back a response to the client (the browser).

The most important part of that response is the <body>.
For a webpage the body contains HTML (Hyper Text Markup Language)

## REST (Reprensentation State Transfer)
API's that meet the REST architectural style constraints are considered to be RESTful. Those constraints are:
- Client-Server Architecture
  - If you want to maintain state like your login details, you must send it with each, and every request. You'll do this by using headers.
- Statelessness 
  - The server won't remeber anything about the particular client
- Layered System
- Cacheability
- Uniform Design
- Code on Demand

Your program sends a GET request to a URI. Then the server response with data and all http headers. 
The body these days is typically represented as JSON (JavaScript Object Natotaion)

JSON actually provides a great way to structure and nest your data.

HTTP Verbs | CRUD 
--- | --- 
GET | Read 
POST | Create 
PUT | Update 
PATCH | Update
DELETE | Delete 


Many products offer what is known as an SDK (Software Developer Kit) or helper library that allows you to interact with their product in your native language.

```
to be continued...
```
