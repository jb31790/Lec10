# Lec10
Lecture 10


# Tasks

## Task 1: Click Event to Increment a Variable
**Objective:** Create a button and a paragraph (<p>) element on a webpage. Each time the button is clicked, increment a variable and update the paragraph to display its new value.

### Instructions:
1. Add a `<button>` element and a `<p>` element with an id, e.g., `id="displayCount"` to your HTML page.
2. Define a variable in your JavaScript file to keep track of the count, e.g., `let count = 0;`.
3. Select the button using `document.getElementById('myButton')` and the paragraph using `document.getElementById('displayCount')`.
4. Add an event listener to the button for the 'click' event.
5. Inside the event listener, increment the variable `count` by 1.
6. Update the text content of the `<p>` element to display the current value of `count`.


## Task 2: Keyup Event
**Objective:** Create a text input field. Display the current value of the input field in a <div> whenever a key is released.

### Instructions:
1. Add an `<input>` element and a `<div>` element with an id, e.g., `id="displayDiv"`.
2. In your JavaScript, select the input field using an appropriate selector.
3. Add an event listener to the input field for the 'keyup' event.
4. Inside the event listener, update the content of the `<div>` with the current value of the input field.

**Expected Outcome:** As the user types in the input field, the `<div>` updates to show the current input value.


## Task 3: Form Submit Event
**Objective:** Create a form with a submit button. Prevent the default form submission and display a custom message when the form is submitted.

### Instructions:
1. Create a form with an `<input>` field and a submit button.
2. In your JavaScript, select the form using an appropriate selector.
3. Add an event listener to the form for the 'submit' event.
4. Inside the event listener, use `event.preventDefault()` to prevent the form from submitting, and then display a custom message, e.g., using `alert()` or updating a `<div>`.

**Expected Outcome:** When the submit button is clicked, the page should not refresh, and the custom message should be displayed.


## Task 4: Mouseover Event
**Objective:** Create a div with some text. Change the text color when the mouse is hovered over it.

### Instructions:
1. Add a `<div>` element with some text and an id, e.g., `id="hoverDiv"`.
2. In your JavaScript, select the div using `document.getElementById('hoverDiv')`.
3. Add an event listener for the 'mouseover' event.
4. Inside the event listener, change the style of the div, for instance, `element.style.color = 'red';`.

**Expected Outcome:** When the user hovers the mouse over the div, the text color should change.
