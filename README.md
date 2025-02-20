# Uncommon HTML Bug: Accessing a Non-Existent Element

This repository demonstrates a subtle bug that can occur in HTML when using JavaScript to interact with the DOM. The issue arises when attempting to access an element that does not exist in the HTML structure.  The code tries to modify the `innerHTML` property of an element with the ID 'nonExistentElement', which does not exist, leading to a runtime error.

## Bug Description

The bug is caused by incorrect element selection. The script attempts to access an element with the id 'nonExistentElement', but no element with that id is present in the HTML.

## Solution

The solution involves carefully checking for the existence of the element before attempting to access its properties.  This prevents the runtime error and handles cases where the element may not be present.

## How to Reproduce the Bug

1. Clone the repository.
2. Open `bug.html` in your web browser.
3. You will see a console error in the browser's developer tools.

## How to Test the Solution

1. Open `bugSolution.html` in your web browser.
2. Observe that there are no errors in the console, and the script executes without issue.