# [Readings: Redux - Combined Reducers](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-37)

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
1. **Why create multiple reducers?**
* To handle different parts of the state independently, improving organization and maintainability.
2. **How would you combine multiple reducers?**
*  By using Redux's combineReducers function, which merges individual reducers into a single root reducer.
3. **How will you manage state as an immutable object? why?**
* By using immutable update patterns to ensure predictability and to take advantage of performance optimizations.

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)
1. **combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**
  * Reducers
2. **Explain how combineReducers assembles the new state tree.**
* It maps the state keys to corresponding reducer functions, combining their results into a single state object.
3. **How would you define initial state in an app using combineReducers?**
* By specifying initial state values within each individual reducer function.

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)
1. **Why will you want to split your reducing functions as your app becomes more complex?**
* To manage different parts of the state more easily and reduce complexity in each function.
2. **The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**
* combineReducers; createStore.
3. **What is a popular convention when naming reducers?**
* Naming them after the state slice they manage.

# Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-37/)?**
* Understand the principles and use cases for managing state with Redux.
* Learn how to create and combine multiple reducers effectively.
* Master the process of managing state immutably to ensure reliable application performance.
* Gain practical skills in applying combineReducers and structuring reducer functions.
* Develop proficiency in defining initial state and handling complex state management scenarios in larger applications.

## Things I want to know
