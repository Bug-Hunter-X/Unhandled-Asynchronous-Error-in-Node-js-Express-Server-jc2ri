## Unhandled Asynchronous Error in Node.js Express Server

This repository demonstrates a common error in Node.js applications: unhandled errors within asynchronous operations. The `bug.js` file shows an Express.js server with an asynchronous route handler that randomly throws an error.  This can lead to the server crashing unexpectedly.

The `bugSolution.js` file provides a corrected version with proper error handling using try...catch blocks within the asynchronous operation and a centralized error handler for the Express app.