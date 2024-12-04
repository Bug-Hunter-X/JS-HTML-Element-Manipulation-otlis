# Incorrect getElementById Usage in JavaScript
This repository demonstrates a common error when using `getElementById` in JavaScript to modify HTML elements.  The incorrect code attempts to include the '#' symbol which is not required.
The solution demonstrates the correct approach.

## Bug
The `bug.html` file contains a script that attempts to modify the innerHTML of a div element using an incorrect method that includes '#' in getElementById. This results in the script failing to modify the element.

## Solution
The `bugSolution.html` file shows the corrected version of the script, removing the '#' symbol for the correct usage of `getElementById`.
