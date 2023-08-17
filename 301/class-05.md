# Putting it all together

This topic covers software design principles like the Single Responsibility Principle (SRP) for modular components and transitioning from static to dynamic apps. It also explores higher-order functions, enabling flexible programming. These concepts are vital for creating organized, maintainable code and harnessing the power of functions for efficiency and reusability.

## React Docs - Thinking in React

1. What is the single responsibility principle and how does it apply to components?
   - The Single Responsibility Principle (SRP) states that a class or module should have only one reason to change. Applied to components, it means each component should have a singular, well-defined purpose. This ensures clear separation of concerns, making code more modular and maintainable.
2. What does it mean to build a ‘static’ version of your application?
   - Building a 'static' version of an application involves creating a version where content doesn't change dynamically. It's a non-interactive snapshot of the interface. This initial version serves as a foundation to build upon, focusing on layout and appearance before introducing dynamic features.
3. Once you have a static application, what do you need to add?
   - After creating a static app, you need to add interactivity and dynamic behavior. This includes implementing user input handling, fetching data from APIs, and managing state. These additions make the app functional and responsive.
4. What are the three questions you can ask to determine if something is state?
   - Does it change over time?
   - Does it need to be remembered or persisted?
   - Does it affect the behavior or appearance of the application?
5. How can you identify where state needs to live?
   - Component Hierarchy: Check where state-dependent components are placed in the hierarchy.
   - Unidirectional Data Flow: Ensure data flows in one direction to manage changes systematically.
   - Container vs. Presentation Components: Separate state management from UI rendering.
   - Context and State Management Libraries: Use tools like context or state management libraries for efficient state handling.

## Higher-Order Functions

1. What is a “higher-order function”?
   - A higher-order function is one that takes or returns other functions. It treats functions as data, allowing for flexible programming.
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
   - Line 2 creates an inner function that remembers the n value from the outer function. This inner function checks if a given value is greater than that n.
3. Explain how either map or reduce operates, with regards to higher-order functions.
   - map: Applies a function to each array element, returning a new array with transformed values.
   - reduce: Uses a function to accumulate values while iterating through the array, returning a final result. Both leverage higher-order functions for custom behavior.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT