# [Readings: Express, NPM, TDD, CI/CD](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-02)

## [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
1. **Explain middleware, answer as though I were a non-technical recruiter.** Middleware is like a bridge between different parts of a software system. It handles requests and responses as they move through the system, performing tasks such as authentication, logging, and error handling.
2. **Express the most popular __ __ ____.** Express is the most popular web application framework for Node.js. It simplifies the process of building web applications and APIs by providing a set of features and tools.
3. **Express is “unopinionated.” What does that mean?** Express is described as "unopinionated" because it doesn't impose a specific way of organizing code or handling tasks. Developers have the freedom to structure their applications and make decisions based on their preferences and requirements.
4. **What is a module and why is modularity useful to us as developers?** A module is a reusable piece of code that encapsulates functionality. Modularity is useful to developers because it promotes code organization, reusability, and maintainability by breaking down large systems into smaller, manageable parts.

## [What is NPM?](https://docs.npmjs.com/about-npm)
1. **What version of npm are you running on your machine?** To find out the version of NPM installed on your machine, you can run the command npm -v.
2. **What command would you type to install a library/package called ‘jshint’ into your node project?** To install the 'jshint' library/package into your Node.js project, you would type the command npm install jshint.

## [What is TDD?](https://www.agilealliance.org/glossary/tdd/)
1. **Explain why tests are important. Please explain as though I were your non technical elder.** Tests are important because they ensure that the software behaves as expected, reducing the likelihood of errors and providing confidence in its functionality, especially for non-technical elders who might not understand the technical details but value the reliability of the software.
2. **What are three expected benefits of testing?**
* Ensures software correctness
* Facilitates code maintenance and refactoring
* Provides documentation for how the software should behave
3. **Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.**
* **Individual Pitfalls:** Over-reliance on tests leading to neglect of other aspects, writing tests that are too coupled to implementation details.
* **Team Pitfalls:** Lack of communication about testing strategies, inconsistent testing practices across team members.

## [CI/CD](https://www.youtube.com/watch?v=k2aNsQKwyOo)
1. **What are three benefits of Continuous Integration?**
* Detects integration issues early
* Facilitates faster feedback loops
* Improves overall software quality
2. **What is the difference between Continuos Delivery and Continuous Deployment?**
* **Continuous Delivery:** Software is automatically prepared for release but requires manual approval for deployment.
* **Continuous Deployment:** Changes to the software are automatically deployed to production without manual intervention.
3. **Explain how GitHub fits into this process assuming the listener comes from a non-technical background?** GitHub serves as a platform for hosting code repositories and collaboration. In the CI/CD process, GitHub is often integrated with CI/CD tools like Jenkins or GitHub Actions to automate tasks such as testing, building, and deploying software. It acts as a central hub for version control and collaboration among developers and other stakeholders.
  
## Bookmark and Review
* [nodeJS docs](https://nodejs.org/docs/latest/api/)
* [npm docs](https://docs.npmjs.com/)
* [express docs](https://expressjs.com/en/4x/api.html)
* [http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
* [supertest](https://github.com/ladjs/supertest)

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-02/)?** The README summarizes learning goals and topics for a class on Express server mechanics, including routing, middleware, and testing. Students will learn Node modules, code modularization, Express middleware, HTTP status codes, and testing techniques like TDD. The README covers Express routing, request/response objects, middleware functions, and testing with libraries like supertest and Jest.

## Things I want to know more about
