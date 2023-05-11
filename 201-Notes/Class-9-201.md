# Class 09 Reading Notes

This reading covers the basics of HTML input forms as well as events within JavaScript.

## HTML Forms

- Why are forms so important in web development?

> Forms are important because they are the main point of interaction for a user with a website or application.  It allows the user to enter data.

- When designing a form, what are some key things to keep in mind when it comes to user experience?

> Long forms risk frustrating the user.  You should keep form length limited to the minimum amount of data you must absolutely collect.  Also put buttons where it is easy for the user to see them.  Label buttons with what they do.

- List 5 form elements and explain their importance.

> \<form> - semantic container element for forms. <br>
> \<label> - labels your other form elements. <br>
> \<input> - input for a single-line text field. <br>
> \<textarea> - input field for a multiline text field. <br>
> \<button> - allows for an action like submitting data when the form is complete.

## Learn JS

- How would you describe events to a non-technical friend?

> Events are the way we can listen for things to happen on our website (like a click or  hover) and then cause something else to happen on our site because of that action.  Think about somebody hitting the play button on spotify for instance.

- When using the `addEventListener()` method, what 2 arguments will you need to provide?

> We need to provide the event (like "click") and the handler, or function that will run on the event as the second argument.

- Describe the event object.  Why is the target within the event object useful?

> The event object is automatically passed to event handlers.  It can be useful to provide extra features and information.

- What is the difference between event bubbling and event capturing?

> In event bubbling, events targeted at a nested element bubble up to their parent elements.  In event capturing, an event fires on the outermost element and then successively down to the target element.

## Things I want to know more about

- What is a situation where we would want to use event capture?