# CRUD

The topic covers fundamental aspects of web development, particularly when building APIs and working with databases. Understanding these concepts is crucial for creating secure, efficient, and reliable applications.

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

100’s = informational responses
200’s = success
300’s = redirection
400’s = client error
500’s = server error

2. What is a status code 202?
   - The status code 202 indicates that the request has been accepted for processing, but the processing has not been completed yet.
3. What is a status code 308?
   - The status code 308 is similar to the more common 301 (Moved Permanently) status code, but it insists that the client should use the same HTTP method when making the redirected request to the new location.
4. What code would you use if an update didn’t return data to a client?
   - 204 No Content.
5. What code would you use if a resource used to exist but no longer does?
   - 410 Gone.
6. What is the ‘Forbidden’ status code?
   - 403 Forbidden. It indicates that the client's request is understood by the server, but the server refuses to authorize it.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
   - To store sensitive data like database connections in a .env file for security and to manage different environments.
2. What is middleware?
   - Middleware are functions that add functionality to the request-response cycle, like authentication or logging.
3. What does app.use(express.json()) do?
   - This middleware helps your app parse incoming JSON data from requests.
4. What does the /:id mean in a route?
   - It's a placeholder for dynamic values in a URL, like user IDs.
5. What is the difference between PUT and PATCH?
   - PUT fully updates, PATCH partially updates resources in APIs.
6. How do you make a default value in a schema?
   - In schemas, set default values for fields like status: 'active'.
7. What does a 500 error status code mean?
   - Server encounters unknown issues, a generic error.
8. What is the difference between a status 200 and a status 201?
   - 200 is success, 201 means resource created successfully.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT
