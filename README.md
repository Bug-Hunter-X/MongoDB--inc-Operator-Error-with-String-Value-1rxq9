# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The error occurs when attempting to increment a numeric field with a string value.

## Bug
The `bug.js` file contains code that attempts to increment the `age` field of a document with the string value '1'. This results in an error because the `$inc` operator requires a numeric value.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator. It increments the `age` field with the numeric value 1, resolving the error.

## Usage
1. Make sure you have MongoDB and Node.js installed.
2. Clone the repository.
3. Run the `bug.js` file to see the error.
4. Run the `bugSolution.js` file to see the correct implementation.
