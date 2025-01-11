# Node.js Server Hangs with Long-Running Task

This repository demonstrates a common issue in Node.js where a long-running task in the request handler blocks the event loop, causing the server to hang and become unresponsive. The `server.js` file shows the problematic code, while `serverSolution.js` provides a solution using asynchronous operations.