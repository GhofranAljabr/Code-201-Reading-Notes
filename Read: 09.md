# Forms and JavaScript Forms
----------------
## JavaScript Form Validation
HTML form validation can be done by JavaScript.

If a form field (fname) is empty, this function alerts a message, and returns false, to prevent the form from being submitted:

JavaScript Example
```````````
function validateForm() {
  var x = document.forms["myForm"]["fname"].value;
  if (x == "") {
    alert("Name must be filled out");
    return false;
  }
}
````````````


The function can be called when the form is submitted:

HTML Form Example
```````````

<form name="myForm" action="/action_page.php" onsubmit="return validateForm()" method="post">
Name: <input type="text" name="fname">
<input type="submit" value="Submit">
</form>
JavaScript Can Validate Numeric Input
JavaScript is often used to validate numeric input:

Please input a number between 1 and 10

 Submit
`````````````````

## JavaScript Events
HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

HTML Events
An HTML event can be something the browser does, or something a user does.

Here are some examples of HTML events:

* An HTML web page has finished loading
- An HTML input field was changed
+ An HTML button was clicked
Often, when events happen, you may want to do something.

### JavaScript lets you execute code when events are detected.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.
```````````
With single quotes:

<element event='some JavaScript'>
With double quotes:

<element event="some JavaScript">
In the following example, an onclick attribute (with code), is added to a <button> element:
``````````
Example
````````````````
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
In the example above, the JavaScript code changes the content of the element with id="demo".

In the next example, the code changes the content of its own element (using this.innerHTML):
````````````
Example
`````````````
<button onclick="this.innerHTML = Date()">The time is?</button>
JavaScript code is often several lines long. It is more common to see event attributes calling functions:
````````````````
Example
```````````
<button onclick="displayDate()">The time is?</button>
``````````````````
------------------

## What can JavaScript Do?
Event handlers can be used to handle and verify user input, user actions, and browser actions:

Things that should be done every time a page loads
Things that should be done when the page is closed
Action that should be performed when a user clicks a button
Content that should be verified when a user inputs data
And more ...
Many different methods can be used to let JavaScript work with events:

HTML event attributes can execute JavaScript code directly
HTML event attributes can call JavaScript functions
You can assign your own event handler functions to HTML elements
You can prevent events from being sent or being handled
And more ...