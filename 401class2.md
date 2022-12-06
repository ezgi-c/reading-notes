[Home](/README.md)

# Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.  
    Middleware provide services to applications beyond those available in the operating system.
1. Express is the most popular <ins>Node web framework</ins>.
1. Express is “unopinionated.” What does that mean?  
    Unopinionated frameworks, in contrast to opinionated, have very few restrictions on how to put components together. It gives the programmer a wide range of choices in how to structure their app.
1. What is a module and why is modularity useful to us as developers?  
    A module is a file or a library that can be imported into other code using Node's `require()` function. Modularity is useful for organizing code into manageable parts.

## What is NPM?

1. What version of npm are you running on your machine?  
    8.12.1
1. What command would you type to install a library/package called ‘jshint’ into your node project?  
    `npm install jshint`

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.  
    Even though tests requires more time commitment at the beginning of a project for establishing them, they end up saving a lot more time towards the end, as well as improving design quality of the code.
1. What are three expected benefits of testing?  

    > - many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
    > - the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
    > - although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

1. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.  
    Individual pitfalls include writing too many tests at once and not running tests frequently enough. Team pitfalls include not all team members using TDD and poor maintenance of the test suite.

## CI/CD

1. What are three benefits of Continuous Integration?  
    - Ensure everyone's changes integrate
    - Catch bugs
    - Reduce merge conflicts
1. What is the difference between Continuos Delivery and Continuous Deployment?  
    Continuous Delivery is developing software in a way that it could be released at any time. Continues Deployment is an extension of Continuous Delivery; deploys new features immediately.
1. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.  
    Developers make changes locally in their computer and push to GitHub to share it with others. With CI, changes must past through CI server to be determined whether or not it will be integrated to main branch. GitHub uses _webhooks_ to send info about our project to the server and publishes the changes if they pass the tests. 

## Bookmark and Review

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)
