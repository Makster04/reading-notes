#  [Reading: Context API](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-31)

## [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure))
1. **Summarize the five principles for structuring state.**
* A. ***Single source of truth:*** Keeping all state in a single place to maintain consistency and avoid conflicts.
* B. ***State is read-only:*** Making state immutable to prevent accidental changes and simplify tracking of updates.
* C. ***Changes are made with pure functions:*** Using pure functions to modify state ensures predictability and facilitates testing.
* D. ***State changes are batched:*** Grouping state changes together improves performance and reduces unnecessary re-renders.
* E. ***Immutable updates:*** Creating new copies of state objects instead of mutating them directly ensures data integrity and facilitates debugging.

## [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)
1. **What problem do Contexts aim to solve?**
* Contexts aim to solve the problem of prop drilling, where props need to be passed through multiple layers of components.
2. **What is one technique to try before useContext?**
* One technique to try before useContext is prop drilling, where state is passed down through component props.
3. **What hook complements useContext for complex applications?**
* The useReducer hook complements useContext for complex applications by providing a more structured way to manage state updates, especially when state logic becomes intricate and requires more than just simple value changes.

## Bookmark and Review
* [Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)
* [Preserving and Restting State](https://react.dev/learn/preserving-and-resetting-state)

## Things I want to know

