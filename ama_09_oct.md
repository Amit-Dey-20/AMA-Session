 # AMA Questions and Answers

## What is Promise.all() ?
### Answer:
Promise.all() is a JavaScript method that runs multiple asynchronous operations concurrently and waits until all of them succeed. It returns the results in an array. If even one Promise fails, the entire Promise.all() rejects.

## What is related_name in Django ?
### Answer:
related_name is an argument used in Django model relationships to specify the name of the reverse relationship.

## What is C in ACID ?
### Answer:
Consistency ensures that a database moves from one valid state to another valid state after a transaction. All database rules and constraints must remain satisfied.

## What was the first JavaScript engine ?
### Answer:
SpiderMonkey

## What is an atomic transaction, and what is a transaction ?
### Answer:
- A transaction is a group of database operations treated as one logical unit of work.
- An atomic transaction follows the principle of all or nothing. Either all operations in the transaction succeed, or none of them are applied.


## What is isolation in ACID ?
### Answer:
Isolation in ACID ensures that multiple transactions executing at the same time do not interfere with each other improperly. Each transaction behaves as though it is executing independently of other concurrent transactions.


## What is the difference between CSRF, XSS, and clickjacking ?
### Answer:
- CSRF (Cross-Site Request Forgery) :- CSRF tricks an authenticated user's browser into performing an unwanted action on a website.
- XSS (Cross-Site Scripting) :- XSS occurs when an attacker injects malicious JavaScript into a webpage that other users visit.
- Clickjacking :- Clickjacking tricks a user into clicking an element different from the one they believe they are clicking, often by placing a transparent or disguised webpage over another interface.


## How does Django communicate with a database ?
### Answer:
Django communicates with a database through its ORM. The ORM converts Python model operations into SQL queries, which are executed by the configured database using a database backend and driver. The results are then returned to the application as Python objects or QuerySets.


## Which middleware is used to protect against clickjacking ?
### Answer:
Django uses XFrameOptionsMiddleware to protect against clickjacking by setting the X-Frame-Options HTTP header.


## At which protocol layer does HTTP work ?
### Answer:
HTTP is an application-layer protocol used for communication between clients and web servers.