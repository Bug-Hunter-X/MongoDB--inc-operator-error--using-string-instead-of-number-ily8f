# MongoDB $inc Operator Error: Using String Instead of Number

This example demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is provided instead of a number, MongoDB will not be able to perform the increment operation, resulting in either an error or incorrect results. 

The `bug.js` file contains the incorrect code that uses a string with `$inc`, and `bugSolution.js` demonstrates the correct usage using a number instead.