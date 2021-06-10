## HTML Images; CSS Color & Text

--------------
**HTML Images**
HTML Images Syntax
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
````
<img src="url" alt="alternatetext">

````
The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

Example
`````````
<img src="img_chania.jpg" alt="Flowers in Chania">
```````

The alt Attribute
The required alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:


Example
````
<img src="img_chania.jpg" alt="Flowers in Chania">
`````
## CSS Color & Text
---------------------------------------------------
Text Color
The color property is used to set the color of the text. The color is specified by:



The default text color for a page is defined in the body selector.

**Example**
````````
body {
  color: blue;
}

h1 {
  color: green;
}
`````````
Note: For W3C compliant CSS: If you define the color property, you must also define the background-color.

Text Color and Background Color
In this example, we define both the background-color property and the color property:

**example**
`````````
body {
  background-color: lightgrey;
  color: blue;
}
````````
`````
h1 {
  background-color: black;
  color: white;
}
```