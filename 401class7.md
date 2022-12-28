[Home](/README.md)

# Class 7 - Bearer Authorization

## Intro to JWT

1. What is a JSON Web Token (JWT)?  
JWT is a compact and secure way of transmitting information between parties a JSON object.
1. When should we use JSON Web Tokens?  
We can use JSON Web Tokens to authenticate users and authorize access to resources, as well as secure information exchange between parties.
1. Claims are expected in which structural component of a JWT?  
Claims are expected in the 'payload' component of a JWT.

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?  
The signature component of the JWT is what makes it secure. It verifies the sender and receiver with a 'secret'.
1. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.  
The 'secret'.
1. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
Concatenated content can be encrypted and anyone without the decryption key cannot access it. Secret can be sent and received securely over a secure communication channel, and stored in a secure storage system.

## JWTs Explained

1. Why use JWT?  
JWT is a useful tool for implementing authentication and authorization. JWTs are secure, self-contained and stateless.

1. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.  
JWT contains all the information it needs without the need to store any additional state on the server.

1. What are the three components (the structure) of a JWT signature?  
Three components of a JWT signature are: the header, the payload and the secret.

## Bookmark and Review

- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

## Reflection

1. What are your learning goals after reading and reviewing the class README?  
My learning goals are to understand and implement Bearer Authentication using JWT.