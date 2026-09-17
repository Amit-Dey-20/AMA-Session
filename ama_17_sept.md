# AMA Questions and Answers

## Which CLI command is used to move a file?
### Answer:

mv [source file] [destination]


## What is Promise.any()?
### Answer:

Promise.any() is a JavaScript Promise method that waits for multiple promises and returns the result of the first promise that succeeds.

If all promises reject, Promise.any() returns an AggregateError.


## What is function hoisting?
### Answer:

In javascript we can call a function before its declaration in the code because in javascript memory is allocated before executing the code.

function declaration are fully hoisted but function expression are not.


## What is lexical scope?
### Answer:
Lexical scope means a function can access variables based on where the function is defined in the code.


## What is the difference between undefined and undeclared variables?
### Answer:

**undefined:-** Variable is declared but has no assigned value.

**Undeclared:-** Variable is not declared and not exist, it is type of ReferenceError.


## What are higher-order functions?
### Answer:

A function that takes one or more function as an arguments or returns a function is called higher order function.


## What is the difference between sequential promises and parallel promises?
### Answer:

**Sequential:**
- Promises are handled one after another. That mean next promise depends on previous promise are called Sequential Promise.
- It can take more time to handled.

**Parallel Promises:**
- Multiple promises are started at the same time and all the promises handled independently is called Parallel Promises.
- It is fast to handle promises.


## What is the callback queue?
### Answer:

The callback queue is a queue where callback functions waiting to be executed are placed after an asynchronous operation has completed.

It is also commonly called the task queue or macrotask queue.


## What is the new keyword?
### Answer:

The new is a keyword is used to call the constructors to create new Object.


## What is the difference between Promise.race() and Promise.any()?
### Answer:

**Promise.race():**
- Promise.race() return first setteled promise either it can be success or fail.

**Promise.any():**
- Promise.any() return first success promise it ignore the failure promises.
- If all the promises get rejected it will returns an AggregateError.


## What is the difference between find() and findIndex()?
### Answer:

- find() returns the first element that satisfies the condition.
- findIndex() returns the index of the first element that satisfies the condition.


## What is the microtask queue?
### Answer:

The microtask queue is a waiting queue for high-priority asynchronous callbacks, such as Promise callbacks, which are processed after the current code finishes and before regular callback queue tasks.


## What are the disadvantages of callbacks?
### Answer

The main disadvvantages of callbacks are:
- Callback Hell :- Due to nested callbacks code will increase horizontally instead of vertically it will decrease readability.
- Inversion of Control:- Executions of callbacks depends on another callbacks.