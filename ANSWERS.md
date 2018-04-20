<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    * Middleware is a function that runs in between a request and response (runs before each request)
    * Sessions are a unique place to store data that persists between requests to let the request whether the user is authenticated or not
    * bcrypt is an express module that is used to hash password in a one way method
    * JWTs (JSON Web Tokens) are pieces of data stored in the browser once authenticated that are passed back to the server to confirm that a user has access to a resource.

2.  What does bcrypt do in order to prevent attacks?
* bcrypt hashes a password in a one way method and can only verify whether a guessed password is correct or not

3.  What are the three parts of the JSON Web Token?
* headers
* payload
* signature
