# Bearer Authentication

## [Intro to JWT](https://jwt.io/introduction/)

What is a JSON Web Token (JWT)?

- Json Web Tokens are a compact and self-contained way to transmit data securely but combining data with a secret hash

When should we use JSON Web Tokens?

- JWT's (JOTS) are useful for authorization and information exchange

Claims are expected in which structural component of a JWT?

- Claims (information about the sender / from the sender) are expected in the payload.

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

If I get a JWT and I can decode the payload, how can we call that secure?

- The JWT and the payload are like the salt in the soup. If you change the ingredients in the soup then the whole flavor is off. The receiver still has their secret ingredient and so no one can decipher the soups real contents, or break the secure recipe book.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- the hash

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

- The content in the message being sent is combined with a secret message that only the sender and receiver know. So if someone knows how to decode the content that is not important. For example a username, they would still be powerless to discover what that secret message is, and thus will not be able to decrypt any important information by intercepting the data being sent between server and client.

## [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

Why use JWT?

- JWT's are a fast and secure way to send, recieve, and store access to sensitive data. Reusable and accessible

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- Compact and self-contained JWT's can be sent easily with all of the data you need through http allowing users to verify their identity quickly with a lightweight payload and then re-authenticate easily by storing a secure, lightweight, and reuseable token

What are the three components (the structure) of a JWT signature?

- The three components are the Header, Payload, and Signature

### Reflection

- its super cool to see how flexible sequelize is and all of the amazing quality of life features it possess, I can't wait to learn how they work and implement some JWT

## Things I want to know more about

- Functions described on the model itself and other model properties