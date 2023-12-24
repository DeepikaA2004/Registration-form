# User Registration Form

## Overview

This repository contains a simple HTML document that serves as a user registration form. The form includes fields for collecting essential user information such as name, phone number, email, pin code, password, confirm password, and date of birth. Additionally, the form incorporates basic styling for a clean and user-friendly interface.

## Table of Contents

- [Getting Started](#getting-started)
- [Form Fields](#form-fields)
- [Styling](#styling)
- [Form Validation](#form-validation)

## Getting Started

To use the user registration form in your project, follow these steps:

1. Copy the HTML code from `index.html`.
2. Integrate the code into your project's HTML file.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Add metadata and styling here -->
</head>
<body>
  <!-- User Registration Form -->
  <!-- ... -->
  <script>
    // Add custom scripts here, if needed
  </script>
</body>
</html>
```
## Form Fields
The user registration form includes the following fields:

-- Name: User's name.
-- Phone Number: User's phone number.
-- Email: User's email address.
-- Pin Code: User's pin code.
-- Password: User's chosen password.
-- Confirm Password: Confirmation of the chosen password.
-- Date of Birth: User's date of birth.
-- All fields are required to be filled out for successful form submission.

## Styling
The form is styled using CSS to enhance its visual appeal. Key styling features include:

Background color for the body.
Centered alignment of the form on the page.
A clean and modern design for form elements, including input fields and buttons.
Feel free to modify the styling to match your project's design guidelines.

## Form Validation
The form includes a simple JavaScript script to validate that the entered password and confirmed password match before submission. If the passwords do not match, an alert is displayed, and form submission is prevented.
``` javascript

const form = document.getElementById("user-registration-form");
form.addEventListener("submit", function(event) {
  const password = form.querySelector("#password").value;
  const confirmPassword = form.querySelector("#confirm-password").value;
  if (password !== confirmPassword) {
    alert("Passwords do not match!");
    event.preventDefault();
  }
});
```
This script can be extended or modified to include additional validation logic as needed for your application.

## output

![Screenshot (389)](https://github.com/DeepikaA2004/Registration-form/assets/110418508/f3fc9116-bb49-46e1-8443-d3f545d0c212)


