# Unhandled JS Exception: Cannot read properties of undefined (reading 'name')

This repository demonstrates a common error in React Native applications: the 'Cannot read properties of undefined (reading 'name')' error. This error occurs when trying to access a property of an object that is null or undefined, often due to asynchronous data loading.  The solution involves using optional chaining or nullish coalescing operators to gracefully handle undefined values.

## Bug Description
The bug occurs when a component attempts to access a property of an object before the object has been properly populated with data from an API call or other asynchronous operation.