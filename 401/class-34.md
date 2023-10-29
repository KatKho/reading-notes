# API Integration

## Review API Server Build

### Explain the difference between a query string parameter and a path parameter.

A query string parameter appears at the end of the URL after a question mark (`?`), and is usually used for filtering and sorting data. A path parameter is part of the URL path, and is often used to identify a specific resource.

### What would our API URL with a path id parameter be given the following information?

Domain: http://our-site.com  
Version: v3  
Model name: stuff  
ID: things  

The API URL would be: `http://our-site.com/v3/stuff/things`

### We have created a dynamic API with an "interface". Describe how that interface works to a non-technical friend.

Imagine the interface as a remote control. You press a button, and something specific happens on the other side—like turning on the TV. Similarly, the interface allows us to interact with our data in specific ways without having to understand all the technical stuff going on in the background.

## Review Auth Server Build

### Describe how you would use middleware to implement basic and bearer auth.

Middleware acts like a gatekeeper. For basic auth, the middleware would check the username and password provided in the request header. For bearer auth, it would check for a token. If either is valid, the request is allowed to continue to the intended route.

### Describe the handshake necessary to implement OAuth.

1. The user tries to log in through a third-party, like Google.
2. The third-party provides a code.
3. Our server takes that code and exchanges it for an access token from the third-party.
4. The access token is then used to request user details, completing the handshake.

### Describe how Role Based Access Control works to a non-technical friend.

Imagine a club with different VIP levels. Regular folks can only go to the main dance floor. Gold members have access to a VIP lounge, and Platinum members have access to everything, including a super-exclusive area. Role Based Access Control works similarly; it decides who gets access to what based on their 'membership level' or role.

## Things I Want to Know More About


## Reference

- Reading Materials
- ChatGPT
