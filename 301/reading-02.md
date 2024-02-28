# [Readings: State and Props](https://github.com/codefellows/seattle-code-301d108/tree/main/class-02)

## [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
1. **Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?** In the React component lifecycle, the constructor happens first, followed by the render method, and then componentDidMount.
2. **What is the very first thing to happen in the lifecycle of React?** The very first thing to happen in the lifecycle of React is the initialization of the component, which includes calling the constructor method.
   
4. **Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
What does componentDidMount do?** The order of lifecycle methods is as follows:
* constructor
* render
* componentDidMount
* React Updates (this includes various updates triggered by state changes or prop changes)
* componentWillUnmount
componentDidMount is a lifecycle method in React that gets called after the component has been rendered to the DOM. It's commonly used for actions that require DOM nodes to be fully constructed, such as fetching data from an external API or initializing third-party libraries.


## [Video vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
1. **What types of things can you pass in the props?** In React, you can pass various types of data in props, including:
* ***Primitives:*** Strings, numbers, booleans
* ***Objects:*** JavaScript objects, arrays
* ***Functions:*** JavaScript functions
* ***React elements:*** Components, JSX elements
* ***Callbacks:*** Functions passed as props to child components
  
2. **What is the big difference between props and state?** Props (short for properties) are immutable and passed from parent components to child components. On the other hand, state is mutable and managed within the component itself.

3. **When do we re-render our application?**
* When there are changes in component state.
* When there are changes in component props.
* When there are changes in the context (with Context API).
* When force re-rendering explicitly using forceUpdate().

4. **What are some examples of things that we could store in state?**
* User input data (e.g., form inputs)
* UI state (e.g., visibility of a modal, collapsed/expanded panels)
* Data fetched from APIs
* Error messages or flags
* Current page or tab index in a multi-step process


## Things I want to know more about


