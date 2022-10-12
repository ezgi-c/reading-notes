[Home](/README.md)

# Class 07 - APIs

## API Design Best Practices

1. What does REST stand for?  
Representational State Transfer
1. REST APIs are designed around a <u>_resource_</u>.
1. What is an identifier of a resource? Give an example.  
An identifier is a URI (Universal Resource Identifier) that uniquely idengifies a resource. Example URI of a customer order:

```http
https://adventure-works.com/orders/1
```

1. What are the most common HTTP verbs?  
GET, POST, PUT, PATCH, and DELETE.

> - GET retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.
> - POST creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.
> - PUT either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.
> - PATCH performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.
> - DELETE removes the resource at the specified URI.

1. What should the URIs be based on?  
URIs should be based on nouns (the resource) and not verbs (the operations on the resource). Example:

```http
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid
```

1. Give an example of a good URI.  

```http
https://adventure-works.com/orders
```

1. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
A chatty API means to have the client make a large number of requests for small size resources. It is a bad thing due to the load it imposed on the server.
1. What status code does a successful `GET` request return?  
HTTP status code 200 (OK)
1. What status code does an unsuccessful `GET` request return?  
HTTP status code 404 (Not Found)
1. What status code does a successful `POST` request return?  
HTTP status code 201 (Created)
1. What status code does a successful `DELETE` request return?  
HTTP status code 204 (No Content)

### Reference

https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design
