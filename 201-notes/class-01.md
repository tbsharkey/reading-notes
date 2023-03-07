# Class 01 Reading Notes

## Getting Started

### A poem describing how HTTP sends data between computers
In packets, bits of data flow,
From one computer to and fro,
HTTP, a protocol grand,
Helps send info across the land.

Port 80, its gateway true,
Helps the data flow anew,
Requests and responses it sends,
Until the journey finds its ends.

### How HTML, CSS, and JS files are “parsed” in the browser
When parsing, the browser does so in order of HTML, followed by CSS, and then JavasScript.
 When the browser loads an HTML file, it starts by parsing the document to create a tree-like structure called the Document Object Model (DOM). The DOM represents the elements and content of the HTML file as a set of objects that can be manipulated by JavaScript. The browser reads the HTML code from top to bottom, and constructs the DOM tree accordingly.

Once the browser has created the DOM tree, it begins parsing the CSS file. The browser reads the CSS code and applies the styles to the appropriate elements in the DOM tree. The resulting visual style of the page is determined by the rules specified in the CSS file.

After the CSS file has been parsed, the browser moves on to the JavaScript file. The browser reads the JavaScript code and executes it. JavaScript can manipulate the DOM tree and dynamically change the content and style of the page based on user input or other events.

### Where images can be found to add to a website
Images can be found on a range of websites or produced by an indivdual utliziling different mediums. The <img> element is what contains an image in the HTML file and the src attribute provides the location. Images can be stored locally with an absolute or relative file path, or provided by a url from an external source. Care must be given to images that are licensed or copyrighted. 

### How strings and numbers are created in JavaScript
String and numbers are stored in a data type known as a variable. The following methods allow variable assignment:
var - Assigns the value to a variable allowing it to be changed later. This method has been deprecated.
let -  Assigns the value to a variable allowing it to be changed later.
const - Assigns the value to a varaible not allowing it be to changed later.
Numbers can be whole integers or floating point. A string is a collection of characters within parenthesis. Therefore, 5 would be considered a number but "5" would be a string. 

### What is a variable and why it's important
A variable is a container that holds a value or data. They allow data to be stored and manipulated being used to write more complex programs. Code becomes modular and reusable with variables. Daata can be stored, retrieved, and changed depending on the need of the program. Variables are one of the fundamental blocks of programming languages. 

## Introduction to HTML

### What is an HTML attribute?

### Describe the Anatomy of an HTMl element.

### What is the Difference between <article> and <section> element tags?

### What Elements does a “typical” website include?

### How does metadata influence Search Engine Optimization?

### How is the <meta> HTML tag used when specifying metadata?

## Miscellaneous 

### Why should you use an <h1> element over a <span> element to display a top level heading?

### What are the benefits of using semantic tags in our HTML?

### Describe 2 things that require JavaScript in the Browser?

### How can you add JavaScript to an HTML document?
JavaScript can be added to an HTML document either through an external link or by placing the code between <script></script>.