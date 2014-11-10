## Context

Working through the [Node Beginner](http://www.nodebeginner.org/) ebook/tutorial.

## Spec

* The user should be able to use the application with a web browser
* The user should see a welcome page
* The welcome pahe displays a file upload form
* By choosing an image file to upload, and submitting the form, the image should be uploaded, and displayed

## Process

What does the application need to consist of?

* HTTP server, to serve webpages
* Router, to map requests to request handlers
* Request handlers to fulfil the requests
* Request data handling, to respond incoming to POST data
* View logic, to display content for GET requests
* Upload handling, to do exactly that

## Steps

1. server.js

## Learning

Clean code:

* Put different concerns in modules
* Loosely couple server and route by injecting dependency


## Further Reading

* [Understanding NodeJS](http://debuggable.com/posts/understanding-node-js:4bd98440-45e4-4a9a-8ef7-0f7ecbdd56cb)

* [Injection Dependency](http://martinfowler.com/articles/injection.html)

* [Execution in the Kingdom of Nouns](http://steve-yegge.blogspot.co.uk/2006/03/execution-in-kingdom-of-nouns.html)