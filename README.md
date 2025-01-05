# MongoDB $inc operator with String Value
This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numeric field. Providing a string value leads to unexpected results or errors. This repository provides a demonstration of the problem and its solution.

## Bug
The `bug.js` file shows the incorrect usage, attempting to increment a counter field with a string value. This results in either a failed update or unintended modification of the field.

## Solution
The `bugSolution.js` file shows the corrected usage using a numeric value with the `$inc` operator.  This ensures the field is correctly incremented.
