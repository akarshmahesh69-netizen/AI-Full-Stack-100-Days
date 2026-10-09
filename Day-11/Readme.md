# Day 11 — JavaScript Form Validation

## What I Learned

* JavaScript form validation
* Reading user input using `.value`
* Removing surrounding whitespace using `.trim()`
* Conditional statements using `if`
* Logical OR operator (`||`)
* Regular expressions
* Using `.test()` to validate input
* NOT operator (`!`)
* Using `return` to stop invalid submissions
* Debugging JavaScript event listeners
* Testing form behavior

## Business Problem

The SCNC B2B clothing website contains a wholesale enquiry form that collects a customer's name, business name, and phone number.

Without validation, users could submit incomplete information or an incorrectly formatted phone number.

## Validation Requirements

The enquiry form should:

* Require a customer name.
* Require a business name.
* Accept only phone numbers containing exactly 10 digits.
* Display an error message when validation fails.
* Display a confirmation message when all validation checks pass.

## What I Built

Improved the existing SCNC B2B website by implementing:

* Name validation
* Business name validation
* Phone-number validation
* Error messages for invalid input
* A personalized confirmation message
* A working enquiry form interaction

## What I Practiced

* Used `.value` to retrieve user input.
* Used `.trim()` to remove whitespace from the beginning and end of input.
* Used `if` conditions to check required fields.
* Used `||` to detect when either required field is empty.
* Used a regular expression to check for exactly 10 digits.
* Used `.test()` to check whether the phone number matches the pattern.
* Used `!` to reverse the validation result.
* Used `return` to stop the function when validation fails.
* Debugged the enquiry form's JavaScript event listeners.
* Tested valid and invalid form inputs in the browser.

## Key Learning

JavaScript validation checks whether user input meets specified requirements before allowing the code to continue.

For example:

```javascript
if (name === "" || business === "") {
    alert("Please enter your name and business name.");
    return;
}
```

This checks whether either required field is empty.

Phone-number validation:

```javascript
if (!/^\d{10}$/.test(phone)) {
    alert("Please enter a valid 10-digit phone number.");
    return;
}
```

This rejects phone-number input that does not contain exactly 10 digits.

The `return` statement stops the function when a validation check fails.

## Testing

Verified that:

* The enquiry form opens when the enquiry button is clicked.
* An empty customer name is rejected.
* An empty business name is rejected.
* A five-digit phone number is rejected.
* A valid 10-digit phone number passes validation.
* Valid inputs display the personalized confirmation message.
* The existing product category filter continues to work.

## What I Demonstrated

* Explained how `.value` retrieves input.
* Explained how `.trim()` removes surrounding whitespace.
* Explained how `if` and `||` validate required fields.
* Explained how `.test()` and `!` work together.
* Explained how `return` stops invalid submissions.
* Implemented and tested validation in the existing website.
* Identified that the current form displays a confirmation but does not save or transmit enquiry data to a backend.


## Status

Day 11 — Complete