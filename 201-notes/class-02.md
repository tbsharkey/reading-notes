# Class 02 Reading Notes

## HTML Text Fundamentals. HTML Advanced Text Formatting

### Why is it important to use semantic elements in our HTML?
It's important to use sematic elements in HTML to organize content and improve readability. 

### How many levels of headings are there in HTML?
There are six levels of headings in HTML, H1-H6.

### What are some uses for the <sup> and <sub> elements?
Sup is used for superscripts which are often used in mathematical expressions or for trademarks and copyright symbols. Subscripts play the string below the text and are useful for instances of chemical expressions. Subscripts can also be used for mathematical expressions.

### When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
The title attribute but be used to full spell out what an abbreviation stands for.
<abbr title="World Health Organization">WHO</abbr>

## Learn CSS

### What are ways we can apply CSS to our HTML?
Styles can be applied through:
Inline CSS- A style attribute is added within an element.
Internal CSS- A style section is added to the head of the document containing all relevant CSS.
External stylesheet- An external stylesheet containing all CSS is linked through the head.

### Why should we avoid using inline styles?
Inline styles must be duplicated often and decrease the readability of the code. 

## Review the block of code below and answer the following questions:

### What is representing the selector?
The H2 element represents the selector.

### Which components are the CSS declarations?
The portions color: black; and padding: 5px; are both declarations. 

### Which components are considered properties?
Color and padding are both properties.

```
   h2 {
     color: black;
     padding: 5px;
   }
   ```
## Learn JS

### What data type is a sequence of text enclosed in single quote marks?
Strings are enclosed within quote marks.

### List 4 types of JavaScript operators.
Four types of operators are arithmetic, comparison, logical, and assignment.

### Describe a real world Problem you could solve with a Function.
A simple function could convert Fahrenheit to Celsius.
```
function fahrenheitToCelsius(fahrenheit) {
  let celsius = (fahrenheit - 32) * 5/9;
  return celsius;
}
```

## Making Decisions In Your Code – Conditionals.

### An if statement checks a __ and if it evaluates to ___, then the code block will execute.
An if statement checks a condition and will evaluate it to true or false before proceeding.

### What is the use of an else if?
 An else if statement allows multiple conditions to be checked.

### List 3 different types of comparison operators.

Equal comparison operator- ==
Strict equal comparison operator- ===
Not equal comparison operator- !=

### What is the difference between the logical operator && and ||?
The && id checking to see if both conditions evaluate to true whereas || only requires one side to evaluate to true.

## Things I want to know more about

I'd like to write cleaner versions of if statements. 

