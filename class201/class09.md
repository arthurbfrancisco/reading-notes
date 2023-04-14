# 201-Class:09

## HTML Forms Structure of a Web Form

* Forms are a crucial part of web development because they allow users to input information, interact with a website, and submit data to a server. Use for signing up for an account, submitting a query, making a purchase, or leaving feedback.

1. Clarity with concise and clear labels, instructions, and placeholder text. Keep the layout simple and clean.

2. Accessibility to all users, including those with disabilities, by using proper HTML semantics, providing alternative text for images, and adhering to accessibility standards.

3. Validation help users identify and correct any errors before submitting the form, and provide clear error messages to guide users.

4. Responsiveness: Design your form to work well on different devices and screen sizes, ensuring a consistent and user-friendly experience.

5. Minimize the number of required fields, for the information you absolutely need, as too many fields can overwhelm users and lead to form abandonment.

1. The input> element is the most versatile form element and can be used for various types of user input, such as text, numbers, email addresses, dates, and more. It allows users to enter information that will be processed by the server.

2. The textarea> element is used for multiline text input, which is useful for collecting longer pieces of information like comments, descriptions, or messages.

3.  The select> element creates a drop-down list of options for users to choose from. This is particularly helpful when you have a predefined set of options, and it helps keep the form tidy and compact.

4. The button> element represents a clickable button, typically used to submit the form or perform other actions. Buttons are crucial for user interactions and make it clear what action will be taken upon clicking.

5. The label> element is used to provide a text description for form controls like input fields or checkboxes. Proper labeling is essential for accessibility and helps users understand the purpose of each form element.

### Event Listeners

* Include clicking on buttons, typing in a text box, scrolling, or even just moving the mouse. Web developers use events to detect and respond to these user interactions, making websites more dynamic and interactive.

 ### JS AddEventListener() method, what 2 argument:

 1. event type: This is a string representing the type of event you want to listen for, such as "click", "mousedown", "keyup", or "submit".

2. event handler: This is a function that will be executed when the specified event occurs on the targeted element. The event handler typically receives an event object as an argument, which contains information about the event.


**Target**: The event object is a JavaScript object that is automatically created when an event occurs.

*Event bubbling* and event capturing are two different phases of event propagation in the browser's Document Object Model (DOM). When an event occurs on an element, it can either propagate up (bubbling) or down (capturing) the DOM tree.

* Event bubbling: In this phase, the event starts from the target element and propagates up to the root of the DOM tree. It passes through each ancestor element, giving each a chance to react to the event. Bubbling is the most commonly used propagation method and is the default behavior in most browsers.
* Event capturing: In this phase, the event starts from the root of the DOM tree and propagates down towards the target element. It passes through each ancestor element on the way down, allowing them to react to the event before it reaches the target. Event capturing is less common and must be explicitly specified when setting up event listeners using the addEventListener method.

