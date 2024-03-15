# [Readings: Authentication](https://github.com/codefellows/seattle-code-301d108/tree/main/class-15)

## [What is OAuth?](https://www.csoonline.com/article/562635/what-is-oauth-how-the-open-authorization-framework-works.html)
1. **What is OAuth?** OAuth is an open standard authorization framework that allows third-party services to access a user's data without needing the user's credentials directly. It facilitates secure and standardized access to resources stored on one site from another site.
2. **Give an example of what using OAuth would look like.** Signing in to a website using Google credentials. When a user clicks on the Google sign-in button, they are redirected to Google's authentication page. After entering their credentials and granting permission, Google redirects them back to the original website, where they are signed in.
3. **How does OAuth work? What are the steps that it takes to authenticate the user?**
* ***Authorization Request:*** Third-party app requests user authorization.
* ***User Authentication:*** User provides credentials to the authorization server.
* ***Authorization Grant:*** Server issues an authorization token to the app.
* ***Access Token Request:*** App sends the authorization grant for an access token.
* ***Access Token Issuance:*** Server issues an access token to the app.
* ***Resource Access:*** App uses the access token to access user resources.
* ***Resource Server Response:*** Server validates the token and provides resources if valid.
4. **What is OpenID?** OpenID is an authentication protocol related to OAuth. It allows users to use a single set of credentials to access multiple websites, eliminating the need for separate usernames and passwords. Users can choose their identity providers to verify their identity, enabling decentralized authentication.

## [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

1. **What is the difference between authorization and authentication?**
* Authentication is the process of verifying the identity of a user, ensuring that the user is who they claim to be.
* Authorization, on the other hand, is the process of determining what resources a user can access and what actions they can perform after they have been authenticated.

2. **What is Authorization Code Flow?**
* Authorization Code Flow is an OAuth 2.0 flow designed for web applications, where the authorization code is exchanged for an access token.

3. **What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**
* Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an enhanced version of the Authorization Code Flow, primarily designed to mitigate certain security risks for native and mobile applications.

4. **What is Implicit Flow with Form Post?**
* Implicit Flow with Form Post is an OAuth 2.0 flow suitable for JavaScript applications running in a browser environment where the access token is returned directly in the URL fragment.

5. **What is Client Credentials Flow?**
* Client Credentials Flow is an OAuth 2.0 flow used by clients to obtain an access token outside the context of any user.

6. **What is Device Authorization Flow?**
* Device Authorization Flow is an OAuth 2.0 flow designed for devices with limited input capabilities, such as smart TVs or media consoles.

7. **What is Resource Owner Password Flow?**
* Resource Owner Password Flow is an OAuth 2.0 flow where the user's credentials are exchanged directly for an access token, typically used by clients that are highly trusted with the user's credentials, such as native applications.

# THings I want to know


