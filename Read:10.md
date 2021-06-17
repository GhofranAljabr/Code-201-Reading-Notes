# JS Debugging
--------------------------
## Code Debugging
Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

-------------------------
### Code Debugging
Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

---------------------------
The console.log() Method
If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:

* Example
````````````````````````````
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>

<script>
a = 5;
b = 6;
c = a + b;
console.log(c);
</script>

</body>
</html>
``````````````````````````````````````

**The debugger Keyword**
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

With the debugger turned on, this code will stop executing before it executes the third line.

+ Example
`````````````````````
var x = 15 * 5;
debugger;
document.getElementById("demo").innerHTML = x;
```````````````````````

**Major Browsers' Debugging Tools**
Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.

Otherwise follow these steps:

***Chrome***
- Open the browser.
- From the menu, select "More tools".
* From tools, choose "Developer tools".
+ Finally, select Console.
***Firefox***
* Open the browser.
+ From the menu, select "Web Developer".
+ Finally, select "Web Console".
***Edge***
+ Open the browser.
+ From the menu, select "Developer Tools".
+ Finally, select "Console".
***Opera***
+ Open the browser.
+ From the menu, select "Developer".
- From "Developer", select "Developer tools".
+ Finally, select "Console".
***Safari***
+ Go to Safari, Preferences, Advanced in the main menu.
+ Check "Enable Show Develop menu in menu bar".
+ When the new option "Develop" appears in the menu:
+ Choose "Show Error Console".