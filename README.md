# Express.js Route Parameter Error Handling

This repository demonstrates a common error in Express.js route handlers:  lack of error handling for invalid or missing route parameters.

The `bug.js` file shows an example of a route handler that fails to handle cases where the `userId` parameter is not a valid number or does not correspond to an existing user.  This can cause unexpected application behavior or crashes.

The `bugSolution.js` file presents a corrected version with proper error handling to gracefully handle such scenarios, returning appropriate HTTP status codes and messages.