# Day 10 — JavaScript Forms & User Input

## What I Learned

* JavaScript form interaction
* JavaScript events and event listeners
* Showing and hiding HTML elements
* `getElementById()`
* Input `.value`
* Variables using `const`
* Reading user input
* Connecting HTML, CSS and JavaScript
* Basic form interaction and testing

## JavaScript Form Interaction

Used the existing SCNC B2B clothing website to understand how JavaScript can respond to user actions and interact with form fields.

The enquiry flow was changed from a simple alert interaction into an interactive enquiry form.

## Form Interaction Practiced

The website should allow users to:

* Click **Enquire About Products**
* Open the enquiry form
* Enter their name
* Enter their business name
* Enter their phone number
* Submit the enquiry
* Receive a personalized confirmation message

## What I Built

Improved the existing SCNC B2B website by adding:

* Interactive enquiry form
* Name input field
* Business name input field
* Phone number input field
* Enquire About Products button interaction
* Submit Enquiry button interaction
* Personalized JavaScript confirmation message

## What I Practiced

* Added IDs to HTML elements so JavaScript could identify them
* Used `getElementById()` to select HTML elements
* Used `addEventListener()` to respond to button clicks
* Used `style.display` to show the enquiry form
* Used `.value` to read information entered by the user
* Stored input values in JavaScript variables
* Used multiple input fields in one interaction
* Tested the complete enquiry flow in the browser

## Key Learning

JavaScript can interact with HTML elements and respond to user actions.

For example:

```javascript
const customerName = document.getElementById("customerName");
```

identifies the input element.

Using:

```javascript
customerName.value
```

retrieves the value entered by the user.

JavaScript can also change the appearance or visibility of an element:

```javascript
document.getElementById("enquiryForm").style.display = "block";
```

This allows a webpage to become interactive rather than only displaying static content.

## Testing

Checked that:

* The enquiry form was hidden when the page loaded
* The enquiry form appeared when **Enquire About Products** was clicked
* The user could enter their name
* The user could enter their business name
* The user could enter their phone number
* The Submit Enquiry button worked
* JavaScript successfully read all three input values
* The personalized confirmation message appeared

## What I Demonstrated

* Explained what JavaScript events are
* Explained how `addEventListener()` works
* Connected an existing HTML button to JavaScript
* Used JavaScript to show a hidden form
* Retrieved user input using `.value`
* Used variables to store user input
* Connected multiple form fields to JavaScript
* Built and tested a complete front-end enquiry interaction

## GitHub Progress

Updated the project with the Day 10 implementation and learning record, committed the changes to Git, and pushed the completed work to GitHub.

## Status

Day 10 — Complete