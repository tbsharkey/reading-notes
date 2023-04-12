# Class 03 Passing Functions as Props

## React Docs - lists and keys

### What does .map() return?
It returns a new array populated with the results of calling a provided function on every element in the calling array.

### If I want to loop through an array and display each value in JSX, how do I do that in React?
Using the Array.prototype.map() method to loop through an array and display each value within JSX. 


### Each list item needs a unique ____.
Each list item needs a unique key.

### What is the purpose of a key?
The key helps React identify which items have changed, are added, or removed, and it optimizes the rendering and updating process for the list items. 

## The Spread Operator

### What is the spread operator?
The Spread operator is represented by three dots. It allows the ability to expand iterable elements, such as arrays, objects, and strings, into iterable elements or properties. 

### List 4 things that the spread operator can do.
The spread operator can copy arrays, merging arrays, copying objects, and merging objects. 

### Give an example of using the spread operator to combine two arrays.
```
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const mergedArray = [...array1, ...array2];
console.log(mergedArray);
```

### Give an example of using the spread operator to add a new item to an array.
```
const originalArray = ['Apple', 'Banana', 'Orange'];
const newItem = 'Grape';

const newArray = [...originalArray, newItem];

console.log(newArray);
```

### Give an example of using the spread operator to combine two objects into one.
const user = { name: 'John Doe', age: 30 };
const address = { city: 'New York', country: 'USA' };

const userWithAddress = { ...user, ...address };

console.log(userWithAddress);

## How to Pass Functions Between Components

### In the video, what is the first step that the developer does to pass functions between components?
He created an increment fuction.

### In your own words, what does the increment function do?
It loops through the object and adds one to the count if the name is detected. 

### How can you pass a method from a parent component into a child component?
Define the method in the parent component and pass the method to the child component.

### How does the child component invoke a method that was passed to it from a parent component?
The child component accesses the method via the props object and invokes it when neccessary. 

## Things I want to know more about
I'd like to see more examples of parent methods being invoked. 