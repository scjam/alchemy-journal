## 12-13-20

### HTTP Basics
- The foundation of the web
- Allows for communication between different hosts and clients
- Stateless
- Communication takes place over TCP/IP and via a request/response pair
- Requests are sent through URLs
- Protocol, host, port, resource path, query
- Request verbs: GET, POST, PUT, DELETE
- Status Codes: 1xx Info msgs, 2xx successful, 3xx redirection, 4xx client error, 5xx server error
- General headers and entity headers
- req.body, req.query, res.send, res.set etc etc

### How DNS works
- Computers communicate via IP addresses but words are easier for humans to remember, DNS brings the numbers and words together
- Ok literally all computer things should be explained via cute cartoons
- Browser checks if it knows the site, then asks the OS if it knows, and if not it will call the resolver
- If resolver doesn't know, the root needs to be checked, if it doesn't know than .com TLD server
- Once the resolver gets the right IP, it reports back and sends you to the right website, or throws error

### HTTP and REST
- API: contract provided by one software to another
- REST: architecture style for designing network apps, almost always HTTP
- GET, POST, PUT, DELETE, HEAD, OPTIONS, PATCH
- Some APIs require authentication
- Postman to test
