# Read 01

The topic of "Component-Based Architecture" is crucial as it provides a structured way to design software by breaking it into reusable components. This approach enhances development efficiency, collaboration, and system maintenance.

Understanding "Props and How to Use it in React" is essential for passing data between components in React applications. Props allow customization and efficient communication within the component hierarchy, ensuring a streamlined data flow. This knowledge is vital for building dynamic and modular React interfaces.

## Component-Based Architecture

1. What is a “component”?
   - A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.
2. What are the characteristics of a component?
   - Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
   - Replaceable − Components may be freely substituted with other similar components.
   - Not context specific − Components are designed to operate in different environments and contexts.
   - Extensible − A component can be extended from existing components to provide new behavior.
   - Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
   - Independent − Components are designed to have minimal dependencies on other components.
3. What are the advantages of using component-based architecture?
   - Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.
   - Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.
   - Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.
   - Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.
   - Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.
   - Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.
   - System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.
   - Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

## What is Props and How to Use it in React

1. What is “props” short for?
   - “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.
2. How are props used in React?
   - Props allow you to customize child components with specific data and functions. Props are read-only and accessed using the props object in the child component. They enable communication between components and help maintain a unidirectional data flow in React applications.
3. What is the flow of props?
   - Props flow from the parent component to the child component, allowing data and behavior customization. The child component uses these props for rendering and functionality, ensuring a controlled and clear data flow throughout the application.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT
