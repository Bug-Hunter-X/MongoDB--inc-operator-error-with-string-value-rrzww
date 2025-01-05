# MongoDB $inc operator error with string value

This example demonstrates an incorrect usage of the `$inc` operator in MongoDB.  The `$inc` operator is used to increment a numeric field by a specified value. Using a string value will result in an error.

## Bug
The `bug.js` file contains code that attempts to increment a field using a string value which will fail.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator by using a numeric value for the increment.