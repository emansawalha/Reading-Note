## WHAT IS AN OBJECT? ##

- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

- #### VARIABLES BECOME KNOWN AS PROPERTIES ####
    - If a variable is part of an object, it is called a
property. Properties te ll us about the object.


- #### FUNCTIONS BECOME KNOWN AS METHODS ####
    - If a function is part of an object, it is called a method.
Methods represent tasks that are associated withthe object.


- You define (and create) a JavaScript object with an object literal:
`var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};`

## Document Object Model ##

- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

- The HTML DOM model is constructed as a tree of Objects:

[The HTML DOM Tree of Objects](https://www.w3schools.com/js/pic_htmltree.gif)

- With the object model, JavaScript gets all the power it needs to create dynamic HTML:

       - JavaScript can change all the HTML elements in the page
       - JavaScript can change all the HTML attributes in the page
       - JavaScript can change all the CSS styles in the page
       - JavaScript can remove existing HTML elements and attributes
       - JavaScript can add new HTML elements and attributes
       - JavaScript can react to all existing HTML events in the page
       - JavaScript can create new HTML events in the page

- The browser represents the page using a DOM tree.

- DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.

- You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.

- Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

- From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.

- An element node can contain multiple text nodes and
child elements that are siblings of each other.

- In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

- Browsers offer tools for viewing the DOM tree .

- to be more profisional in DOM [see this](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

