## 12-14-20

### Using Express Routing
- How do endpoints respond to client requests
- Callback (handler functions)
- Express supports methods that correspond to all HTTP request methods
- Route paths can be strings, string patterns, or regex
- Multiple callback functions that behave like middleware to handle a reuest as long as they invoke a next parameter

### Supertest
- Driven by superagent for testing node.js HTTP servers
- Works with any test framework
- Don't have to pass the app or URL each time

### Using Middleware
- Middleware functions are functions that have access to req, res, and the next middleware function in the application’s request-response cycle
- Middleware functions can execute code, make changes to req and res, end the req-res cycle, call the next middleware
- Route handlers enable you to define multiple routes for a path
- Middleware can be declared in an array

### Express Middleware
- The order in which the middleware is written in the file is the order in which they execute
- body-parser is used to parse body of requests with payloads
- cookie-parser does cookie stuff
- express-session
