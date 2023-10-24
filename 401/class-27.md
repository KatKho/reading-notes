# useState() Hook

## Thinking in React

### Summarize the five steps of thinking in react.

1. **Break the UI into a Component Hierarchy**: Start by drawing boxes around each part of the interface and give them names. This sets the foundation for your component structure.
   
2. **Build a Static Version in React**: Build a static, non-interactive version of your UI using React components.
   
3. **Identify the Minimal Representation of UI State**: Figure out the minimal state your application needs and where it should live.
  
4. **Identify Where Your State Should Live**: Determine which component should own the state, and move it there if needed.
  
5. **Add Inverse Data Flow**: Allow data to flow from child components to parent components through callbacks or other methods to keep the state consistent across the application.

## State: A Component’s Memory

### What is one reason a local variable isn’t sufficient for managing a React component?

A local variable won't trigger a re-render of the component when its value changes. Therefore, it's not suitable for managing state that impacts the UI.

### What is the argument to the useState hook, and what are the two parts of its return array?

The argument to the `useState` hook is the initial state. The hook returns an array where the first element is the current state and the second element is a function to update that state.

### How can Component A access state from Component B?

Component A can access state from Component B through props if Component A is a child of Component B. Alternatively, you can use context, Redux, or other state management libraries to share state between unrelated components.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
