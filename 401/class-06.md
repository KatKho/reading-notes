# Authentication

Authentication is essential for online security. To securely store passwords, we use tools like Bcrypt, which turns them into highly secure codes with added salts. Basic Authentication in HTTP involves sending usernames and passwords in request headers. These credentials are Base64-encoded. Proper error messages, including HTTP status codes and user-friendly HTML messages, guide users and enhance security. Bookmarking OWASP fundamentals for secure authentication practices is crucial, reducing vulnerabilities throughout an application's lifespan.

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.
   - To safely hash and store a password, you'd use a tool like Bcrypt, which turns the password into a secret code and adds a unique ingredient (salt) before storing it on a computer. This makes it extremely difficult for anyone to discover the actual password, even if they gain access to the computer.
2. What is Bcrypt?
   - Bcrypt is a security tool that transforms passwords into highly secure codes with added salts. It's used to protect passwords by making them virtually impossible for attackers to crack.
3. Why might you use something like Bcrypt?
   - Bcrypt is used to enhance password security, ensuring that even if a computer is compromised, the actual passwords remain hidden. It's vital for safeguarding online accounts and sensitive information from unauthorized access.

## Basic Auth

1. What is Basic Authentication?
   - Basic Authentication is a simple method of user authentication used in HTTP, where a username and password are sent as part of the request header to access a protected resource.
2. What properties are necessary in the header of a Basic Auth request?
   - In a Basic Auth request header, two properties are necessary: "Authorization" and "Base64-encoded username:password."
3. How are username:password in Basic Auth encoded?
   - To encode the username and password in Basic Auth, they are combined with a colon (e.g., "username:password") and then Base64-encoded. The resulting string is included in the "Authorization" header of the request.

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.
   - Authentication is like showing an ID to enter a secure area. When a user tries to access a protected part of a website or application, they provide their username and password. The system checks if this matches the stored information. If it does, the user gets access; if not, they're denied entry.
2. How should your error messaging respond (both HTTP and HTML)? Why?
   - For HTTP responses, errors should include appropriate status codes (e.g., 401 Unauthorized) to inform the client that authentication failed. In HTML, user-friendly error messages should be displayed, guiding users on what went wrong.
3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.
   - It's important to bookmark OWASP (Open Web Application Security Project) fundamentals as a reference for secure authentication practices. Applications designed with security in mind are less likely to have vulnerabilities, ensuring better protection throughout their lifespan.

## Reflection

1. What are your learning goals after reading and reviewing the class README?
   - I aim to have the ability to revisit and reference the topics and themes we've covered in the course, considering the extensive content we're learning.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT