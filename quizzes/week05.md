# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CRUD refers to the four functions that are considered necessary to implement a persistent storage application: create, read, update and delete.
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively.
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object-Relational Mapping (ORM), and the PyMongo MongoDB ORM for Python is a native and highly popular Python driver for MongoDB. It supports MongoDB versions MongoDB 2.6, 3.0, 3.2, 3.4, 3.6, 4.0, 4.2, 4.4, and 5.0. The package is essentially built to provide Python developers with all the right tools to interact with a MongoDB database.
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
HTTP request bodies are theoretically allowed for all methods except TRACE, however they are not commonly used except in PUT, POST and PATCH. Because of this, they may not be supported properly by some client frameworks, and you should not allow request bodies for GET, DELETE, TRACE, OPTIONS and HEAD methods.
```

**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronous programming, and asynchronous programming.
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import defaultExport from "module-name"

let mongoose = require('mongoose');
```

**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is software that lies between an operating system and the applications running on it, enabling communication and data management.
```

**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
data, and ETL
```

**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
string winter1 = Request.QueryString["winter"];
string winter2 = Request["winter"];
```