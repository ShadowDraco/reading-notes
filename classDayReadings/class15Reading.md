# Authentication

## Auth in our apps will provide a complete and secure experience for individual users

### [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

What is OAuth?

- OAuth is a framework that allows servers to delegate authentication processes and provide access to one another with a third-party. OAuth is a framework to work with a third party authenticator.

Give an example of what using OAuth would look like.

- OAuth looks like a user logging in or attempting an action that requires their identity to be verified using the credentials and permission given by another trust worthy site.

How does OAuth work? What are the steps that it takes to authenticate the user?

<small>

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

3. The first site gives this token and secret to the initiating user’s client software.

4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

6. The user approves (or their software silently approves) a particular transaction type at the first website.

7. The user is given an approved access token (notice it’s no longer a request token).

8. The user gives the approved access token to the first website.

9. The first website gives the access token to the second website as proof of authentication on behalf of the user.

10. The second website lets the first website access their site on behalf of the user.

11. The user sees a successfully completed transaction occurring.
    </small>

What is OpenID?

- OpenID is an authentication service that used to handle its own SingleSignOn service but was beat out by a company with a recognizable name. It returned as a layer for OAuth which made the two work in tandem ever since.

### [Authorization and Authentication flows](https://auth0.com/docs/flows)

What is the difference between authorization and authentication?

- Authorization provides a user access to resources, and authentication is verifying the user's identity

What is Authorization Code Flow?

- Authorization code flow exchanges a secure authorization code for a user token

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

- Mobile and native applications require additional security, and single-page apps have special challenges

What is Implicit Flow with Form Post?

- Public clients that do not have the ability to store client secrets can use the implicit flow with form post to perform user authentication with only an ID token

What is Client Credentials Flow?

- CCF is for CLIs, daemons or other services running on the backend which authorizes an app rather than a user (no username and password, but built in security on the app authorizing itself with the server)

What is Device Authorization Flow?

- Device authorization means authorizing the device by going to a trusted place to prevent devices with limited text-entering capabilities having a poor user experience

What is Resource Owner Password Flow?

- Highly trusted applications can use a username and password flow with an interactive form but should only be used when the more secure _Authorization Code Flow_ cannot be used

## Things I want to know more about
