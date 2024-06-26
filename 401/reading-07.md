# [Reading: Bearer Authorization](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-07)

## [Intro to JWT](https://canvas.instructure.com/courses/8944808/discussion_topics/21361257/submit)
1. **What is a JSON Web Token (JWT)?** A JSON Web Token (JWT) is a compact, self-contained means of securely transmitting information between parties as a JSON object. It is used for authentication and authorization purposes and consists of three parts: a header, a payload, and a signature.
2. **When should we use JSON Web Tokens?** JSON Web Tokens should be used in scenarios where stateless, secure authentication and authorization mechanisms are required. They are commonly used in web applications and APIs where sessions need to be maintained without storing session state on the server.
3. **Claims are expected in which structural component of a JWT?** Claims are expected in the payload component of a JWT. The payload contains the actual data being transmitted, such as user information or authorization details, encoded as JSON objects.

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
1. **If I get a JWT and I can decode the payload, how can we call that secure?** While the payload of a JWT is base64 encoded and can be decoded, the security of JWTs relies on the integrity of the signature. Decoding the payload does not compromise the security as long as the signature remains intact. The signature is used to verify that the payload has not been tampered with.
2. **If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.** Both the sender and receiver must know the secret key used to generate the signature appended to the JWT. This secret key is used to sign the payload, and the receiver uses it to verify the integrity of the JWT.
3. **Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.** The concatenated content (payload) and secret are used to generate a signature, which is appended to the JWT. This JWT can then be securely transmitted over the network. The receiver, who also possesses the secret, can verify the integrity of the JWT by recalculating the signature using the received content and comparing it with the signature appended to the JWT. This ensures that the content has not been altered during transmission.

   
## [WTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
1. **Why use JWT?** JWTs provide a secure and efficient way to transmit information between parties. They are widely used for authentication and authorization in web applications and APIs due to their compactness, self-containment, and security features.
2. **JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.** Imagine JWTs as small, sealed envelopes containing important information. These envelopes are compact, meaning they don't take up much space, and they contain everything needed inside them. This makes it easy to pass them around without needing to constantly check back with a central authority. For example, if you need to prove your identity to access different rooms in a building, you can carry your ID in this sealed envelope (JWT), which contains all the necessary information. You can show this envelope to security guards at each door, and they can verify your identity without needing to contact the main office.
3. **What are the three components (the structure) of a JWT signature?** The three components of a JWT signature are:
*  1. ***Header:*** Contains metadata about the type of token and the signing algorithm being used.
*  2. ***Payload:*** Contains the actual data being transmitted, such as user information or authorization details.
*  3. ***Signature:*** Used to verify that the payload has not been tampered with. It is generated by combining the encoded header, encoded payload, and a secret key, using a specified cryptographic algorithm.


## Bookmark and Review
* [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

## Reflection
1. **What are your learning goals after reading and reviewing the [class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-07/)?** The class README introduces Bearer Tokens for secure client-server communication post-login, demonstrated through Express middleware for token validation. Additionally, it explains Sequelize Virtual Properties, enabling the storage of calculated values in data models without database persistence, providing essential skills for building secure authentication systems in web applications.
## Things I want to know
