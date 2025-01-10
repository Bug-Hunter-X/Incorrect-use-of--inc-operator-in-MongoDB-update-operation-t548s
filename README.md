# Incorrect use of $inc operator in MongoDB update operation

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical value in a document. However, if you provide a string value to `$inc`, it will result in an error or unexpected behavior.  This example showcases the error and how to correct it.

## Bug
The file `bug.js` contains code that attempts to increment the `count` field by the string value "1". This will not work as expected and may result in an error or unexpected results. 

## Solution
The file `bugSolution.js` provides a corrected version of the code. The `$inc` operator now uses a number instead of a string to increment the `count` field properly.
