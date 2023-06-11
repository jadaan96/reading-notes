### why this topic matters:-
##### 1- Classes are a template for creating objects.
##### 2- Can a class declaration be hoisted? 
>No, class declarations are not hoisted
##### 3-How would you describe a constructor and contextual “this” to a non-technical friend?


* A constructor is a special function that creates objects in JavaScript, like a blueprint. "This" refers to the current object being worked with, allowing you to access its properties and methods.

##### 4-Within Express, what does routing refer to?
 > Routing refers to how an application’s endpoints (URIs) respond to client requests
 
 ##### 5- What is the difference between a route path and a route method?
* Route methods
>A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.
* Route paths
>Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
##### 6-When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
> when you want to pass control to the next middleware or route handler in the chain,When "next" is passed to your middleware as a parameter, it is your responsibility to call it within your middleware to pass control to the next middleware function or route handler.
#### Express Routing
Express Router is a feature in Express.js for creating modular and organized route handlers
#####   1- By what mean do we initialize express.Router() in an express server?

 > var router = express.Router();
 
 ##### 2- What do we use route middleware for?
Keep in mind that you can use route middleware for many things. You can use it to check that a user is logged in in the session before letting them continue.

#### What are your learning goals after reading and reviewing the class README?
* Gain an understanding of how to implement external (modular) routing with Express.
* Building a REST API server using Express.
* Learn to perform CRUD operations (Create, Read, Update, Delete) with REST and Express.

## Things I want to know more about
* best use for express Router