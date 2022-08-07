# Middleware


The middleware in node.js is a function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle. This function can be used for modifying the req and res objects for tasks like adding response headers, parsing requesting bodies, and so on.

Middleware functions can perform the following tasks:

Execute any code.
Make changes to the request and the response objects.
End the request-response cycle.
Call the next middleware in the stack.

Next()

Next() is a middleware function that calls for the control of another middleware once the code is completed. You can wait till the network operations are completed before you go to the next step. As with the functionality of route handlers, a middleware will ensure the receipt of the request and response objects effortlessly.

Now, the request object is referred to as the req variable and the response object as the res variable. The next middleware function is referred to as the next function. It plays a responsible role in creating the request-response cycle of the application.

Here are some vital tasks performed by the middleware functions:

Completing the request and response cycle
Executing the codes
Calling the subsequent middleware function in the line
Making necessary changes to the request and response objects as per the requirement

Types of middleware in Node.js

1. Application-level middleware
2. Router-level middleware
3. Route-level middleware
