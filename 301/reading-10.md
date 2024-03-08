
# [Readings: Functional Programming](https://github.com/codefellows/seattle-code-301d108/tree/main/class-09)


## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
1. **What is a ‘call’?** In the context of the JavaScript call stack, a "call" refers to the invocation of a function. When a function is called, its execution context, including local variables and parameters, is pushed onto the call stack.

2. **How many ‘calls’ can happen at once?** In JavaScript, only one call can happen at a time due to its single-threaded nature. The call stack processes function calls one at a time in a synchronous manner, executing each function in the order it was called.

3. **What does LIFO mean?** LIFO stands for Last-In, First-Out. In the context of the call stack, it means that the most recently added function call is the first to be executed. When a function is called, its execution context is pushed onto the stack, and when the function finishes executing, its context is popped off the stack.
   
4. **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.** Suppose we have three functions: main, foo, and bar. Here's how the call stack would look like when main calls foo, and foo calls bar.
5. **What causes a Stack Overflow?** A stack overflow occurs when the call stack reaches its maximum capacity due to excessive function call nesting, causing it to run out of memory. This usually happens when there is a recursive function that doesn't have a proper base case or when there is an infinite loop. When a stack overflow occurs, it results in a runtime error, and the program terminates abruptly.



## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
1. **What is a ‘reference error’?** A reference error occurs when you try to access a variable or function that does not exist. This can happen if you mistype a variable name, attempt to use a variable that is not declared, or try to access a property of an undefined object.
2. **What is a ‘syntax error’?** A syntax error occurs when the JavaScript engine encounters code that violates the syntax rules of the language. This can happen if you forget to close a parenthesis, use an invalid keyword, or have a typo in your code that makes it impossible for the engine to parse and understand.
3. **What is a ‘range error’?** A range error occurs when you try to manipulate a value that is outside the acceptable range of values. For example, attempting to create an array with a negative length or calling a function with more arguments than it expects can result in a range error.  A type error occurs when you try to perform an operation on a value that is not of the expected type. This can happen if you attempt to call a method on an undefined or null value, or if you try to access a property of a value that is not an object.
4. **What is a ‘type error’?** A type error occurs when you try to perform an operation on a value that is not of the expected type. This can happen if you attempt to call a method on an undefined or null value, or if you try to access a property of a value that is not an object.
5. **What is a breakpoint?** A breakpoint is a point in your code where execution will pause when reached, allowing you to inspect the state of your program at that point. Breakpoints are commonly used during debugging to identify and diagnose issues in the code.
6. **What does the word ‘debugger’ do in your code?**he debugger keyword is used in JavaScript to pause execution of code and launch the debugger. When the JavaScript engine encounters the debugger statement while executing code, it will pause execution and allow you to inspect variables, step through code, and analyze the program's state using a debugging tool such as the browser's developer tools or a Node.js debugger.


## Things I want to know more about

  


