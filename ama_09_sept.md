# AMA Questions and Answers

## What is the free command in CLI?
## Answer:
The free command in Linux CLI is used to check the system RAM usage like total RAM, used and available.

## What is the meaning of transform in CSS?
## Answer:
transform is used to change the position, size, shape, rotation of an element without changing the normal layout of the page.

## What is a dictionary in Python?
## Answer:
- A dictionary is a data structure used to stores data in key-value pairs.
- It is written using curly brackets {}.
- Each key has a corresponding value.
- Keys must be unique.
- Values can be duplicate.
- Dictionaries are mutable.

## What are indexes in SQL?
## Answer:
An SQL index is a data structure that helps the database find data faster it work like an index in a book.

## List some array methods in Python.
## Answer:
- append()
- insert() 
- remove()
- pop() 
- clear()
- sort()
- reverse()
- index()
- count()
- extend()

## Why do we use the get() method with dictionaries?
## Answer:
by using get() if we try to find value of any key, if key is not present it will give default value instead of throwing error.

## What does grid-template-columns: repeat(3, 1fr) mean in CSS?
## Answer:
It will create 3 columns with equal spaces.

## What is a namespace in python?
## Answer:
- A namespace is a place where Python stores names and their corresponding objects.
- It helps Python know which variable, function, class a name refers to.
- Its help to reduce conflict.

## What is LIMIT in SQL?
## Answer:
LIMIT is used to retrive the exact number of rows from the query.

## What is TCL in SQL?
## Answer:
- TCL stands for Transaction Control Language.
- It is used to manage transactions in a database.
- It has three command COMMIT, ROLLBACK, SAVEPOINT.

## Explain media types in CSS.
## Answer:

- Media types tell CSS what type of device or medium the styles are used.
- They are mainly used with @media rules.
- Common media types are:
    - screen
    - print
    - speech

## What is the enumerate() function in Python?
## Answer:
enumerate() is a built-in Python function. It is used to get both the index and value while looping through an iterable objects.

## Give one example of the Open/Closed Principle in SOLID.
## Answer:
Open/Closed Principle in SOLID is open for extension and closed for modification.

Example:-

```python
class Shape:
    def area(self):
        pass


class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius ** 2


class Rectangle(Shape):
    def __init__(self, length, breadth):
        self.length = length
        self.breadth = breadth

    def area(self):
        return self.length * self.breadth

```
We can add other shape without modifying the existing classes.