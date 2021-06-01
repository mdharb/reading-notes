# **HTML**

## **Forms**

* Is collecting information from visitors using `<form>` tag in ***html***.

> The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

### **Types of Form Controls:**

* Adding text.
  - Text input ***(single-line)***.
  - Password input.
  - Text area ***(multi-line)***.

* Making Choices.
  - Radio buttons.
  - Checkboxes.
  - Drop-down boxes.

* Submitting Forms.
  - Submit buttons.
  - Image buttons.

* Uploading Files.
  - File upload.

# **CSS**

* List markers can be given different appearances using the list-style-type and list-style image properties.
* Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 
* Forms are easier to use if the form controls are vertically aligned using CSS.
* Forms benefit from styles that make them feel more interactive.

# **JavaScript**

## **Events**

### **Event Handling:**

* When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as ***event handling***.

1. Select the **element node(s)** you want the script to respond to.
2. ndicate which **event** on the selected node(s) will trigger the response.
3. State the **code** you want to run when the event occurs. 

### **Event flow:**

* HTML elemetns nest inside other elments. If you hover or click on a link, you will be hovering or clicking on it parent elements.

* The flow of event only really matters when your code has event handlers on an element, and one of its ***ancestor*** or ***descendant*** elements.

### **Event Object**

* When an event occurs, the event object tells you information about the event, and the element it happened upon.

### **Event delegation:**

* Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.

### **Changing defult behavior:**

* The event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event:
  - `preventDefault()`.
  - `stopPropagation()`.
  - `Using both methods`.

### **Different type of methods:**

* USER INTERFACE EVENTS.
* FOCUS & BLUR EVENTS.
* MOUSE EVENTS.
* KEYBOARD EVENTS.
* FORM EVENTS.
* MUTATION EVENTS & OBSERVERS.
* HTML5 EVENTS.
* W3C DOM.




