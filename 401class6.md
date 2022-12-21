[Home](/README.md)

# Class 6 - Authentication

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.  
Hashing is turning a password into a string of characters. The hash is then safely stored in a database.
1. What is Bcrypt?  
Bcrypt is a password hashing algorithm.
1. Why might you use something like Bcrypt?  
Bcrypt is effective in protection against brute force attacks with utilization of a security factor.

## Basic Auth

1. What is Basic Authentication?  

> In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

1. What properties are necessary in the header of a Basic Auth request?  
`Authorization` field with a value that contains the word `Basic` followed by a space and the base64-encoded username and password.
1. How are `username:password` in Basic Auth encoded?
Username and password are combined into a single string with a `:` separating them, then encoded using base64.

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.  
Authentication is the process of verifying identity of a user or device. Methods of authentication include password-based authentication, two-factor authentication, biometric authentication, and token-based authentication.
1. How should your error messaging respond (both HTTP and HTML)? Why?  
For HTTP error messaging, the correct HTTP status code should be returned.
For HTML error messaging, a user-friendly message should be displayed to the user.
Designing clear, concise, user-friendly error messaging makes it easier to understand and solve issues.

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

## Additional Questions

1. Looking ahead at this module’s course schedule, What do you look forward to learning?  
Everything.
1. What are your learning goals after reading and reviewing the class README?  
My learning goals include understanding and implementing the authentication process, hashing and modeling a user and safely storing their data.