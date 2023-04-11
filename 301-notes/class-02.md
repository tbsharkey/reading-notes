# Class 02 State and Props

## React lifecycle

### Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
Render occurs prior to componentDidMount.

### What is the very first thing to happen in the lifecycle of React?
The first thing to happen is mounting. This is when a component is created and inserted into the DOM.

### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1. Constructor
2. Render
3. ComponentDidMount
4. React Updates
5. componentWillUnmount

### What does componentDidMount do?
It is a lifecycle method class based component. If anything is needed to be loaded using a network request or initializing the DOM it is put here. 

## React State Vs Props

### What types of things can you pass in the props?
Props can have serveral types of data passed into them to include Primitive data types, complex data types, functions, and React elements. 

### What is the big difference between props and state?
Props are read only and are not mutable. State is internal storage and is mutable. 

### When do we re-render our application?
A re-render will occur when there is a change in prop, states, a forced re-render, or a context change. 

### What are some examples of things that we could store in state?
User input from text inputs, checkboxes, radio buttons, or dropdowns can have their value stored in states, allowing a component to keep track of user input and respond to changes.

## Things I want to know more about
React blows my mind. I need to learn more basics. 