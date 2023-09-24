# Bearer Authorization

Bearer Authorization is a method for securing web applications and APIs by using tokens. One common type of token is the JSON Web Token (JWT).

## Intro to JWT

**What is a JSON Web Token (JWT)?**
A JSON Web Token (JWT) is a compact and self-contained means of representing information between two parties. It's often used for securely transmitting information between a client and a server as a JSON object. JWTs are commonly used for authentication and authorization purposes in web applications.

**When should we use JSON Web Tokens?**
JWTs should be used when you want to securely transmit information between a client and a server, and you need to ensure that the data hasn't been tampered with. They are particularly useful for implementing authentication and authorization mechanisms.

**Claims are expected in which structural component of a JWT?**
Claims are expected in the payload component of a JWT. The payload contains claims, which are statements about an entity (typically, the user) and additional data. Claims can be used to provide information such as the user's ID, roles, or permissions.

## Are JWTs Secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**
Decoding the payload of a JWT does not make it insecure by itself. The security of a JWT relies on its signature, which is used to verify the integrity of the token. If the signature is valid, it means that the token hasn't been tampered with and can be trusted.

**If sending a JWT, what must the sender and receiver both know? Hint, it’s appended in the signature.**
When sending a JWT, the sender and receiver both need to know a secret key that is used to sign and verify the JWT. This secret key is a shared secret between the parties involved. It's used to create the digital signature, and the recipient uses it to verify the signature.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
JWTs use a process called HMAC (Hash-based Message Authentication Code) to secure the token. The content of the JWT (header and payload) is concatenated, and a secret key is used to create a digital signature. This signature is appended to the JWT. When the recipient receives the JWT, they also have access to the secret key. They can perform the same concatenation and signature verification. If the signature matches, they can trust that the JWT's content hasn't been tampered with and is secure.

## JWTs Explained

**Why use JWT?**
JWTs are useful because they are compact, self-contained, and can be easily transmitted as part of an HTTP request. They are commonly used for implementing single sign-on (SSO) and enabling secure communication between different services in a distributed system.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
Imagine a JWT as a small, sealed envelope that contains important information. This envelope is easy to carry and can be handed over quickly. You don't need to open the envelope to see what's inside; the information is right there on the outside. This makes it efficient for transferring data between two parties without the need for additional requests or lookups.

**What are the three components (the structure) of a JWT signature?**
A JWT signature consists of three components:

1. Header: Contains metadata about the type and signing algorithm.
2. Payload: Contains claims, which are statements about the entity and additional data.
3. Signature: Created by taking the encoded header, encoded payload, and a secret key, and then applying a signing algorithm to produce a signature. The signature is used to verify the integrity of the JWT.

## Reflection

1. What are your learning goals after reading and reviewing the class README?
   - I aim to have the ability to revisit and reference the topics and themes we've covered in the course, considering the extensive content we're learning.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT