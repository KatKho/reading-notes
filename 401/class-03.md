# Express REST API

The Express REST API topic covers ES6 classes as templates for object creation, Express routing for handling client requests and differentiating between route paths and methods, and the use of Express Routers for modularizing routes and middleware. It emphasizes the significance of adding "next" in route handlers to control middleware flow and improve code organization through route middleware.

## Review: ES6 Classes

1. Classes are a template for creating ____.
   - Classes are a template for creating objects.
2. Can a class declaration be hoisted?
   - No, a class declaration cannot be hoisted like function declarations can in JavaScript.
3. How would you describe a constructor and contextual “this” to a non-technical friend?
   - "This" is like a special word that points to the thing you're currently working on. It helps you make sure you're doing the right stuff for that thing, not getting mixed up with other things. So, when you use "this," you're saying, "I'm talking about this particular thing right now." It keeps everything organized.

## Using Express Routing

1. Within Express, what does routing refer to?
   - In Express, routing refers to the process of determining how an application responds to a client request at a specific endpoint (URL).
2. What is the difference between a route path and a route method?
   - Route Path: A route path is the URL pattern that defines the path part of a route. It can include static segments like "/home" or dynamic segments like "/users/:id", where ":id" represents a parameter that can vary.
   - Route Method: A route method corresponds to an HTTP method such as GET, POST, PUT, DELETE, etc. It defines what action should be taken when a request with that specific HTTP method is made to the given route path.
3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
   - Add next as a parameter when you want to pass control to the next middleware or route handler. If next is passed to your middleware, you must call it to allow the request to continue through the Express middleware chain. Failure to do so can lead to request handling issues.

## Express Routing

1. What is an Express Router?
   - An Express Router is a way to organize and modularize your Express application's routes and middleware into separate, reusable components.
2. By what mean do we initialize express.Router() in an express server?
   - You initialize an express.Router() in an Express server by creating an instance of the router.
3. What do we use route middleware for?
   - Route middleware allows you to add functionality and behavior to your routes without cluttering the main route handlers, making your code more organized and maintainable.

## Reflection

1. What are your learning goals after reading and reviewing the class README?
   - I aim to have the ability to revisit and reference the topics and themes we've covered in the course, considering the extensive content we're learning.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT