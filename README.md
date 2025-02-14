# React Native useRef Hook Error: Cannot access a disposed object

This repository demonstrates a common error encountered when using the `useRef` hook in React Native: attempting to access or modify a component's state or properties after it has been unmounted.  This often occurs when asynchronous operations, such as network requests or timers, outlive the component's lifecycle.

The `Bug.js` file showcases the problematic code, while `BugSolution.js` provides a corrected version implementing appropriate cleanup and handling of asynchronous operations.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npx react-native run-android` or `npx react-native run-ios`.
4. Observe the console logs and notice the error in `Bug.js`.
5. Switch to `BugSolution.js` for a corrected implementation.