# Redux - Asynchronous Actions

## async actions

### Why use Redux middleware?
Redux middleware is used to extend the capabilities of Redux, allowing for side effects such as asynchronous actions, logging, and more.

### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
The Redux Async Data Flow Diagram shows the process of dispatching an action, having the middleware handle the asynchronous operation, then dispatching a new action with the result of the async operation, which is then handled by the reducer to update the state.

### How are we accommodating async in our Redux app?
In a Redux app, async is accommodated through the use of middleware, such as redux-thunk, which allows for asynchronous actions to be dispatched.

## thunk middleware

### Why would you need redux-thunk middleware?
Redux-thunk middleware is needed to handle asynchronous actions in a Redux application, such as fetching data from an API.

Redux Thunk middleware allows you to write action creators that return a function instead of an action.

### Describe how any return value from the inner thunk function will be made available.
The return value from the inner thunk function will be made available as the resolved value of the promise returned by the dispatch function.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
