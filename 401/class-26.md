# Component Based UI

## React Quick Start

**What are the building blocks of a React app?**  
The building blocks of a React app are components.

**What is the difference between an HTML element and a React component?**  
An HTML element represents a DOM node, while a React component can represent multiple DOM nodes and can contain logic.

**What is JSX and why do we use it?**  
JSX is a syntax extension for JavaScript. It allows us to write HTML-like code within JavaScript, making it easier to create and visualize React components.

**Describe the process of embedding JavaScript expressions in JSX.**  
JavaScript expressions can be embedded in JSX by wrapping them in curly braces `{}`.

**Does React or JSX have any special features for iteration or conditional logic?**  
No, React and JSX don't have special iteration or conditional logic features. We use JavaScript's native features for these purposes.

**How does React know to respond to a user’s inputs?**  
React responds to user inputs using event handlers, like `onClick` and `onChange`.

**What word indicates that a React component manages data with a Hook?**  
The word "use" (as in `useState`, `useEffect`, etc.) indicates that a React component manages data with a Hook.

**How can two react components share data?**  
Two React components can share data through props or by using context.

## Render and Commit

**What are the three steps of refreshing a React UI?**  
1. Reconciliation
2. Render
3. Commit

**How do you trigger updates to a component after the initial render?**  
Updates can be triggered by calling `setState`, using hooks like `useState`, or receiving new props.

**Does React recreate DOM nodes on every rerender?**  
No, React only updates the parts of the DOM that have changed, using a process called reconciliation.

**After React has updated the DOM, what still needs to happen before the user sees the change?**  
After React has updated the DOM, the browser needs to repaint the screen for the user to see the changes.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
