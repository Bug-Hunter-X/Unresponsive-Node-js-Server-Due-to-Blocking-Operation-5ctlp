# Unresponsive Node.js Server Due to Blocking Operation

This repository demonstrates a common issue in Node.js applications where a long-running synchronous operation in the request handler blocks the event loop, making the server unresponsive. The solution involves refactoring the code to use asynchronous operations.