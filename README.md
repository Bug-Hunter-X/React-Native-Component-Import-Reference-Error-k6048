# React Native Component Import/Reference Error

This repository demonstrates a common but often overlooked error in React Native development: incorrect component imports or references.

## Problem
The `BuggyComponent.js` file shows an example of a common error: a component is used before being properly imported, or the import path is incorrect, leading to a runtime error. The component might be misspelled, or the file might be in an unexpected location.

## Solution
The `FixedComponent.js` file presents the correct solution.  It shows how to accurately import the component and use it in your code. Ensure the import path is correct and the component's name matches exactly.

## How to reproduce the bug:
1. Clone the repository.
2. Run `npm install` or `yarn install`.
3. Run the app in your preferred React Native environment.
4. Observe the error displayed.