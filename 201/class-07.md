# Read 07

Studying domain modeling, HTML table basics, constructors, and object prototypes is crucial in this module as it provides a foundation for software development and web design. It enables effective communication, structuring tabular data, creating and managing objects, and leveraging inheritance. This knowledge is essential for developing efficient and user-friendly software applications and websites.

## Domain Modeling

1. Explain why we need domain modeling.
   - A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.
  
## HTML Table Basics

1. Why should tables not be used for page layouts?
   - Layout tables reduce accessibility for visually impaired users.
   - Tables produce tag soup.
   - Tables are not automatically responsive.
  
2. List and describe 3 different semantic HTML elements used in an HTML table.
   - The smallest container inside a table is a table cell, which is created by a td element ('td' stands for 'table data').
   - To stop this row from growing and start placing subsequent cells on a second row, we need to use the tr element ('tr' stands for 'table row').
   - Lastly, we need to use th element to define a header - special cells that go at the start of a row or column and define the type of data that row or column contains.

## Introducing Constructors

1. What is a constructor and what are some advantages to using it?
   - A constructor is just a function called using the new keyword. When you call a constructor, it will:
     - create a new object
     - bind this to the new object, so you can refer to this in your constructor code
     - run the code in the constructor
     - return the new object.
2. How does the term this differ when used in an object literal versus when used in a constructor?
   - In an object literal, "this" refers to the object itself. When "this" is used in a constructor function, it refers to the newly created object that is being instantiated. It represents the specific instance of the object that is being created.

## Object Prototypes Using A Constructor

1. Explain prototypes and inheritance via an analogy from your previous work experience.
   - Prototypes:
    In the company, there are predefined job roles or prototypes that define the tasks and responsibilities associated with each role. These prototypes act as a blueprint for creating new employees. Each job role has a specific set of tasks and methods that employees of that role can perform.
   - Inheritance:
    When a new employee joins the company, they inherit the tasks and responsibilities defined by their job role prototype. The employee can perform the tasks assigned to their role, which are inherited from the prototype. They can also have their own unique properties and methods.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT