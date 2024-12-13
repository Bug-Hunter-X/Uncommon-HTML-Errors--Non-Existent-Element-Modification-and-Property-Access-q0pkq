# Uncommon HTML Errors

This repository demonstrates two unusual errors that can occur in HTML, particularly when working with JavaScript and the Document Object Model (DOM):

1. **Attempting to modify a non-existent element using innerHTML:** The code attempts to change the innerHTML of an element that does not exist in the DOM. This results in a silent failure; no error is thrown, but the intended change does not happen.
2. **Accessing a non-existent property of a DOM element:**  The code tries to access a property of a DOM element that does not exist. This throws an error and can halt the script execution.

The `bug.html` file contains the buggy code.  The `bugSolution.html` file shows how to handle these situations gracefully, preventing unexpected behavior or crashes.