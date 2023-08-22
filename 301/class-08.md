# APIs

API Design Best Practices, particularly focusing on REST principles, are crucial because they guide the creation of efficient and well-structured APIs. REST APIs center around resources identified by unique URIs and employ common HTTP verbs for various operations. These practices ensure smooth communication between software systems, minimize performance bottlenecks, and establish effective error handling through standardized status codes. By adhering to these guidelines, developers can create APIs that facilitate seamless interaction between applications, enhancing overall software efficiency and reliability.

## API Design Best Practices

1. What does REST stand for?
   - REST stands for Representational State Transfer
2. REST APIs are designed around a ____.
   - REST APIs are designed around a resource
3. What is an identifier of a resource? Give an example.
   - An identifier of a resource is a URI (Uniform Resource Identifier) that uniquely identifies the resource. For example, in the URI "https://api.example.com/users/123", the identifier is "123"
4. What are the most common HTTP verbs?
   - GET, POST, PUT, DELETE
5. What should the URIs be based on?
   - URIs (Uniform Resource Identifiers) should be based on the resources being accessed.
6. Give an example of a good URI.
   - An example of a good URI: "https://api.example.com/books/978-1234567890"
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
   - Having a 'chatty' web API refers to an API that requires multiple requests to perform a single logical operation. This is generally considered a bad thing because it increases the number of network round-trips and can lead to slower performance and increased overhead.
8. What status code does a successful GET request return?
   - 200 OK
9. What status code does an unsuccessful GET request return?
    - 404 Not Found
10. What status code does a successful POST request return?
    - 201 Created
11. What status code does a successful DELETE request return?
    - 204 No Content

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT