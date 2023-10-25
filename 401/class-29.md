# Advanced State with Reducers

## Extracting State Logic into a Reducer

### What is the motivation for adding a reducer?

Reducers are mainly added to manage state in a more predictable manner. In complex applications where state transitions are involved, reducers offer a clear and centralized way to handle such transitions. The motivation is often to achieve scalability, maintainability, and easier debugging capabilities.

### What are actions in the context of a reducer? How are they different than setting state directly?

Actions in the context of a reducer are objects that provide information about what should change, often having a `type` property that defines the type of operation to be performed on the state. They might also carry some payload to provide additional details. When using a reducer, instead of setting state directly, you dispatch an action that describes the change. The reducer then determines how the state should change in response to that action. This distinction makes state changes more predictable and easier to trace.

### What common list operation is useReduce named for, and why?

The `useReducer` hook is named after the `reduce` function commonly used in JavaScript, which processes a list (or array) to combine its items into a single value. The similarity is in how both handle accumulated values. In the context of `useReducer`, it refers to accumulating state values over time, based on actions dispatched.

### When should you switch from useState to useReducer?

You should consider switching from `useState` to `useReducer` when:
- The state logic becomes more complex.
- You have multiple related pieces of state that need to be managed together.
- There are complex state transitions or when the next state depends on the previous one.
- When you need clearer action descriptions for state changes, which can be especially beneficial for debugging.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
