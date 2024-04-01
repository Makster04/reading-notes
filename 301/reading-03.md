# [Readings: Passing Functions as Props](https://github.com/codefellows/seattle-code-301d108/tree/main/class-03)

## [React Docs - lists and keys){:target=”_blank”}](
1. **What does .map() return?** The .map() function in React returns a new array with transformed elements based on the provided function.
2. **If I want to loop through an array and display each value in JSX, how do I do that in React?** To loop through an array and display each value in JSX in React, you can use the .map() function inside curly braces {} within your JSX code.
3. **Each list item needs a unique ____.** Each list item needs a unique ***"key" attribute.***
4. **What is the purpose of a key?** The purpose of a key in React is to help React identify which items have changed, been added, or been removed from a list, allowing it to efficiently update the UI. Keys should be unique identifiers for each element in the list.

## [The Spread Operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)
1. **What is the spread operator?** The spread operator (...) is a syntactic feature in JavaScript used for expanding elements, such as arrays or objects, into places where multiple elements or key-value pairs are expected.

2. **List 4 things that the spread operator can do.**
* - Expand arrays into individual elements.
* - Copy arrays and objects.
* - Merge arrays and objects.
* - Pass elements of an iterable (like an array) as arguments to a function or constructor.
  
3. **Give an example of using the spread operator to combine two arrays.**
* const array1 = [1, 2, 3];
* const array2 = [4, 5, 6];
* const combinedArray = [...array1, ...array2];
* console.log(combinedArray); // Output: [1, 2, 3, 4, 5, 6]
  
4. **Give an example of using the spread operator to add a new item to an array.**
* const originalArray = [1, 2, 3];
* const newArray = [...originalArray, 4];
* console.log(newArray); // Output: [1, 2, 3, 4]

5. **Give an example of using the spread operator to combine two objects into one.**
* const obj1 = { a: 1, b: 2 };
* const obj2 = { c: 3, d: 4 };
* const combinedObject = { ...obj1, ...obj2 };
* console.log(combinedObject); // Output: { a: 1, b: 2, c: 3, d: 4 }

## [How to Pass Functions Between Components](https://www.youtube.com/watch?v=n-6i_WGIOKE)
1. **In the video, what is the first step that the developer does to pass functions between components?** In the video, the first step the developer does to pass functions between components is defining a function in the parent component that they want to pass to a child component.

2. **In your own words, what does the handleClick function do?** The handleClick function, in essence, is a function defined in the parent component that gets called when a button is clicked. This function typically performs some action, such as updating state or triggering some behavior in the parent component.

3. **How can you pass a method from a parent component into a child component?** You can pass a method from a parent component into a child component by including it as a prop when rendering the child component.

4. **How does the child component invoke a method that was passed to it from a parent component?** The child component can invoke a method that was passed to it from a parent component by accessing it through props and then calling it when needed.

## Things I want to know more about,




   
