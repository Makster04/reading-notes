# [Readings: React and Forms](https://github.com/codefellows/seattle-code-301d108/tree/main/class-04)

## [How to use Forms in React](https://www.robinwieruch.de/react-form/)
1. **What is a ‘Controlled Component’?** A "Controlled Component" in React is a form element, like an input or textarea, whose value is controlled by React state. This means that the value displayed in the form element is derived from the component's state, and any changes to the value are managed by React through state updates.
2. **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.** It's generally better to update the state with the user's responses as soon as they enter them rather than waiting until they submit the form. This approach provides immediate feedback to the user and allows for real-time validation and interaction with the form. Delaying state updates until form submission might lead to a less responsive and interactive user experience.
3. **How do we target what the user is entering if we have an event handler on an input field?** To target what the user is entering if there's an event handler on an input field, you can access the value entered by the user through the event object passed to the event handler function. In React, you typically use event.target.value to access the current value of the input field.

## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff?gi=025249561b32)
1. **Why would we use a ternary operator?**
2. **Rewrite the following statement using a ternary statement:**
* ***Original***
* if(x===y){
* console.log(true);
* } else {
* console.log(false);
* }
* ***Rewritten***
* x === y ? console.log(true) : console.log(false);


## Things I want to know more about




   

