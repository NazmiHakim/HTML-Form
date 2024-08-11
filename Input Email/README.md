```markdown
# Input Email in HTML

This project demonstrates how to use the `<input>` element with the `email` type in an HTML form. The `email` input type is used to capture a user's email address, ensuring that the input adheres to the standard format of an email address.

## Overview

The HTML form in this project contains a single `input` field of type `email`:
- **Email Address**: A required field where the user must enter a valid email address.

The form is simple and functional, designed to validate the user's input to ensure it is a properly formatted email address before submission. This is commonly used in contact forms, registration forms, or any other scenario where an email address is needed.

## HTML Code

Here is the HTML code used in this project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Email</title>
</head>
<body>
    <form action="">
        <label for="email">Email :</label>
        <input type="email" name="email" id="email" required>
        <input type="submit" value="Send">
    </form>
</body>
</html>
```

### Explanation

- **`<label for="email">Email :</label>`**: This label is associated with the email input field.
- **`<input type="email" name="email" id="email" required>`**: This input field allows the user to enter their email address. The `email` type ensures that the input follows the email address format (e.g., `user@example.com`). The `required` attribute makes this field mandatory, so the form cannot be submitted unless a valid email address is entered.
- **`<input type="submit" value="Send">`**: This submit button allows the form to be submitted.

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in your web browser.
3. Use the form to input a valid email address, then submit the form.

## Notes

- The `email` input type is supported in most modern browsers, ensuring that the input is checked against the standard email format before submission.
- The `required` attribute ensures that the form cannot be submitted unless the email field is filled out with a valid email address.
