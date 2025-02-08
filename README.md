# Unexpected Null Behavior in JavaScript Function

This repository demonstrates a common error in JavaScript where null values are not explicitly checked, leading to unexpected behavior.

The `bug.js` file contains the buggy code, which doesn't handle null values appropriately.  The `bugSolution.js` file demonstrates the corrected code.

## Bug Description

The `foo` function adds two numbers. However, if either input is null, it causes an error. The fix explicitly checks for null inputs and handles them.