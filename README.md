# Express.js Route Handler Missing Error Handling

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.

The `bug.js` file shows a route handler that is vulnerable to errors if the `userId` parameter is not a valid number or if no user with that ID exists.

The `bugSolution.js` file provides a corrected version with robust error handling, returning appropriate HTTP status codes and messages.