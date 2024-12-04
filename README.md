# Express.js Error Handling for Non-Existent Static Files

This repository demonstrates a common error in Express.js applications when serving static files: attempting to serve a file that does not exist.  The example showcases the error and provides a solution for robust error handling.

## Bug

The `bug.js` file contains an Express.js app that attempts to serve `index.html`.  If `index.html` is not present in the same directory, the app will throw an error.

## Solution

The `bugSolution.js` file demonstrates a solution using Express's built-in `static` middleware and enhanced error handling to gracefully manage situations where requested files are not found.