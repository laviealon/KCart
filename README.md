# KCart
A grocery delivery application for the kosher-consuming community.

## Backend

### High Level Design

The technologies used for the backend are:
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Passport](http://www.passportjs.org/)
- [Firebase](https://firebase.google.com/)
- [Stripe](https://stripe.com/)
- [SendGrid](https://sendgrid.com/)

The main architecture consists of a NodeJS server communicated with a database. The server is responsible for handling all requests from the client, and the database is responsible for storing all data. The server is also responsible for communicating with external services such as Firebase, Stripe, and SendGrid.
The server has a few main components:
- **Routes**: The routes are responsible for handling all requests from the client. The routes are divided into two main categories: public and private. Public routes are routes that do not require authentication, and private routes are routes that require authentication. The routes are also divided into categories based on the type of request. For example, there are routes for users, routes for stores, routes for orders, etc.
- **Controllers**: The controllers are responsible for handling the logic of the routes. The controllers are divided into two main categories: public and private. Public controllers are controllers that do not require authentication, and private controllers are controllers that require authentication. The controllers are also divided into categories based on the type of request. For example, there are controllers for users, controllers for stores, controllers for orders, etc.
- **Models**: The models are responsible for defining the schemas of the data that is stored in the database. The models are divided into two main categories: public and private. Public models are models that do not require authentication, and private models are models that require authentication. The models are also divided into categories based on the type of data. For example, there are models for users, models for stores, models for orders, etc.
- **Middleware**: The middleware is responsible for handling the authentication of the private routes. The middleware is divided into two main categories: public and private. Public middleware is middleware that does not require authentication, and private middleware is middleware that requires authentication. The middleware is also divided into categories based on the type of request. For example, there is middleware for users, middleware for stores, middleware for orders, etc.
- **Services**: The services are responsible for handling the communication with external services. The services are divided into two main categories: public and private. Public services are services that do not require authentication, and private services are services that require authentication. The services are also divided into categories based on the type of service. For example, there are services for Firebase, services for Stripe, services for SendGrid, etc.
- **Utilities**: The utilities are responsible for handling miscellaneous tasks. For example, there are utilities for sending emails, utilities for generating tokens, etc.

#### Controllers

For example, 