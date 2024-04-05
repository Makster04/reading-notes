# [Readings: Express, NPM, TDD, CI/CD](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-02)

## [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
1. **Classes are a template for creating ____.** Classes are a template for creating objects.
2. **Can a class declaration be hoisted?** No, class declarations cannot be hoisted.
3. **How would you describe a constructor and contextual “this” to a non-technical friend?** A constructor is a special method within a class that initializes object instances, and "this" refers to the current instance of the class being created.
Using Express Server:


## [Using Express Server](https://expressjs.com/en/guide/routing.html)
1. **Within Express, what does routing refer to?** Routing in Express refers to directing incoming requests to specific endpoint handlers based on the request's method and URL.
2. **What is the difference between a route path and a route method?** A route path defines the URL endpoint, while a route method specifies the HTTP method used to access the endpoint.
3. **When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?** Adding "next" as a parameter to a route handler is appropriate when you want to pass control to the next middleware or route handler, and if "next" has been passed to your middleware, you must call it to pass control to the next middleware in the stack.

## [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)
1. **What is an Express Router?** An Express Router is a middleware that allows modular route handling by providing a mini-application capable of handling routes.
2. **By what mean do we initialize express.Router() in an express server?** We initialize express.Router() by assigning it to a variable: const router = express.Router().
3. **What do we use route middleware for?** Route middleware is used for executing code at specific stages of the request-response cycle, such as logging, authentication, or data validation.

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)?** The class README covers using Express for building REST APIs, emphasizing modular routing with Express Router, CRUD operations, Sequelize for database communication, PostgreSQL shell commands, and considerations for hosting in the cloud, including using environment variables for database connection strings.
## Things I want to know more about
