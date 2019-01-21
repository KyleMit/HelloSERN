# Notes

High level outline of the frameworks, tools, and concepts in the SQL, Express, React, Node (SERN) stack

## Development Stack

* Client - SPA
  * [React](https://reactjs.org/)
    * [React DOM](https://reactjs.org/docs/react-dom.html)
    * [State](https://reactjs.org/docs/state-and-lifecycle.html)
      * ~~[redux](https://redux.js.org/basics/usage-with-react)~~
      * React State Management
        * [Context API](https://reactjs.org/docs/context.html)
        * Encapsulation
        * Props through State Tree
        * Sideload
        * Subscription
    * [React Router](https://reacttraining.com/react-router/web/guides/quick-start)
      * [`History.pushState()`](https://developer.mozilla.org/en-US/docs/Web/API/History_API)
      * [HashRouter](https://reacttraining.com/react-router/web/api/HashRouter) uses [`window.location.hash`](https://developer.mozilla.org/en-US/docs/Web/API/Window/location)
    * Views
      * [JSX](https://reactjs.org/docs/introducing-jsx.html)
      * [CSS-in-JS](https://cssinjs.org/)
        * Multi-tenant themes?
      * Library
        * [Material UI](https://material-ui.com/)
        * [Bootstrap](https://facebook.github.io/create-react-app/docs/adding-bootstrap) (CSS)
  * Authentication
    * [JSON Web Tokens](https://jwt.io/) (JWT)
  * [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
    * ~~[AXIOS](https://github.com/axios/axios)~~
    * [Polyfill](https://github.com/github/fetch)
* Server - API
  * [Node.js](https://nodejs.org/en/)
  * [Express](https://expressjs.com/)
    * Controller 
      * Service
        * Data Access Object (DAO)
          * [MySQL Driver](https://dev.mysql.com/downloads/connector/nodejs/8.0.html)
          * ~~Object Relational Mapping (ORM)~~
  * [Aurelia DI](https://aurelia.io/docs/fundamentals/dependency-injection/)
  * Authentication
    * [Passport](http://www.passportjs.org/)
* Database
  * [MySQL](https://www.mysql.com/)
  * Procs written in Javascript (not SPs)
* Testing
  * [Mocha Test Runner](https://mochajs.org/)
    * End to End (ETE) API Test
  * Web Acceptance
    * [Chrome Driver](https://sites.google.com/a/chromium.org/chromedriver/)
    * [Cypress](https://www.cypress.io/)

## Tooling

* [Webpack](https://webpack.js.org/)
  * [Babel](https://babeljs.io/)

## Deployment Infrastructure

* [Amazon Web Services (AWS)](https://aws.amazon.com/)
  * Content Delivery Network (CDN)
* [CloudFront](https://aws.amazon.com/cloudfront/)
* [AWS S3](https://aws.amazon.com/s3/)
* [AWS API Gateway](https://aws.amazon.com/api-gateway/)
* [AWS Lambda](https://aws.amazon.com/lambda/)
  * [Serverless Framework](https://serverless.com/)

## Architectural Concepts

* [REST](https://www.wikiwand.com/en/Representational_state_transfer) - REpresentational State Transfer
  * Levels of Rest Compliance
  * Evolvability
  * [Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html)
    * Level 0
    * Level 1 - Resources
    * Level 2 - HTTP Verbs
    * Level 3 - Hypermedia Controls
* Patterns
  * [Strategy Pattern](https://www.wikiwand.com/en/Strategy_pattern)
  * [Data Access Object](https://www.wikiwand.com/en/Data_access_object)
  * [Inversion of Control (IOC)](https://www.wikiwand.com/en/Inversion_of_control)
  * [Dependency Injection (DI)](https://www.wikiwand.com/en/Dependency_injection)
* [SOLID](https://www.wikiwand.com/en/SOLID)
  * Single Responsibility Principle
  * Open / Closed Principle
  * Liskov Substitution Principle
  * Interface Segregation Principle
  * Dependency Inversion Principle
* Javascript
  * [JS Cheatsheet](https://mbeaudru.github.io/modern-js-cheatsheet/)
  * [ES6](http://es6-features.org/)
    * Import > (~~require~~)
    * Promises
* Multi-tenancy

## Questions

* Typescript
* Async / Await
