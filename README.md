# JavaScript Null Value Handling Bug

This repository demonstrates a common issue in JavaScript programming: improper handling of null values.  The `foo` function in `bug.js` showcases how null values can unexpectedly cause issues.  The solution, `bugSolution.js`, addresses this.  This is a simple example highlighting a critical aspect of robust JavaScript development.

## Bug Description
The original code incorrectly handles null values.  This example shows how easily unhandled nulls can lead to unexpected behaviour or runtime errors.  The fix involves explicitly checking for null values and providing suitable alternative behaviour.

## Solution
The solution in `bugSolution.js` adds explicit null checks before performing the addition operation. This ensures the function handles nulls gracefully and prevents potential errors.