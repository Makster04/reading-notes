# [Readings: Redux - Asynchronous Actions](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-38)

## [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic))
1. **Why use Redux middleware?**
2. **Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**
3. **How are we accommodating async in our Redux app?**
   
## [thunk middleware](https://github.com/reduxjs/redux-thunk)
1. **Why would you need redux-thunk middleware?** To enable writing action creators that can perform asynchronous operations before dispatching actions.
2. **Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.** Function (thunk).
3. **Describe how any return value from the inner thunk function will be made available.** The return value from the inner thunk function is passed back to the dispatching code, allowing for additional chaining or handling based on the result of the async operation.
Reflection


# Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-38/)?**
* Understand how to integrate and use Redux middleware for handling asynchronous actions.
* Learn the detailed flow of async actions in Redux applications.
* Gain proficiency in writing and managing thunks with Redux Thunk middleware.
* Develop the ability to accommodate and manage async operations within a Redux app effectively.





## Things I want to know
