# Class 04 React and Forms

## React Docs -  Forms

### What is a ‘Controlled Component’?
A controlled component is a form element that derives its value and behavior from the state of its parent component.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
If a form is simple with limited interactivitiy with large amounts of data then waiting is acceptable. However, for real time validation or interactivitiy then updating the state with the responses is neccessary.

### How do we target what the user is entering if we have an event handler on an input field?
The the input is accessed by using the event object that gets passed to the event handler. 

## The Conditional (Ternary) Operator Explained

### Why would we use a ternary operator?
The ternary operator simplies code to when a conditional statement is true or false.

### Rewrite the following statement using a ternary statement:
```
if(x===y){
  console.log(true);
```

```
console.log(x === y ? true : false);
```

## Things I want to know more about
I'd like to try to implement event handlers into input fields.