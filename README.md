# Incorrect DOM Manipulation in HTML

This repository demonstrates a common mistake in accessing and manipulating HTML elements using JavaScript. The issue arises from an incorrect method of selecting the div element.

## Bug
The `bug.html` file contains a div element with the id "myDiv".  The JavaScript code attempts to directly access the div element using `document.div`, which is incorrect. The proper method is to use `document.getElementById("myDiv")`.

## Solution
The `bugSolution.html` file demonstrates the correct approach using `document.getElementById()` to select the div element before modifying its content.
