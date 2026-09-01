# AMA Questions and Answers

## What are the different ways to write CSS?
### Answer:
There are three ways to write a css.
- Inline css
- Internal css
- External css
#### Inline CSS
Inline css are written directly inside the HTML element using the style attribute.
#### Internal CSS
Internal css is written inside a style tag in the head section.
#### External CSS
External css is written in a seperate .css file to use this file in our html we have to link that file by using link tag in the head section. 


## What are the properties of Flexbox?
### Answer
Flex properties are divided into two types
- Container properties
- Items properties
#### Container Properties
- display-flex
- flex-direction
- flex-wrap
- flex-flow
- justify-content
- align-items
- align-contents
- row-gap
- column-gap
- gap 

#### Items Properties
- order
- flex-grow
- flex-shrink
- flex-basis
- flex
- align-self
## How do you define a protected variable in Python?
### Answer
In python a protected variable is defined by using single underscore "_"
Example:
```
_user = 'Amit'
```

## What are the !important keywords in CSS?
### Answer
!important is used for give css declaration higher priority than all the other css declarations. So, if we use !important in any declaration the specificity is highest.

## What is the difference between height and min-height?
### Answer
- height -> It is used to set fixed height of the element.
- min-height -> It is used to set minimum height of the element. So, element become taller when required.

## What is CSS Grid?
### Answer
CSS Grid is used to create a layout in which elements are arranged in rows and columns.

CSS grid is used to create a 2-D layout.

## What are pseudo-classes in CSS, and how are they used?
### Answer
- Pseudo-class is a keyword which are used with any css selectors to style the elements based on it state or condition.
- By using pseudo-class we can change the style of the entire elemnt.
- It start with a single colon :

Syntax:

```
selector : pseudo-class{
    <!-- Style -->
}
```

## What is the difference between CSS Grid and Flexbox?
### Answer
#### CSS Grid
- Css grid is used to create a 2-D layout.
- Css grid elements are arranged rows and columns.
- Grid is suitable for creating card layout, dashboard etc.

#### Flexbox
- Flexbox is used to create a 1-D layout.
- In flexbox elements are arranged in either row or column.
- flexbox is suitable for creating navbar etc.

## What is flex-wrap in CSS?
### Answer
flex-warp property is used to adjust the flex items in proper position inside flex container when there is not enough space in the flex- container.
## What is the difference between HTML and HTML5?
### Answer
#### HTML
- Older version.
- Used older document type declarations
- Limited multimedia support.
- Fewer semantic elements.

#### HTML5
- Morden version of HTML.
- Uses simple document type.
- Built in audio and video tags are available.
- Have more semantic tags like header, section, nav etc.

## What is atomicity in SQL?
### Answer
Atomicity ensures that a transaction is completed or not in between the transaction if any operation failed the entire transaction get rollback from starting.
## What is the CSS box model?
### Answer
In CSS every elements of html is treated as a rectangular box.

This rectangular box consists of four parts
- content
- padding
- border
- margin
## What are selectors in CSS?
### Answer
A css selector is used to target the html elements so that css style can be applied to them.

Examples
- Element Selector
- Class Selector
- Id Selector
- Universal Selector