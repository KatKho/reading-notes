# Passing Functions as Props

Passing functions as props, utilizing the spread operator, and transferring functions between components are essential concepts in React. They enable efficient data handling, reusability, and interactivity in applications, enhancing state management and user experience. These techniques are fundamental for building dynamic and organized React applications.

## React Docs - lists and keys

1. What does .map() return?
   - The .map() function is used to iterate over elements in an array and transform each element according to a specified transformation function.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
   - You can use the .map() function within the render method of a component
3. Each list item needs a unique ____.  
   - "key" prop
4. What is the purpose of a key?
   - The purpose of a "key" in React is to help the framework identify individual items in a list when they are updated or re-rendered.

## The Spread Operator

1. What is the spread operator?
   - The spread operator, denoted by ..., is a feature introduced in JavaScript ES6 that allows you to expand elements from an iterable (like an array or an object) into various places
2. List 4 things that the spread operator can do.
   - Copying Arrays and Objects
   - Passing Multiple Arguments
   - Combining Arrays
   - Combining Objects
3. Give an example of using the spread operator to combine two arrays.
   - const array1 = [1, 2, 3];
    const array2 = [4, 5, 6];
    const combinedArray = [...array1, ...array2];
4. Give an example of using the spread operator to add a new item to an array.
   - const originalArray = [1, 2, 3];
    const newItem = 4;
    const newArray = [...originalArray, newItem];
5. Give an example of using the spread operator to combine two objects into one.
   - const object1 = { a: 1, b: 2 };
    const object2 = { c: 3, d: 4 };
    const combinedObject = { ...object1, ...object2 };

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
   - The first step that the developer takes to pass functions between components is to define the function in the higher-level parent component
2. In your own words, what does the increment function do?
   - The increment function is responsible for updating the count property of a specific person object in the state
3. How can you pass a method from a parent component into a child component?
   - To pass a method from a parent component into a child component, you can include the method as a prop when rendering the child component
4. How does the child component invoke a method that was passed to it from a parent component?
   - The child component can invoke a method that was passed to it from a parent component by accessing the method through its props

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT