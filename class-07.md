# HTML Tables #
<hr />
## How to create tables ##

### How to create tables? ###
- The `<table>` tag defines an HTML table.

- Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th> `tag. Each table data/cell is defined with a` <td> `tag.

- By default, the text in `<th>` elements are bold and centered.

- By default, the text in `<td>` elements are regular and left-aligned.

- You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.

- For long tables you can split the table into a <thead>,
<tbody>, and <tfoot>.

<ht />

# JS #

### Creating an object : constructor notation : ###

- Define the object type by writing a constructor function. There is a strong convention, with good reason, to use a capital initial letter.

- Create an instance of the object with new.

- To define an object type, create a function for the object type that specifies its name, properties, and methods

### adding or removing properties ###

- To add a new key-value pair to an object, the simplest and popular way is to use the dot notation or Alternatively, you could also use the square bracket notation to add a new item.

Example:
<code>

 foods = { burger: '🍔', pizza: '🍕' };

 foods.custard = '🍮';
 foods['cake'] = '🍰';
 </code>

- JavaScript provides the delete operator to remove a property from an object. On successful deletion, it will return true, otherwise false:
<code>
 delete foods.pizza;

 </code>
<hr />
- <h3>GLOBAL OBJECTS</h3>

The JavaScript Global Object has some properties and methods which are globally defined and are available to all Variables of a JavaScript Program.

When the Javascript interpreter begins to parse the webpage, it creates a new global object and then assigns it a set of properties which defines:

  - Global Properties of undefined, Infinity and NaN
  - Global Functions like NaN(), parseInt() and eval()
  - Constructor Functions like Date(), RegExp(), String(), Object() and Array()
  - Global Objects like Math and JSON

For Client Side JavaScript, the Window object serves as the global object for all JavaScript code contained within the browser window.

`This window` object is referenced using window property instead of this to refer the global object.

<hr />

- Please visit this sites to read more about objects 
    [W3Schools](https://www.w3schools.com/jsref/jsref_obj_global.asp)
    [tutorial park](http://www.tutorialspark.com/javascript/JavaScript_Global_Objects.php)















