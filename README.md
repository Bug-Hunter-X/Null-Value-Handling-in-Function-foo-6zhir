# Null Value Handling in Function foo

This repository demonstrates a common JavaScript bug related to unexpected behavior when null values are passed to a function. The `foo` function does not handle null values gracefully, potentially leading to errors or unexpected results.

The `bug.js` file contains the buggy implementation, while `bugSolution.js` provides a corrected version with proper null value handling.

## Bug Description

The `foo` function is expected to perform some operations on the input values `a` and `b`. However, it does not explicitly handle the case where either `a` or `b` is `null`. This can lead to unexpected behavior or runtime errors depending on the operations performed within the function.

## Solution

The solution in `bugSolution.js` adds explicit checks for null values at the beginning of the function. If either `a` or `b` is `null`, the function returns immediately, preventing further processing and potential errors.