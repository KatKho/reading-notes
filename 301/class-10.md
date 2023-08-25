# In memory storage

This topic offers insights into function invocation and execution in JavaScript, including the concept of 'calls,' the single-threaded nature of JavaScript, and the significance of LIFO. It also covers error types like 'reference error,' 'syntax error,' 'range error,' and 'type error,' along with the use of breakpoints and debugger tools for effective debugging. This knowledge is pivotal for writing error-free code and ensuring smooth program execution, enhancing code quality and reliability.

## Understanding the JavaScript Call Stack

1. What is a ‘call’?
   - A 'call' refers to invoking a function in JavaScript, where the program's execution transfers to that function.
2. How many ‘calls’ can happen at once?
   - Only one 'call' can happen at a time due to JavaScript's single-threaded nature.
3. What does LIFO mean?
   - LIFO stands for "Last In, First Out," illustrating how the call stack operates with the most recent function being executed first.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
   - 
  ┌──────────────┐     ┌──────────────┐     ┌──────────────┐
  │   function   │     │   function   │     │   function   │
  │     foo()    │     │     bar()    │     │     baz()    │
  └──────────────┘     └──────────────┘     └──────────────┘

5. What causes a Stack Overflow?
   - A Stack Overflow occurs when the call stack's capacity is exceeded due to excessive function nesting.

## JavaScript error messages

1. What is a ‘reference error’?
   - A 'reference error' happens when accessing an undefined variable or function, indicating an identifier issue.
2. What is a ‘syntax error’?
   - A 'syntax error' occurs due to code violating language syntax rules, often caused by incorrect placement or missing characters.
3. What is a ‘range error’?
   - A 'range error' emerges when an operation involves a value outside the valid range.
4. What is a ‘type error’?
   - A 'type error' arises when an operation is performed on an inappropriate data type.
5. What is a breakpoint?
   - A 'breakpoint' is a code location where a debugger can pause execution for inspection.
6. What does the word ‘debugger’ do in your code?
   - A 'debugger' tool helps locate and fix issues by allowing step-by-step code execution, variable inspection, and behavior analysis.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT