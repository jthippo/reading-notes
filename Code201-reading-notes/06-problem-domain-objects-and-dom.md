# problem-domain-objects-and-dom

#### How would you describe an object to a non-technical friend you grew up with?

Object is a data type in JS. They are contained for properties, which are named values. The properties are organised via keys.

#### What are some advantages to creating object literals?

- Convenience
- Flexibility in declaration
- Less code during declaration
- You can drop an object literal anywhere in your program with no previous setup and it'll work

#### How do objects differ from arrays?

- Arrays are better for numbers; objects for strings.
- Data in arrays are "elements"; data in objects are "properties" made up of a key and a value.
- Array elements are manipulated with []bracket notation; objects elements are manipulated with []bracket notation and .dot notation.

#### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

When an object property name is held in a variable. You can't use dot notation to access the value, but can with bracket notation.

#### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

_const dog = {_  
_name: 'Spot',_  
_age: 2,_  
_color: 'white with black spots',_  
_humanAge: function ()_{  
*console.log(`${this.name} is ${this.age*7} in human years`);\  
_}_  
_}_

THIS = the current object. So this.name is the dog object, keeps things simple.

#### What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

#### Briefly describe the relationship between the DOM and JavaScript.

All parts of a web document can be accessed and manipulated using the DOM and a scripting language like JavaScript. The DOM is not part of the JavaScript language but is instead a Web API used to build websites.
