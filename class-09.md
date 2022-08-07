[Home](/README.md)

# Class 09 - Forms and Events

## Web Forms

1. Why are forms so important in web development?

    They are a fundamental way of getting user input, with which we can crate dynamic webpages.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

    We need to make sure to have labels for our input fields in order to make the form accessible to both seeing and visually impaired users.

3. List 5 form elements and explain their importance.

    - `<form></form>` is the semantic tag that contains the form elements.
    - `<label></label>` is the element that describes the type of input we want the user to input.
    - `<input>` tag creates the field for input.
    - `type` attribute of `input` element is where we choose the type of input including types such as 'text', 'number', 'radio', etc. 
    - `name` attribute for `input` is where we name the input in order to make it accesible to JavaScript.

## Introduction To Events

1. How would you describe events to a non-technical friend?

    An `event` is an action taken by a user on our page, for example, clicking a button, submitting a form, zooming in, etc.

2. When using the `addEventListener()` method, what 2 arguments will you need to provide?

    First argument is the `event`, for example `'submit'`.
    Second argument is the event handler function.

3. Describe the event object. Why is the target within the event object useful?

    The `target` within the `event` object represents element the event happened to.
