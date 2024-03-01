# [Readings: Putting it all together](https://github.com/codefellows/seattle-code-301d108/tree/main/class-05)


## [React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)
1. **What is the single responsibility principle and how does it apply to components?** The single responsibility principle states that a component should ideally only do one thing. In React, this means each component should focus on rendering UI based on the data it receives.
2. **What does it mean to build a ‘static’ version of your application?** Building a 'static' version of an application involves creating components that render UI but do not include interactivity or state management. This version serves as a foundation before adding dynamic functionality.
3. **Once you have a static application, what do you need to add?** After creating a static application, you need to add interactivity by identifying where your state should live, implementing stateful components, and defining how the UI should respond to changes in state.
4. **What are the three questions you can ask to determine if something is state?** Does it change over time? Can it be computed based on any other state or props? Does it need to be passed to other components?
5. **How can you identify where state needs to live?** Identify where state needs to live by finding the components that require it for rendering or responding to user interactions. Centralizing state management in the highest common ancestor of these components simplifies data flow and reduces potential bugs.


## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. **What is a “higher-order function”?** A "higher-order function" is a function that either takes one or more functions as arguments or returns a function as its result.
2. **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?** The greaterThan function compares two numbers. In line 2, it defines a new function, greaterThan(x), which takes a single argument, y, and returns a boolean value indicating whether y is greater than x.
3. **Explain how either map or reduce operates, with regards to higher-order functions.** Both map and reduce are higher-order functions. Map applies a function to each element of an array and returns a new array containing the results. Reduce applies a function against an accumulator and each element in the array (from left to right) to reduce it to a single value.


## Things I want to know more about




   


