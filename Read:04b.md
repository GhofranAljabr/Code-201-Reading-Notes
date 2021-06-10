#  HTML Links, CSS Layout, JS Functions
------------
***HTML Links***

### Links are found in nearly all web pages. Links allow users to click their way from page to page.

## HTML Links - Hyperlinks
HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!
```````
HTML Links - Syntax
The HTML <a> tag defines a hyperlink. It has the following syntax:

<a href="url">link text</a>
The most important attribute of the <a> element is the href attribute, which indicates the link's destination.
`````
- The link text is the part that will be visible to the reader.

Clicking on the link text, will send the reader to the specified URL address.

*Example*
This example shows how to create a link to W3Schools.com:
````````````````
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
By default, links will appear as follows in all browsers:

An unvisited link is underlined and blue
A visited link is underlined and purple
An active link is underlined and red
Tip: Links can of course be styled with CSS, to get another look!

HTML Links - The target Attribute
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:

_self - Default. Opens the document in the same window/tab as it was clicked
_blank - Opens the document in a new window or tab
_parent - Opens the document in the parent frame
_top - Opens the document in the full body of the window
Example
Use target="_blank" to open the linked document in a new browser window or tab:

<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
Absolute URLs vs. Relative URLs
Both examples above are using an absolute URL (a full web address) in the href attribute.

A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):

Example
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
ADVERTISEMENT	
HTML Links - Use an Image as a Link
To use an image as a link, just put the <img> tag inside the <a> tag:

Example
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
````````````````````
Link to an Email Address
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

Example
`````````````````
<a href="mailto:someone@example.com">Send email</a>
Button as a Link
To use an HTML button as a link, you have to add some JavaScript code.
````````````
JavaScript allows you to specify what happens at certain events, such as a click of a button:

Example
````````````
<button onclick="document.location='default.asp'">HTML Tutorial</button>
Tip: Learn more about JavaScript in our JavaScript Tutorial.
`````````````
Link Titles
The title attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.

Example
````````````````
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
More on Absolute URLs and Relative URLs
Example
Use a full URL to link to a web page: 

<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>
```````````````````
Example
Link to a page located in the html folder on the current web site: 
````````````
<a href="/html/default.asp">HTML tutorial</a>
`````````````
Example
Link to a page located in the same folder as the current page: 
````````````
<a href="default.asp">HTML tutorial</a>
``````````````
You can read more about file paths in the chapter HTML File Paths.

* Chapter Summary
Use the <a> element to define a link
Use the href attribute to define the link address
Use the target attribute to define where to open the linked document
Use the <img> element (inside <a>) to use an image as a link
Use the mailto: scheme inside the href attribute to create a link that opens the user's email program
HTML Link Tags
Tag	Description
<a>	Defines a hyperlink
For a complete list of all available HTML tags, visit our HTML Tag Reference.

### CSS Layout
--------
Website Layout
A website is often divided into headers, menus, content and a footer:


There are tons of different layout designs to choose from. However, the structure above, is one of the most common, and we will take a closer look at it in this tutorial.

Header
A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name:

*Example
`````````````
.header {
  background-color: #F1F1F1;
  text-align: center;
  padding: 20px;
}
````````````````
Result

**Header**
------------------------

## JavaScript Functions
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Example
````````````````
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}
```````````````
## JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
`````````````````````
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
``````````````````
*Function parameters are listed inside the parentheses () in the function definition.

*Function arguments are the values received by the function when it is invoked.

*Inside the function, the arguments (the parameters) behave as local variables.

*A Function is much the same as a Procedure or a Subroutine, in other programming languages.

*Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)
You will learn a lot more about function invocation later in this tutorial.