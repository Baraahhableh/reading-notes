# Forms and JS Events

## Chapter 7: “Forms”

Form Controls There are several types of form controls that you can use to collect information from visitors to your site.

- Form Structure
Form controls live inside a <'form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

- action: Every <'form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted. -method: Forms can be sent using one of two methods: get or post.

- Text Input
The <'input> element is used to create several different form controls. The value of the type attribute determines what kind of input they will be creating.


- type="text": When the type attribute has a value of text, it creates a singleline text input.

- name: When users enter information into a form, the server needs to know which form control each piece of data was entered into.

- Password Input
type="password": When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. 


- name: The name attribute indicates the name of the password input, which is sent to the server with the password the user enters.
size, maxlength: It can also carry the size and maxlength attributes like the the single-line text input.


- Drop Down List Box
<'select>: A drop down list box  allows users to select one option from a drop down list.
The <'select> element is used to create a drop down list box. It contains two or more <'option> elements.

- name: The name attribute indicates the name of the form control being sent to the server, along with the value the user selected.
Chapter 14: “Lists, Tables & Forms”

- Bullet Point Styles: list-style-type
The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 

- Positioning the Marker: list-style-position
Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points. This property can take one of two values:

- outside The marker sits to the left of the block of text. (This is the default behaviour if this property is not used.)
inside The marker sits inside the box of text (which is indented).
Table Properties
width, padding, text-transform, letter-spacing, font-size, border-top, border-bottom, text-align, background-color and hover.

# Chapter 6: “Events”
## HOW EVENTS TRIGGER JAVASCRIPT CODE

- When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. 

- Select t he element node(s) you want the script to respond to.
Indicate which event on the selected node(s) will trigger the response.
State the code you want to run when the event occurs.


#### THREE WAYS TO BIND AN EVENT TO AN ELEM ENT
Event handlers let you indicate which event you are waiting for on any particular element. There are three types of event handlers.

_HTML EVENTHANDLERS_

### TRADITIONAL DOM EVENT HANDLERS
DOM LEVEL 2 EVENT LISTENERS
USING PARAMETERS WITH EVENT HANDLERS & LISTENERS
Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround When an event occurs, the event object tells you information about the event, and the element it happened upon.

- Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element

- CHANGING DEFAULT BEHAVIOR
The event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event.

preventDefau1t ()
stopPropagation()
USING BOTH METHODS
FOCUS & BLUR EVENTS


- MOUSE EVENTS
The mouse events are fired when the mouse is moved and also when its buttons are clicked