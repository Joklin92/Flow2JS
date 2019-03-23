Why would you consider a Scripting Language as JavaScript as your Backend Platform?

    It's easy to setup a working network application with node.js and fast build it.
    Using the same language for front-end and back-end makes for better workflow throughout the entire program
    Minimal amount of code is required


Explain Pros & Cons in using Node.js + Express to implement your Backend compared to a strategy using, for example, Java/JAX-RS/Tomcat
Node.js and Express


Pros

    JavaScript is Asynchronous, which makes it easier to create a program that can handle several tasks at once
    Setup and building is super fast.
    Easy to setup a REST-API.

Cons

    Doesn't work well with heavy calculation as Javascript is a singlethreaded language per default. Therefore it can block some code from executing.
    Java is well integrated with Relational database compared with Node.JS.
    Node.js doesn't handle server side errors (http status code 500) very well, and can cause the server to crash.

Explain briefly how to deploy a Node/Express application including how to solve the following deployment problems:

Deploying Node.js app on digital ocean

Ensure that you Node-process restarts after a (potential) exception that closed the application

Ensure that you Node-process restarts after a server (Ubuntu) restart

Ensure that you can run “many” node-applications on a single droplet on the same port (80)

Explain the difference between “Debug outputs” and application logging. What’s wrong with console.log(..) statements in our backend-code.

Explain, using relevant examples, concepts related to testing a REST-API using Node/JavaScript + relevant packages

Explain, using relevant examples, the Express concept; middleware.

Compare the express strategy toward (server side) templating with the one you used with Java on second semester.

Demonstrate a simple Server Side Rendering example using a technology of your own choice (pug, EJS, ..).

Explain, using relevant examples, your strategy for implementing a REST-API with Node/Express and show how you can "test" all the four CRUD operations programmatically using, for example, the Request package.

Explain, using relevant examples, about testing JavaScript code, relevant packages (Mocha etc.) and how to test asynchronous code.

Explain, preferably using an example, how you have deployed your node/Express applications, and which of the Express Production best practices you have followed.

NoSQL, MongoDB and MongooseExplain, generally, what is meant by a NoSQL database.

    NoSQL is a database design that can handle a lot of data models, e.g. Key-value, graphs, documents and columns.
    It is an alternative to tradional relational databases, where data is stores in tables and schemas which are developed before the database is created.
    NoSQL is good for large sets of data. 

Explain Pros & Cons in using a NoSQL database like MongoDB as your data store, compared to a traditional Relational SQL Database like MySQL.

Explain reasons to add a layer like Mongoose, on top on of a schema-less database like MongoDB

These two topics will be introduced in period-3

Explain about indexes in MongoDB, how to create them, and demonstrate how you have used them.

Explain, using your own code examples, how you have used some of MongoDB's "special" indexes like TTL and 2dsphere

Demonstrate, using a REST-API you have designed, how to perform all CRUD operations on a MongoDB

Explain the benefits of using Mongoose, and demonstrate, using your own code, an example involving all CRUD operations