# Origins and history of CommonJS

CommonJS was developed in 2009 by Kevin Dangoor and other developers. It was created to solve the problem of managing dependencies in JavaScript projects. Before CommonJS, JavaScript code was typically written in a single file, making it difficult to manage dependencies.


### Characteristics of CommonJS
* CommonJS is a `synchronous` module system. This means that when a module is imported, the code `execution is blocked` until the module is loaded.

```javascript
// use require to import 
const fs = require('fs')

// this for export
module.export = fs;
```

| Pros                                                                 | Cons                                                                 |
|----------------------------------------------------------------------|----------------------------------------------------------------------|
| ✅ Easy to learn and use                                             | ❌ Synchronous module loading can lead to performance issues         |
| ✅ Widely supported and used in Node.js                              | ❌ No tree-shaking support, which can result in larger bundle sizes  |
| ✅ Synchronous loading ensures all dependencies are available before execution | ❌ Not suitable for client-side/browser environments                  |



<br>
<br>

# ES MODULES
ES Modules is a modern module system that is built into the JavaScript language. ES Modules was created to solve the problem of managing dependencies in JavaScript projects, both on the client-side and server-side.

> A more modern approach to Javascript module management.
