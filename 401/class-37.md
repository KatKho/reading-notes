# Redux - Combined Reducers

Multiple Reducers Example

### Why create multiple reducers?
Multiple reducers are created to manage different parts of the state separately, making the code more organized and easier to maintain.

### How would you combine multiple reducers?
You would use the `combineReducers` utility function to combine multiple reducers into a single reducer.

### How will you manage state as an immutable object? why?
You would use techniques such as spreading objects or arrays to avoid mutating the state directly. This is important because it helps to maintain a predictable state and makes it easier to debug and test the application.

Redux Docs: Using Combined Reducers

### `combineReducers` is a utility function to simplify the most common use case when writing a Redux application.

### Explain how combineReducers assembles the new state tree.
`combineReducers` takes an object where the keys are the slices of the state and the values are the corresponding reducers. It then combines these reducers into a single reducing function that will be used by the store.

### How would you define initial state in an app using combineReducers?
You would define the initial state in each individual reducer, and `combineReducers` would then assemble the initial state tree based on the initial states of the reducers.

Redux Docs: Combined Reducer Syntax

### Why will you want to split your reducing functions as your app becomes more complex?
Splitting reducing functions as the app becomes more complex helps to maintain a more organized and manageable codebase.

The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

### What is a popular convention when naming reducers?
A popular convention when naming reducers is to name them after the slice of the state they manage.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
