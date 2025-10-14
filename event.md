* click
- occuring when a user presses and releases a mouse button over an element, like a button or a link. It's a fundamental part of creating interactive web pages because it allows the browser to respond to user actions.

* submit
- What it belongs to: The submit event belongs to an entire HTML <form> element. It's an action that the form itself performs.
* How it's triggered: This event is usually triggered in one of two ways:
1. When a user clicks a <button type="submit"> inside that form.
2. When a user presses the Enter key while focused on a text input field inside the form.

- What is the browser's default behavior? 
When a submit event occurs and you don't use any JavaScript, the browser's default action is to gather all the data from the form's input fields and send it to a server. This process almost always causes the page to reload or navigate to a new page.

### Mouse Events

* mouseover
Triggered when: The mouse pointer moves onto an element.
Common Use Case: Showing a dropdown menu, highlighting a button, or displaying a tooltip when a user hovers over something.

* mouseout
Triggered when: The mouse pointer moves off of an element.
Common Use Case: Hiding the dropdown menu or tooltip that appeared on mouseover.

* mousedown / mouseup
Triggered when: The mouse button is pressed down (mousedown) or released (mouseup).
Common Use Case: Used for creating drag-and-drop functionality. You start dragging on mousedown and stop on mouseup.

### Keyboard Events

* keydown
Triggered when: Any key on the keyboard is pressed down.
Common Use Case: Creating keyboard shortcuts (like Ctrl + S) or controlling a character in a game.
* keyup
Triggered when: A key is released.
Common Use Case: Triggering a search function after a user has finished typing their query. This is often better than keydown because it waits for the character to actually appear in the input box.

### Form Evemnts

* submit: Fires when a form is submitted (e.g., by clicking a submit button or pressing Enter). This is where you'd typically validate input before sending it to a server.
* focus: Fires when an element (like an input field) receives focus, meaning it's ready for user input.
* blur: The opposite of focus. Fires when an element loses focus.
* change: Fires when the value of an element like <input>, <select>, or <textarea> has been changed.
* input: Fires immediately whenever the value of an <input> or <textarea> element changes. Unlike change, it triggers on every keystroke.

### Document/Window Events

* load: Fires on the window object when the entire page and all its resources (images, CSS files, etc.) have finished loading. This is often used to run setup code.
* DOMContentLoaded: Fires when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets and images to finish loading. It's often a better choice than load for running scripts that only need the HTML structure.
* resize: Fires when the browser window is resized.
* scroll: Fires when the user scrolls up or down the page.