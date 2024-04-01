# [Readings: Functional Programming](https://github.com/codefellows/seattle-code-301d108/tree/main/class-09)


## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
1. **What is functional programming?** Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state and mutable data. It emphasizes the use of functions that take inputs and produce outputs without modifying external state or relying on external data.
2. **What is a pure function and how do we know if something is a pure function?** A pure function is a function that, given the same input, will always return the same output and has no side effects. Side effects include modifying external state, performing I/O operations, or relying on mutable data. We can determine if a function is pure by examining whether it meets these criteria: it always returns the same output for the same input, and it does not cause any observable side effects.
3. **What are the benefits of a pure function?** There are several benefits to using pure functions:
* **Predictability:** Pure functions are deterministic, meaning they always produce the same output for the same input, which makes the behavior of the program more predictable.
* **Testability:** Since pure functions do not rely on external state, they are easier to test because you can isolate them and test them independently without worrying about external dependencies.
* **Concurrency:** Pure functions are inherently thread-safe and can be easily parallelized, which can improve performance in concurrent or distributed systems.
4. **What is immutability?**  Immutability is a concept where once an object is created, its state cannot be changed. In functional programming, data is immutable, meaning it cannot be modified after it is created. Instead of modifying existing data structures, immutable data structures are created through operations that return new data structures with the desired changes.
5. **What is Referential transparency?** Referential transparency is a property of expressions in a program where a function call can be replaced by its return value without changing the behavior of the program. In other words, if an expression can be replaced with its value without affecting the program's output, then that expression is referentially transparent. This property allows for easier reasoning about code and enables optimization techniques such as memoization.



## [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)
1. **What is a module?**In the context of Node.js, a module is a reusable piece of code that encapsulates related functionality. Modules help organize code into logical units, making it easier to manage, maintain, and reuse. Each module typically contains its own variables, functions, classes, or other components, which can be imported and used in other parts of the application.
2. **What does the word ‘require’ do?** The require function in Node.js is used to import modules into a file. When you require a module, Node.js searches for the module in the node_modules folder or the core Node.js modules. Once found, it loads the module and makes its functionality available for use within the file.
3. **How do we bring another module into the file the we are working in?** To bring another module into the file you are working in, you use the require function followed by the path to the module you want to import. 
4. **What do we have to do to make a module available?** To make a module available for use in Node.js, you need to export its functionality. You can do this by assigning the functionality you want to export to the module.exports object or by using the exports shorthand. 




## Things I want to know more about

  


