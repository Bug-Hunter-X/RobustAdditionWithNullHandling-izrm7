# Unexpected Null Handling in Addition Function

This repository demonstrates a common error in JavaScript related to null handling in functions. The `foo` function is designed to add two numbers. However, it unexpectedly returns `null` if either input is `null`. This behavior might not be desired in all situations. A better approach would be to handle `null` values by treating them as 0, ensuring a numerical result in all cases.

## Bug

The `bug.js` file contains the function with the problematic null handling.  The output shows that even if one argument is a valid number and the other is null, the function returns null.

## Solution

The `bugSolution.js` file provides a corrected version of the function that handles null values by converting them to 0 before performing the addition. This guarantees a numerical result irrespective of the input values.
