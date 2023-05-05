# cyber-security-project
project

## Technology selection

### Backend:

For the backend, Node.js was used as the primary technology. Node.js is a popular open-source server-side runtime environment that allows developers to build scalable and high-performance web applications using JavaScript. The reason for choosing Node.js is that it provides a non-blocking I/O model, making it ideal for building fast and scalable web applications. 

For the web framework, Express.js was chosen. Express.js is a popular open-source web framework for Node.js that simplifies the process of building web applications. It provides a minimalist approach to web development, allowing developers to build scalable and efficient applications quickly.

For data storage, MongoDB was chosen. MongoDB is a NoSQL document-oriented database that provides high performance, scalability, and flexibility. It allows developers to store and retrieve data in JSON-like documents, making it easy to work with data.

### Authentication and Authorization:

For authentication and authorization, JSON Web Tokens (JWT) were used by me. JWT is an open standard for securely transmitting information between parties as a JSON object. It is widely used for authentication and authorization purposes in web applications. 

## installation guidelines

### Installation dependency
Enter the root directory
```
npm install
```
then
```
npm preinstall
```
### Run
Start the server end in development mode
```
SET NODE_ENV=development& npm run dev:server
```
then start the front end
```
npm run dev:client
```
