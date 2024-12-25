# Uncommon HTML Bug: Timing Issue

This repository demonstrates a subtle timing-related bug in HTML and JavaScript.  The JavaScript code attempts to manipulate the content of a div element before the browser has fully rendered the element, leading to unexpected behavior (the text isn't updated). This highlights the importance of ensuring elements exist before manipulating them.

## Bug

The `bug.html` file contains the faulty code.  The JavaScript attempts to change the text content of a div, but because the script runs before the DOM is fully ready, the change is not reflected.