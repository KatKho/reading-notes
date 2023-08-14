# State and Props

Mastering the React lifecycle and understanding the differences between state and props empower developers to create efficient, modular, and responsive applications.

## React lifecycle

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
   - 'render'
2. What is the very first thing to happen in the lifecycle of React?
   - mounting
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
   - constructor, render, componentDidMount, React Updates, componentWillUnmount
4. What does componentDidMount do?
   - It loads anything using a network request or initialize the DOM

## React State Vs Props

1. What types of things can you pass in the props?
   - You can pass various types of data such as strings, numbers, arrays, objects, functions, and even React elements
2. What is the big difference between props and state?
   - The main difference between props and state in React is that props are used to pass data from parent to child components and are immutable, while state is used to manage internal component data that can change over time and is mutable within the component itself.
3. When do we re-render our application?
   - React components re-render when their props or state change, including changes in parent components affecting child components.
4. What are some examples of things that we could store in state?
   - State holds dynamic data within components, such as user input, API responses, form data, counters, toggle states, and changing component-specific data.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT
