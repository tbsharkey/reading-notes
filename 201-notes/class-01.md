# Class 01 Reading Notes

## Getting Started

### A poem describing how HTTP sends data between computers
In packets, bits of data flow,
From one computer to and fro,
HTTP, a protocol grand,
Helps send info across the land.

Port 80, its gateway true,
Helps the data flow anew,
Requests and responses it must send,
Until the journey finds its end.

### How HTML, CSS, and JS files are “parsed” in the browser
When parsing, the browser does so in order of HTML, followed by CSS, and then JavaScript.
 When the browser loads an HTML file, it starts by parsing the document to create a tree-like structure called the Document Object Model (DOM). The DOM represents the elements and content of the HTML file as a set of objects that can be manipulated by JavaScript. The browser reads the HTML code from top to bottom, and constructs the DOM tree accordingly.

Once the browser has created the DOM tree, it begins parsing the CSS file. The browser reads the CSS code and applies the styles to the appropriate elements in the DOM tree. The resulting visual style of the page is determined by the rules specified in the CSS file.

After the CSS file has been parsed, the browser moves on to the JavaScript file. The browser reads the JavaScript code and executes it. JavaScript can manipulate the DOM tree and dynamically change the content and style of the page based on user input or other events.

### Where images can be found to add to a website
Images can be found on a range of websites or produced by an individual utilizing different mediums. The <img> element is what contains an image in the HTML file and the src attribute provides the location. Images can be stored locally with an absolute or relative file path or provided by an url from an external source. Care must be given to images that are licensed or copyrighted. 

### How strings and numbers are created in JavaScript
String and numbers are stored in a data type known as a variable. The following methods allow variable assignment:
var - Assigns the value to a variable allowing it to be changed later. This method has been deprecated.
let - Assigns the value to a variable allowing it to be changed later.
const - Assigns the value to a variable not allowing it be to changed later.
Numbers can be whole integers or floating point. A string is a collection of characters within parenthesis. Therefore, 5 would be considered a number but "5" would be a string. 

### What is a variable and why it's important
A variable is a container that holds a value or data. They allow data to be stored and manipulated being used to write more complex programs. Code becomes modular and reusable with variables. Data can be stored, retrieved, and changed depending on the need of the program. Variables are one of the fundamental blocks of programming languages. 

## Introduction to HTML

### What is an HTML attribute?
Attributes are additional information of an element that don't appear in the content. This could be linking an external file, assigning a class or id, or allowing a new tab to be opened when clicked.

### Describe the Anatomy of an HTMl element.
HTML elements typically have opening and closing tags with content between them. 
<p>I like pizza!</p>

### What is the Difference between <article> and <section> element tags?
The two are only semantically separate and only matter with layout. An article attribute usually enclosed a block of content that's related and easily stands out on it's own. An example would be a blog post. A section encompasses a smaller part than an article and would contain a single piece of a functionality like a mini-map.

### What Elements does a “typical” website include?
A typical website will include most of the semantic elements such as header, main, footer, article, and section.

### How does metadata influence Search Engine Optimization?
Metadata affects SEO though:
Title Tags- The title tag is what is displayed on the search engine results as a clickable title.
Meta Descriptions- The meta description provides a brief summary of the content on a webpage. It's displayed under the title tag in the results. 
Heading Tags- Heading tags provide information on the sturcture and hierachy of a webpage's content. They help search engines understand the context and organization of the content
Image Alt Tages- Alt tags provide an image's description. They are used by search engines to index images and can improve a search ranking. 

### How is the <meta> HTML tag used when specifying metadata?
The meta tag provides metadata which provides additional information on a webpages content. This can be done through a description or through providing keywords. 

## Miscellaneous 

### Why should you use an <h1> element over a <span> element to display a top level heading?
Semantically an h1 element denotes a top level heading whereas a span would not. This allows for consistency across websites. Furthermore screen readers and other assistive technologies rely on semantics to accurately convey information.  

### What are the benefits of using semantic tags in our HTML?
Semantic tags make code considerably easier to read and understand for programmers.

### Describe 2 things that require JavaScript in the browser? 
Form validation, which validates input on a webpage requires JavaScript as does dynamic content which can include animations or interactive maps.

### How can you add JavaScript to an HTML document?
JavaScript can be added to an HTML document either through an external link or by placing the code between <script></script>.

## Things I want to know more about

I would like to know more about SEO.
