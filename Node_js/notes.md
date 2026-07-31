# Node.js

## Roles and features of node.js

- Node.s is an open source, server-side javascript runtime built on Google's V8 engine, supporting Linux, Windows, and Mac OSX
- It is event-driven and uses asynchronous, non-blocking i/o, enabling efficient processing of web service requests.

### Difference between javascript and node.js

- Javascript is commonly used for client side scripting in browsers, while node.js allows javascript to run on the server side.
- Node.js handles server-side tasks such as processing HTTP request and routing, complementing client-side javascript.

## Express.js framework

- Express.js is a configurable framework that simplifies building Node.js application by abstracting lower-level APIs.
- It provides features like routing, middleware, template rendering, and static asset management, helping developers build applications quickly and efficiently.

### Modules and Module specifications

- A module is a file or collections of files containing related code serving a specific purpose.
- Module specification like CommonJS and ES modules define conventions for creating packages in Node.js
- Developers rely heavily on modules because of their reusability as well as their ability to break down complex code into manageable chunks
- Library owner can change the commonjs module into ES module by changing the extension(.js to .jsm)
- use them we have to export them first

### Import and require statements

- Module calling techniques into external applications
- **require** can be called anywhere in the code, support dynamic binding and is synchronous. it's used by commonjs, and errors are identified at runtime
- **import** must be called at the beginning of the file, uses static binding, and is asynchronous. it's used by ES, and errors are identified at compile time
- import is generally faster for large-scale application due to asynchronous loading.

### Purpose and roles of javascript

- Javascript is a widely used language for adding dynamic behavior to websites, originally running on the client side.
- It is an interpreted language, not requiring compilation, and can now run on servers embedded systems.

### Client-side vs Server-side javascript

- Client side javascript runs in the browser, handling user interface interactions and sending web service requests in JSON over HTTP.
- **Node.js**: with javascript process and routes these web services requests and routes web service requests on the server, running javascript code outside the browser.

### Node.js Framework

- Node.js is a server side framework that uses javascript to build scalable, concurrent server applications.
- It allows developers to quickly develop server applications with minimal tools, replacing traditional backend languages like java or php in handling web service requests.
