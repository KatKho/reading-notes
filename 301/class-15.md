# Authentication

OAuth is a protocol that safeguards your data by letting apps access it without your password. It ensures secure access through authorization steps, granting apps limited permissions. Different authentication flows like Authorization Code, Implicit, and Client Credentials offer flexibility for various scenarios. OpenID adds single sign-on convenience. This knowledge is crucial for developers to create secure, user-friendly apps.

## What is OAuth

1. What is OAuth?
   - OAuth is a protocol that allows apps to access your data without needing your password. It ensures secure access to resources on your behalf.
2. Give an example of what using OAuth would look like.
   - Imagine a social media app posting to your Twitter. OAuth lets the app post without giving it your Twitter password.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
   - User initiates authorization.
   - User logs in and grants permission.
   - Service provides an access token.
   - App uses token to access data.
   - Optional: Refresh tokens for prolonged access.
4. What is OpenID?
   - OpenID is a protocol for single sign-on. It lets you use one account to log into multiple websites, simplifying login processes.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
   - Authentication: Confirming someone's identity, often involving a username and password.
   - Authorization: Granting permissions to authenticated users based on their role or requested actions.
2. What is Authorization Code Flow?
   - A secure OAuth flow. User is redirected to log in, then gives app permission. App exchanges a code for an access token. Used for web apps and confidential clients.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
   - Enhanced version of Auth Code Flow. Adds security to public clients (like mobile apps). Generates a temporary code verifier and a challenge, protecting against code interception.
4. What is Implicit Flow with Form Post?
   - Old OAuth flow, less secure. Access token obtained via browser redirect. Intended for web apps using JavaScript, but not recommended due to security risks.
5. What is Client Credentials Flow?
   - Used by apps/machines to authenticate themselves. No user involvement. Direct exchange of credentials for tokens. Typically for backend-to-backend communication.
6. What is Device Authorization Flow?
   - For devices with limited input capabilities. User authorizes on another device. Device polls for access token when approved.
7. What is Resource Owner Password Flow?
   - Least recommended OAuth flow. User's credentials sent to app's server. App exchanges credentials for an access token. Riskier due to password exposure and less secure than other flows.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT