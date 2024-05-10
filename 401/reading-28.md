#  [Reading: Component Lifecycle / useEffect Hook](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-06)

## [useEffect hook](https://react.dev/reference/react/useEffect#reference)
1. **What is the main intended use case for the useEffect hook?**
* useEffect in React is primarily used to handle side effects in functional components, such as data fetching, subscriptions, or manual DOM manipulation.
2. **How does the effect’s logic interact with the component?**
* The effect's logic executes after each component render, allowing it to interact with the component's state or props. Dependencies can be specified to control when the effect re-runs.
3. **What is the importance of the return value from the effect’s logic function?**
* The return value from the effect's logic is optional but crucial for cleanup tasks. It allows for unsubscribing from subscriptions, clearing timers, or any other necessary cleanup to prevent memory leaks and ensure application correctness.

## Bookmark and Review
### Keep these pages handy - they answer questions that show up regularly for this lab.
* [Responding to Events](https://react.dev/learn/responding-to-events)
* [Conditional Rendering](https://react.dev/learn/conditional-rendering)
* [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)
* [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

## Reflection
1. **What are your learning goals after reading and reviewing the class [README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-28/)?**
* The README introduces React's useEffect() hook for managing component lifecycle and side effects. It covers the hook's callback function and optional array of watchers, as well as emphasizing the importance of cleanup on component un-mount. Overall, it's a succinct guide for effectively utilizing useEffect() in React applications.

## Things I want to know






