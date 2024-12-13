# Uncommon HTML Error: Accessing Non-Existent Element

This repository demonstrates a common yet easily overlooked error in HTML/JavaScript: attempting to access a DOM element that doesn't exist.

## The Bug
The `bug.html` file contains a simple HTML structure with two paragraphs and a JavaScript script.  The script attempts to access an element with the ID 'nonExistent' using `document.getElementById()`. Since no element with that ID exists, this results in a `TypeError`.

## The Solution
The `solution.html` file demonstrates a solution to this issue.  Before attempting to access the element, we check to ensure it exists using a conditional statement. If the element does not exist, the code handles the case gracefully, preventing the error.

## How to Run
1. Clone this repository.
2. Open `bug.html` and `solution.html` in your web browser. 
3. Open your browser's developer console (usually by pressing F12) to see the error message in `bug.html` and the corrected behavior in `solution.html`.