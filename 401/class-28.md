# useEffect hook

1. What is the main intended use case for the useEffect hook?
   - The primary use of useEffect is to execute side effects in functional components. These side effects could be anything from data fetching and subscriptions to manual DOM manipulations.
2. How does the effect’s logic interact with the component?
   - useEffect runs automatically after every render, including the first one. You can control its execution by providing a dependency array. If the values in this array don't change between renders, useEffect won't execute.
3. What is the importance of the return value from the effect’s logic function?
   - The return value from the useEffect logic function serves as a cleanup mechanism. This function will run when the component unmounts or before the next effect is run. It helps in avoiding memory leaks, clearing subscriptions, and other cleanup tasks.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT