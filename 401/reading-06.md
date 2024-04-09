# [Reading: Authentication](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-06)

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
1. **Explain to a non-technical friend how you would safely hash and store a password.** To securely hash and store a password, I would use a cryptographic hashing algorithm like Bcrypt. This involves taking the user's password, passing it through the Bcrypt algorithm, which generates a hash, and then storing this hash in the database.

2. **What is Bcrypt?** Bcrypt is a password-hashing function designed to be slow and computationally intensive, making it difficult for attackers to brute-force passwords.

3. **Why might you use something like Bcrypt?** Bcrypt is used to securely store passwords because it adds a layer of security by making it computationally expensive for attackers to crack hashed passwords, even if they have access to the hashed values.

   
## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
1. **What is Basic Authentication?** Basic Authentication is a simple authentication scheme built into the HTTP protocol, where the client sends credentials in the form of a username and password with each request.

2. **What properties are necessary in the header of a Basic Auth request?** In the header of a Basic Auth request, the "Authorization" header is necessary, which includes the word "Basic" followed by a space and then the Base64-encoded string of "username:password".

3. **How are username: password in Basic Auth encoded?** The username and password in Basic Auth are encoded using Base64 encoding before being transmitted over the network. However, it's important to note that Base64 encoding is not encryption and can be easily decoded.


## [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
1. **Define the authentication process to a non-technical recruiter.** The authentication process involves verifying the identity of a user trying to access a system or application. This is typically done by requesting credentials (e.g., username and password), validating them against stored credentials, and granting access if they match.

2. **How should your error messaging respond (both HTTP and HTML)? Why?** Error messaging should respond with appropriate HTTP status codes (e.g., 401 Unauthorized) and HTML error messages to inform users of authentication failures without revealing too much information about why the authentication failed. This helps prevent attackers from exploiting vulnerabilities.

3. **Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.** Did it

## Bookmark and Review** 

1. **[bcrypt docs](https://www.npmjs.com/package/bcrypt)**

## Additional Questions
1. **Looking ahead at this module’s [course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-2), What do you look forward to learning?** I really look forward to learning how to get ready for these whiteboard interviews.
2. **What are your learning goals after reading and reviewing the [class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-06/)?** The class README on Authentication provides a concise guide for secure user authentication in web apps. It covers key concepts like password encryption, Basic Authorization, and using Sequelize for custom functionality. Students are urged to develop debugging skills for system integrity.

## Things I want to know
