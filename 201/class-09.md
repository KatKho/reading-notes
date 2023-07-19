# Read 09

HTML forms allow users to input and submit data accurately, and properly structuring them ensures usability and accessibility. JavaScript events enable interactivity by triggering actions in response to user interactions. Understanding events and using the event object helps developers respond to events and manipulate specific elements that triggered the events. Mastering these topics empowers developers to create user-friendly forms and dynamic web applications.

## HTML Forms. Your first Web Form. How To Structure A Web Form

1. Why are forms so important in web development?
   - The flexibility of forms makes them one of the most complex structures in HTML; you can build any kind of basic form using dedicated form elements and attributes. Using the correct structure when building an HTML form will help ensure that the form is both usable and accessible.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
   - The label element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms — when implemented properly, screen readers will speak a form element's label along with any related instructions, as well as it being useful for sighted users.
  
3. List 5 form elements and explain their importance.
   - The form element is the container for form elements and handles data submission.
   - The fieldset element groups related form elements together.
   - The legend element provides a caption or title for the grouped fields.
   - The label element associates text with form controls, enhancing accessibility.
   - The input element creates various types of form controls for user input.

## Learn JS .Introduction To Events

1. How would you describe events to a non-technical friend?
   - Events in JavaScript are like activities or moments that trigger certain actions.
2. When using the addEventListener() method, what 2 arguments will you need to provide?
   - The first argument is the event you want to listen for. The second argument is the function that will be invoked or executed when the specified event occurs.
3. Describe the event object. Why is the target within the event object useful?
   - The event object is a special object that contains information and properties related to an event that has occurred. It provides details about the event itself, such as the type of event, the element on which the event occurred, and additional data associated with the event.
4. What is the difference between event bubbling and event capturing?
   - Event capturing is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

## Things I want to know more about

## Reference

- Reading Materials
- ChatGPT