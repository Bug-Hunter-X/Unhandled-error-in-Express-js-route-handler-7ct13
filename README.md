# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers:  lack of proper error handling. The `bug.js` file shows a route that attempts to find a user by ID. However, it fails to handle cases where the ID is invalid or the user is not found.

The `bugSolution.js` file provides a corrected version that includes comprehensive error handling to prevent unexpected crashes and return appropriate HTTP status codes.