[Home](/README.md)

# Express REST API

## Review: ES6 Classes

1. Classes are a template for creating <ins>objects</ins>.
1. Can a class declaration be hoisted?  
No, classes must be defined before they can be constructed.
1. How would you describe a constructor and contextual “this” to a non-technical friend? 
Constructor is used within a class to initialize and object. We can use contextual "this" to access the object created. 


## Using Express Routing

1. Within Express, what does routing refer to?  
Routing refers to how an application's endpoints (URIs) respond to client requests.
1. What is the difference between a route path and a route method?  
A route method is derived from and attached to one of the HTTP methods including `GET`, `POST` , `PUT` and `DELETE`.
Route paths, combined with route methods, define the endpoints at which requests can be made. 
1. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?  
We need to add 'next' as a parameter when we provide multiple callback functions. 

## Express Routing

1. What is an Express Router?  
Express Router is a mini express application with just the routing functionality.
1. By what mean do we initialize express.Router() in an express server?  
We call an instance of the `express.Router()` in our application as follows:

``` js
// get an instance of router
    var router = express.Router();

    // home page route (http://localhost:8080)
    router.get('/', function(req, res) {
        res.send('im the home page!');
    });

    // about page route (http://localhost:8080/about)
    router.get('/about', function(req, res) {
        res.send('im the about page!');
    });

    // apply the routes to our application
    app.use('/', router);

```

1. What do we use route middleware for?  
Middleware is used for telling our application to do something before a request is processed. For example, check for authentication, logging data for analytics, etc.
