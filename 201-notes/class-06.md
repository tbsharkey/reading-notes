# Class 06

## JavaScript Object Basics

### How would you describe an object to a non-technical friend you grew up with?
An object is a piece of data that bundles other data related to one function. It allows one to more efficiently write code as the particular data or functions are needed, they can easily be found and used. 

### What are some advantages to creating object literals?
Object literals allow data items to be quickly transferred and eliminate the need for sending items individually or through an array, which would be more time consuming to work with. 

### How do objects differ from arrays?
Objects can hold data in key-value pairs and each string acts as a unique identifier.  Objects are also unordered. Arrays are better suited for structured data of related values. 

### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
Bracket notation is needed when a property contains special characters or spaces such as trailing white space in a string. 

### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```

The keyword "this" refers to the current object that is being accessed. IT allows an object to be referenced without explicitly referencing the object's name. 

## Introduction To The DOM

### What is the DOM?
The Document Object Model(DOM) is a programming interface for web documents. It represents a web page in a tree-like structure where the nodes represented elements, attributes, or text. 

### Briefly describe the relationship between the DOM and JavaScript.
JavaScript uses the DOM to manipulate, style, and structure a web page. When a user performs actions such as clicking on a button, JavaScript can add, delete, or modify HTML and CSS elements. 

## Things I want to know more about

I've worked with classes in Ruby so I am looking forward to learning how to manipulate them in JavaScript. 

