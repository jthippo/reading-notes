# forms-and-js-events

#### Why are forms so important in web development?

Web forms are a powerful tool for interacting with users, most commonly used for collecting data from users or allowing them to control a user interface.

#### When designing a form, what are some key things to keep in mind when it comes to user experience?

- Keep it simple, ask only for the data you absolutely need.
- Make buttons look like buttons and put them where users can find them.
- Visually group fields that belong together.

#### List 5 form elements and explain their importance.

- < form > starts off all forms
- < label > labels each input field
- < input > indicates a single line text field
- < textarea > indicates a multi-line text field
- < button > indicates a button

#### How would you describe events to a non-technical friend?

Events are things that occur in the system you are programming. The system tells you about them happening so your code can react to them.

#### When using the addEventListener() method, what 2 arguments will you need to provide?

_Type_ (the event type to listen for) and _listener_ (the object that receives a notification when an event occurs).

#### Describe the event object. Why is the target within the event object useful?

An event object is placed in an event handler function, specified with a name such as _event_, _evt_ or _e_. It is automatically passed to event handlers to provide extra features and information.

#### What is the difference between event bubbling and event capturing?

Event bubbling describes how the browser handles events targeted at nested elements; the event bubbles up from the innermost/most nested element that was clicked.

Event capture is like event bubbling but the order is reversed; the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.
