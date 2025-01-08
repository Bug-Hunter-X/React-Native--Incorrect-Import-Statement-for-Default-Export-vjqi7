# React Native Incorrect Import
This repository demonstrates a common error in React Native: using a named import for a default exported component.

## Bug
The `bug.js` file shows the incorrect import statement. This will result in a runtime error because React Native will not be able to find the component.

## Solution
The `bugSolution.js` file corrects this error by using the correct import statement for a default export. 

## How to reproduce
1. Clone the repository.
2. Run `npm install`.
3. Run `npx react-native run-android` or `npx react-native run-ios`.
4. Observe the error in the `bug.js` file and the successful rendering in `bugSolution.js`