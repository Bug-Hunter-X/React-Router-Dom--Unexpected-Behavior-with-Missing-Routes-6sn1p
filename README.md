# React Router Dom: Handling Missing Routes

This repository demonstrates a common issue in React Router Dom v6 and above: how to gracefully handle navigation attempts to routes that haven't been defined.

The `bug.js` file shows the problem - an application that lacks a route for `/contact`. Navigating to this URL will result in an error or unexpected behavior.

The `bugSolution.js` file demonstrates the solution, using a `Route` with a `path='*'` to create a catch-all for undefined routes.