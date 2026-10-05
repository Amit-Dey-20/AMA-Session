# AMA Questions and Answers

## What is Promise.all()?
### Answer:
Promise.all() waits for all promises to successfully complete and gives all their results in an array if any promise get reject it will return error.

## How do you handle static files in Django?
### Answer:
- Static files are files like CSS, JavaScript, images, and fonts used by your website.
- Make a static folder in Django app and configure setting.py with `STATIC_URL = "static/"` and at the top of the template user `{% load static %}`
- Link your static files with `<link>` tag.

## What happens when authorization is rejected?
### Answer:
Authorization checks whether a user has permission to access a resource or perform an action.

If authorization is rejected, the server denies access to that resource.

## What does a 500 status code represent?
### Answer:
500 status code represents server side error.

## What is the difference between annotation and aggregation in Django?
### Answer:
- annotate() adds a calculated value to each object or row in the QuerySet.
- aggregate() calculates a value for the whole QuerySet and returns a dictionary.

## How do you inherit a template in Django?
### Answer:
{% extends "our html file" %}

## What is Q in Django?
### Answer:
Q is used in Django ORM to create complex database queries, especially when you need OR, AND, or NOT conditions.

## What is AJAX?
### Answer:
AJAX stands for Asynchronous JavaScript and XML.

It is a technique that allows a web page to send or receive data from the server without refreshing the entire page.

## How do comments work in Django?
### Answer:
In Django template files, comments are used to write notes that Django will not display in the browser.

{# comment #}

## What is the path() function in Django?
### Answer:
path() is used in Django's URL configuration to connect a URL to a view function.