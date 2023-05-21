# Authentication

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

Explain to a non-technical friend how you would safely hash and store a password.

- Hashing a password is the process of turning the characters in a password into other characters based on a set algorithm. A hash will generate a different string of characters that will be stored, and the server that checks if someone enters the correct password will check if the password entered matches the hashed value.

What is Bcrypt?

- Bcrypt is a key stretching, adaptive, hash algorithm function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a security factor that predicts the time it will take to run the function.

Why might you use something like Bcrypt?

- Bcrypt is able to scale the complexity of the hash to make brute force attacks take even longer as the speed of computers increases.

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

What is Basic Authentication?

- Basic authentication is a method for a browser to prove a username and password when making a request. Its a format for doing a basic form of authentication and not a service like Auth0.

What properties are necessary in the header of a Basic Auth request?

- This request contains a header _Authorization: Basic \<Credentials\>_ where the credentials are Base64 encoded as an ID and password.

How are username:password in Basic Auth encoded?

- The encoding for authorization is base64 encoded. This is not a secure or encrypted encoding, so doing these requests over https is essential

##[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

Define the authentication process to a non-technical recruiter.

- Authentication is the process of verifying that an individual, entity, or website is who it claims to be. Like presenting a key card, or a username and password. The idea is to authenticate someone by having them provide information only they should have.

How should your error messaging respond (both HTTP and HTML)? Why?

- Simply Generic. It should be generic because a malicious user can differentiate between a wrong username or password or otherwise find vulnerabilities in the way that sensitive data is stored and secured if messages are not generic enough.

_Consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle._

### Things I want to know more about

- What other vulnerabilities can be exploited from the outside. Error messages, time differences in the returns of errors, etc.

#### Reflection

- Zip? like zipping a file? that's an interesting challenge. I'd love to learn about stacks and queues, and think more about the implementations for them. And Auth is a nightmare to dive into when its riiiight before your final project so I'm glad we can spend more time on it this time around haha. Also, putting methods on models to simplify and limit repeating in queries is such a great idea wow
