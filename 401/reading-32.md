#  [Reading: Context API- Behavior](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-32)
## [Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)
1. **How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)**
* In React applications, useReducer and useContext simplify state management by centralizing state logic and sharing state across components. useReducer manages complex state transitions through a reducer function, which updates state based on actions, making state logic predictable and testable. useContext creates a global state accessible to any component within the context provider, eliminating the need for prop drilling. When combined, a context provider uses useReducer to manage state and wraps the component tree, allowing nested components to access and update state seamlessly. This approach decouples state logic from UI components, enhancing code organization, scalability, and maintainability.






