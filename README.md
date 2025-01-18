# MongoDB $inc operator with NaN value
This repository demonstrates an uncommon error related to the MongoDB `$inc` operator when using a `NaN` value for incrementing a numeric field.  The issue arises from attempting to increment a field with a value that is not a number, leading to unexpected results or errors.

The `bug.js` file shows the erroneous code that uses `$inc` with `NaN`. The `bugSolution.js` provides the correct approach of handling this scenario.

This example highlights the importance of data validation before using MongoDB update operators to prevent unexpected behavior.