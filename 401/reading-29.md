#  [Reading: Advanced State with Reducers](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-29)

## [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)
1. **What is the motivation for adding a reducer?**
* Reducers streamline state management by consolidating updates into a single function, enhancing code organization and scalability.
2. **What are actions in the context of a reducer? How are they different than setting state directly?**
* Actions are objects describing state changes, dispatched to reducers for interpretation and state adjustment. They offer a structured approach, improving code clarity and maintainability.
3. **What common list operation is useReduce named for, and why?**
*  `useReduce` mirrors the `reduce` operation, iteratively processing actions to compute the next state. It underscores the functional programming aspect of reducers.
4. **When should you switch from useState to useReducer?**
*  Transition to `useReducer` when state logic becomes complex or component hierarchy becomes unwieldy. It offers structured state management, particularly beneficial for intricate state transitions and complex updates.

## Bookmark and Review
### Keep these pages handy - they answer questions that show up regularly for this lab.
* [useReducer hook](https://react.dev/reference/react/useReducer)
* [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
* [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-29/)?**
* The README discusses using reducers for advanced state management in React. It covers actions, dispatching, and immutable updates with useReducer(). Understanding these concepts is essential for efficient state management, improving React component scalability and maintainability.

## Things I want to know


