# Lists #
 ### Ordered List  ###

 - ** Ordered lists ** are lists where each item in the list is
numbered.
- `<ol>` The ordered list is created with
the ` <ol>` element.
- `<li>` Each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag.* (The li
stands for list item.)*

### Unordered Lists ###

- Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).

- `<ul>`The unordered list is created
with the`<ul>` element.
- `<li>`Each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag.

<img src="list.png"/>


### Definition Lists ###

- Definition lists are made up of a set of terms along with the
definitions for each of those terms.

- ` <dl>` The definition list is created with
the ` <dl>` element and usually consists of a series of terms and
their definitions.
- Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements.
- `<dt>` This is used to contain the term being defined (the definition term).
- `<dd>` This is used to contain the definition.

<img src="dl.png"/>



 #### Nested Lists ####

 - You can put a second list inside an `<li>` element to create a sublist or nested list.


<img src="nlist.png"/>


# Boxes #

** You can set several properties that affect the appearance of
these boxes. In this chapter you will see how to Control : **  

1.  The dimensions of boxes : To set your own dimensions for a
box you can use the <code> height </code> and
<code>width </code> properties. The most popular ways to
specify the size of a box are to use pixels <code> px </code>  , percentages <code> % </code>, or
ems <code>em </code>.

- <code>  min-width </code>  property specifies the smallest size a box can be
displayed at when the browser window is narrow, and the
<code>max-width </code> property indicates the maximum width a box can
stretch to when the browser window is wide.

- to limit the width of a box on a page, you may also want
to limit the height of it. This is achieved using the<code> min-height</code> 
and <code>max-height</code> properties.

2. Create borders around boxes
- The CSS border properties allow you to specify the style, width, and color of an element's border.
- The <code> border-style </code> property specifies what kind of border to display.
- The <code> border-style </code> property can have from one to four values (for the top border, right border, bottom border, and the left border).
      The following values are allowed:
    ----------|------------------------ 
       dotted |- Defines a dotted border
       dashed |- Defines a dashed border
        solid |- Defines a solid border
        double|- Defines a double border
        groove| - Defines a 3D grooved border. The effect depends on the border-color value
        ridge |- Defines a 3D ridged border. The effect depends on the border-color value
        inset |- Defines a 3D inset border. The effect depends on the border-color value
        outset| - Defines a 3D outset border. The effect depends on the border-color value
        none  |- Defines no border
        hidden| - Defines a hidden border

- The <code>border-width </code> property specifies the width of the four borders.
- The <code> border-color </code> property is used to set the color of the four borders.
- The border property is a shorthand property for the following individual border properties:

   - <code>border-width</code>
   - <code>border-style</code> (required)
   - <code>border-color</code>


#### Set margins and padding for boxes ####

- The CSS <code>margin </code> properties are used to create space around elements, outside of any defined borders.
- The<code> margin </code> property is a shorthand property for the following individual margin properties:

       - <code>margin-top </code>
       - <code>margin-right</code>
       - <code>margin-bottom</code>
       - <code>margin-left</code>

- The CSS <code> padding </code> properties are used to generate space around an element's content, inside of any defined borders.

- The padding property is a shorthand property for the following individual padding properties:

     - <code>padding-top </code>
     - <code>padding-right</code>
     - <code>padding-bottom</code>
     - <code>padding-left</code>

[boxes](https://4.bp.blogspot.com/-p8vD7Kxpd0Q/Uy2j7mt1x9I/AAAAAAAAGhU/exqNzQJYkFU/s1600/difference-between-margin-padding-css-propriety-tutorial.png)

<br>
<hr  />

# JS ARRAYS #

- An Array is a special type of variable. It's store a list of values. 

- Using an array literal is the easiest way to create a JavaScript Array.
    Syntax:

     <code>var array_name = [item1, item2, ...];</code>

- To access an array element by referring to the index number. 
    <code>var name = cars[0]; </code>
      
- You can change the value of an item an array by selecting it and assigning it a new value just as 
you would any other variable (using the equals sign and the
new value for that item).


### USING SWITCH STATEMENTS ###
- about switch statment go to this resource [switch statment](https://www.w3schools.com/js/js_switch.asp)
     


