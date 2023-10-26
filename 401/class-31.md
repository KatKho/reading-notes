# Context API

## Choosing the State Structure

**Summarize the five principles for structuring state:**

1. **Single Source of Truth:** Maintain your application's state in a centralized location, ensuring consistency.
2. **State Should Be Read-Only:** Never modify the state directly. Instead, use functions or methods to produce a new state.
3. **Changes Are Made with Pure Functions:** Use reducers to specify how the state transitions from one state to the next, given an action.
4. **Keep state normalized:** Reduce redundancy by ensuring each piece of data is stored in only one place.
5. **Avoid Large and Complex States:** Simplify state structure to avoid nested or deep states, making it easier to understand and manage.

## Passing State Deeply with Context

**What problem do Contexts aim to solve?**  
Contexts aim to solve the problem of prop-drilling, where state has to be passed through multiple components that might not necessarily use it.

**What is one technique to try before useContext?**  
One can try lifting the state up to a common ancestor component before resorting to `useContext`.

**What hook complements useContext for complex applications?**  
The `useReducer` hook complements `useContext` for more complex state logic, giving a more structured way to handle state updates.

## Things I Want to Know More About

## Reference

- Reading Materials
- ChatGPT
