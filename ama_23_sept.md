# AMA Questions and Answers

## What is the lspci command?
### Answer:

lspci is a Linux command used to display information about PCI devices connected to the computer, such as Wi-Fi cards, graphics cards, and network cards etc..


## What is Promise.race()?
### Answer:

Promise.race() is a JavaScript Promise method that returns the result of the first Promise that settles either it resolved or reject.


## What is the difference between querySelector() and querySelectorAll()?
### Answer:

**querySelector():-**
- Selects the first matching element
- Returns a single element
- If no match return null

**querySelectorAll():-**
- Selects all matching elements
- Returns a NodeList
- If no match return empty NodeList


## What is a closure?
### Answer:

A closure is a function that remembers the variables from its outer scope even after the outer function has finished execution.


## What is the difference between element.className and element.classList.add()?
### Answer:

- Both are used to add or change CSS classes of an HTML element.
- The main difference is that className replaces all classes and classList.add() adds a class while keeping existing classes.


## What is encapsulation?
### Answer:

Encapsulation means wrapping all the data and methods in a single unit and controlling how the data can be accessed or changed.


## What is the difference between PUT and POST?
### Answer:

**POST:**
- Usually used to create a new resource.
- Server usually decides the new resource ID.
- Repeating the same request may create multiple resources.
- Not necessarily idempotent.

**POST:**
- Usually used to create or replace/update a resource.
- Client commonly specifies the resource URL/ID.
- Repeating the same request normally produces the same final state
- Idempotent.


## What is the difference between innerText and innerHTML?
### Answer:

**innerText:**
- innerText property returns only the rendered text content as it appears visually on the screen.

**innerHTML**
- innerHTML property returns the text along with all the child html tags exactly they are written in the source code.


## What are promises?
### Answer:

A promise is an object it represents eventually completion or failure of an asynchronous operations.


## What is a memoization function in JavaScript?
### Answer:

Memoization is a technique where we store the result of a function so that when the same input comes again, we can use the stored result instead of calculating it again.


## How do you change text using JavaScript?
### Answer:

We can change innerText and textContent.


## What is preventDefault()?
### Answer:

preventDefault() is a JavaScript method used to stop the browser's default action for an event.


## What is web storage?
### Answer:

Web Storage is used to store data in the browser using localStorage and sessionStorage.
