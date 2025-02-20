# Unhandled Exception in Node.js HTTP Server

This repository demonstrates a common error in Node.js: unhandled exceptions within HTTP request handlers.  The `bug.js` file shows a server that crashes when the `/error` route is requested due to a thrown error that isn't caught. The `bugSolution.js` file provides a solution implementing proper error handling.