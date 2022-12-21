# development-blog
A blog on what I have learnt from week 1 onwards!

# Week 2
- Sematic HTML, which makes the sections of the website more accessible to users who rely on assistive 
technologies to use the web.

- Common Element: (header, article, nav, section, table, details, figure, form, aside, main, mark)

- Inspector mode: enables users to make and view temporary changes on the spot.

- Device Mode: The device mode allows you to toggle devices for preview and testing.

CSS:
- selector { property: value;}

- <p style="text-align: 
left;">Just a sentence</p>

-<link rel="stylesheet"
href="basic.css" type="text/css">

- @import: 
● Set of style rules defined in 
an external file
● Should appear as a first rule 
in an external stylesheet
● Used to chain multiple 
external files together

- HASH symbol for ID name. Unique to that element.

- PERIOD symbol for class name. Selects any element.

- In CSS, an ID is #
// change the color of the element with id "main"
#main {
color: black
}
// change the color of the element with class special
.special {
color: black
}
You can specify a HTML tag and a class to be more specific
// for all <p> with the class special
p.special {
}
You can target a children element that is in a parent 
element
// all <a> inside the ID "main" html element
#main a {
}
  
- Link:
a:link { /* unvisited link */ color: red; }
a:visited { /* visited link */ color: blue; }
a:hover { /* moused over link */ color: green; }
a:active { /* current link */ color: purple; }
a:focus { /* focused link */ color: purple; }
  
- background-color: changes background color
  
 - Typography
  
 - web gradient
  
 - Box model
  
 
# Week 3
- <form>
  
- <input>

- Labels

- Validation
  
- Nested Elements & the DOM
  
- Descendant Selector

- Grouping Selectors

- Inheritance
  
- Specify
  
-  !Important
  
- Media Query:
  
 * Min-width
If the minimum width of the viewport is at least 
the specific width or wider, then the media 
query is true
  
 * Max-width
If the maximum width of the viewport is at no 
more than the specified width, or it’s narrower 
then the media query is true
  
Positioning
Relative
For tweaking the position of an element without affecting its 
surrounding boxes
Absolute
Take elements out of the static flow of the page and place 
relative to the browser window
Relative Absolute 
Allows us hook back into the static flow of the page
Fixed
Make elements don't scroll with the rest of the page (sticky)

* z-index property lets you control the 
depth of elements on the page.
Imagine the screen as a 3D world
Negative z-index go farther into the 
page. (behind)
Positive z-index comes out of the page

*Flexbox
Can adapt layout to suit content

*Wireframe
Like a blueprint for a site or app's 
layout
Shows important functionality
Conveys content types and grouping
Shows information hierarch
  
# Week 4
- Responsive Images
● Auto-resize based on screen size
● Better Performance
○ Load higher resolution images only when needed
● Provide better design control depending on device

- Github
  
# Week 5
- javascript essential training
* javascript basics
* Objects
* Sidebar: string output
* DOM
* Access LinkedIn Learning
  
# Week 6
- console.log
  
- DATA TYPES
Strings, Values, Booleans
  
- Numbers: Floating point numbers, decimals & Integers
- Strings: Sequence of characters, text
- Booleans: Logical Data (True or False)
- 2 OTHER PRIMITIVE DATA TYPES
* Undefined: Data type of a variable that does not have a value yet
* Null: Also means non-existent

- Dynamic Typing

- String Processing

- Template Literals
  
- COMPARISON & LOGICAL OPERATORS
  
- === (strict equal to)

- !==(strict not equal to)
- == (equal to)
  
- != (not equal to)
  
-LOGICAL OPERATORS
  
- LOOPS

- ARRAY Indexing
  
- ARRAY
  
- Functions
  
- Literal Object
  
- Accessing an object

- Updating an object
  
- Constructor notation

- Function based objects
  
- Multiple object instances

-VAR, LET, CONST
  
- For... of loop

- DOM
* getElementById();
Uses the value of an element's id attribute
querySelector();
Uses a CSS selector, and returns the first
matching element. Classes or Ids can be
used
Traversal methods
  
* getElementsByClassName();
Selects all elements that have a specific
value for their class attribute
getElementsByTagName();
Selects all elements that have the specified
tag name
querySelectorAll()
Uses a CSS selector to select all matching
elements
  
*parentNode
Selects the parent of the current node
previousSibling/nextSibling
Selects the previous or next sibling from the
DOM tree
firstChild/lastChild
  
* When a script selects an element to modify, the
interpreter finds the element(s) in the DOM
tree
The following query searches the DOM tree for
an element whose id attribute has a value of
one
Once the node is found, you can work with that
node, its parent or children

- <element>.innerHTML;
  
- <element>.textContent;
  
- <element>.className;
  
# Week 7
- element.addEventListener('event', functionName, [Boolean]);
  
-el.addEventListener('blur', function(){
checkUsername(5);
}, false);
  
-preventDefault()
  
- stopPropagation()
  
- Validating Forms

- Clearing Storage
  localStorage.clear();
  localStorage.removeItem(<item key>);
  
- JSON
  
-Clearing Storage with API
localStorage.clear();
localStorage.removeItem(<item key>);
  
# Week 8
- jQuery Selectors
- jQuery Events
.show() Displays selected elements
.hide() Hides selected elements
.toggle() Toggles between showing and hiding selected elements
.fadeIn() Fades in selected elements making them opaque
.fadeOut() Fades out selected elements making them transparent
.fadeTo() Changes opacity of selected element
.fadeToggle() Hides or shows selected elements by changing their opacity (opposite of current state)
.slideUp() Hides selected elements with a sliding motion
.slideDown() Shows selected elements with a sliding motion
.slideToggle() Hides or show selected elements with a sliding motion (opposite direction of current state)
.delay() Delays execution of subsequent items in queue
.stop() Stops an animation if it is currently running
.animate() Creates custom animation
  
- Get, Set
  
- Append, After

- AJAX
  
- Fetch
  
- jQuery AJAX
  
# Week 9
- Bootstrap
- Bootstrap Utilities
- Bootstrap Components
