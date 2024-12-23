# React Router v6 Nested Routes Rendering Issue

This repository demonstrates a problem with nested routes in React Router v6.  Sometimes, nested routes fail to render their child components, even though the parent route renders correctly.  The issue appears to be intermittent and not easily reproducible. 

The `App.js` file contains the buggy code, while `AppSolution.js` provides a solution (using `useLocation` to force a rerender).  See the solution for how to fix this behavior.

## Setup

1. Clone the repo.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.