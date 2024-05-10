# [Reading: useState() Hook](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-27)

## [Thinking in React](https://react.dev/learn/thinking-in-react)
1. **Summarize the five steps of thinking in react.**
* Thinking in React means
* 1. breaking down UI into components,
  2. building a static version,
  3. identifying minimal UI state,
  4. deciding where state should live, and
  5. implementing data flow for user input.
* This helps organize React apps, manage state, and create interactive interfaces.

## [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)
1. **What is one reason a local variable isn’t sufficient for managing a React component?**
* One reason a local variable isn't sufficient for managing a React component is because local variables don't persist between renders, and changes to them won't trigger re-renders in React.
2. **What is the argument to the useState hook, and what are the two parts of its return array?**
* The argument to the useState hook is the initial value of the state variable. The useState hook returns an array with two parts: the current state value and the function to update that state value.
3. **How can Component A access state from Component B?**
* Component A can access state from Component B by passing down the state value and the setter function as props from Component B to Component A, allowing Component A to update the state in Component B.

## Bookmark and Review
### Keep these pages handy - they answer questions that show up regularly for this lab.
* [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
* [Rendering Lists](https://react.dev/learn/rendering-lists)
* [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)
* [useState hook](https://react.dev/reference/react/useState)

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-27/)?** 
* Upon reviewing the class README, my learning objectives include grasping the differences between functional and class components in React, mastering the useState() hook for state management in functional components, understanding the use of the effect hook for lifecycle events, and effectively utilizing the Hooks API to manage state and lifecycle events in functional components while adhering to conventions and best practices.
