# HTML Lists, Control Flow with JS, and the CSS Box Model


##  Learn HTML

### When should you use an unordered list in your HTML document?
Unordered lists should be when the order of items doesn't matter. 

### How do you change the bullet style of unordered list items?
The bullet style can be changed by either using the type attribute or by using list-style in CSS.

### When should you use an ordered list vs an unorder list in your HTML document?
If list items need to be numerically arranged then an ordered list should be list. All other cases should be fine to use the bullet points provided by the unordered list. 

### Describe two ways you can change the numbers on list items provided by an ordered list?
The numbers on an ordered list can be modified by the type attribute or the list-style property in a stylesheet. 

## Learn CSS

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Margin and padding are two key characters in the story of "The Box Model". Margin is the space between the box and other elements on the page, like the buffer zone between people at a party. Padding, on the other hand, is the space between the content of the box and its border, like the distance between a book's text and its cover.

Together, margin and padding help define the size and spacing of boxes on a web page, and they play an important role in the overall layout of the page. Think of margin and padding as the unsung heroes of the web design world, working quietly behind the scenes to make sure everything looks just right.

### List and describe the four parts of an HTML elements box as referred to by the box model.
The four parts of the box elements are:
Content- The actual content of the element such as text or images.
Padding- The space between the content and the border of the element. 
Border- The border is a line or outline around the element.
Margin- The margin is the space outside the element's border.

## Learn JS

### What data types can you store inside of an Array?
An array can hold all data types to include numbers, strings, Booleans, objects, arrays, functions, null, and undefined. 

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 ```
The people array is a valid array. It contains three inner arrays. To access the values you would use the index notation like console.log(people[0][0])

 ### List five shorthand operators for assignment in JavaScript and describe what they do.
+= adds the value on the right side to the existing value of the variable.
-= subtracts the value on the right side from the existing value of the variable on the left side.
*= multiplies the value on the right side with the existing value of the variable on the left side assigns it to the left side.
/= divides the existing value of the variable on the left side by the value on the right side and assigns it to the left side.
%= takes the modulus of the existing value of the variable on the left side with the value on the right side and then assigns it to the left side. 
 ### Read the code below and evaluate the last expression and explain what the result would be and why.

 ```
  let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ```
The result is 10dog. The first part adds 10 to false which is still 10. Then the second adds an integer to a string resulting in 10dog.

 ### Describe a real world example of when a conditional statement should be used in a JavaScript program.
An example of a conditional statement would be in a online shopping cart. The statement could evaluate whether a price total exceeds a threshold thus allowing the customer to have free shipping.

 ### Give an example of when a Loop is useful in JavaScript.
 A loop could be used to iterate over an array adding the values up to a sum variable. By using a for loop the code would run until the entire array had been iterated over. 

