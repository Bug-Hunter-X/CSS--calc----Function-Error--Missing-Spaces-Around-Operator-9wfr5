# CSS `calc()` Function Error: Missing Spaces Around Operator

This repository demonstrates a common, subtle error when using the `calc()` function in CSS.  The error involves forgetting to include spaces around the arithmetic operators (+, -, *, /) within the `calc()` expression. This can lead to unexpected behavior and is often difficult to debug.

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

## Reproducing the Bug
1. Open `bug.html` in a web browser.
2. Observe the width of the element; it will likely be incorrect due to the missing spaces in the `calc()` function.

## Solution
Ensure you always include spaces around the operators within the `calc()` function. This is a crucial part of the `calc()` syntax. 