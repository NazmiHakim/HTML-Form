Here is a README.md file that explains the creation and usage of an input submit form in HTML:

```markdown
# Input Submit Form in HTML

## Overview

This document provides an example of a basic HTML form for user registration. The form collects a user's name, email, and phone number, and includes a submit button to send the information.

## HTML Structure

The HTML form is structured using the following elements:
- `<form>`: Defines the form element.
- `<label>`: Defines labels for the input elements.
- `<input>`: Defines input fields where users can enter their data.
- `<br>`: Inserts line breaks for better readability.

## Code Example

Below is the complete HTML code for the registration form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Label</title>
</head>
<body>
    <form name="registration">
        <label for="name">Name :</label><br>
        <input type="text" name="name" id="name"><br>
        <label for="email">Email :</label><br>
        <input type="text" name="email" id="email"><br>
        <label for="phone">Phone Number :</label><br>
        <input type="text" name="phone" id="phone"><br>
        <input type="submit" value="Registration">
    </form>
</body>
</html>
```

## Explanation

1. **DOCTYPE Declaration**:
   ```html
   <!DOCTYPE html>
   ```
   This declares the document type and version of HTML being used.

2. **HTML Element**:
   ```html
   <html lang="en">
   ```
   The root element of the HTML document, with the language set to English.

3. **Head Section**:
   ```html
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Label</title>
   </head>
   ```
   Contains meta-information about the document, including the character set, viewport settings, and the title.

4. **Body Section**:
   ```html
   <body>
       <form name="registration">
           <label for="name">Name :</label><br>
           <input type="text" name="name" id="name"><br>
           <label for="email">Email :</label><br>
           <input type="text" name="email" id="email"><br>
           <label for="phone">Phone Number :</label><br>
           <input type="text" name="phone" id="phone"><br>
           <input type="submit" value="Registration">
       </form>
   </body>
   ```
   Contains the main content of the HTML document. Here, it includes the form with input fields for the user's name, email, and phone number, and a submit button.

## Form Elements

- **Form Tag**:
  ```html
  <form name="registration">
  ```
  Defines the start of the form and gives it a name attribute.

- **Label and Input Tags**:
  ```html
  <label for="name">Name :</label><br>
  <input type="text" name="name" id="name"><br>
  ```
  Each label is associated with an input field through the `for` attribute, which matches the `id` of the corresponding input element.

- **Submit Button**:
  ```html
  <input type="submit" value="Registration">
  ```
  Creates a button that submits the form data when clicked.

## Usage

1. Save the HTML code in a file with a `.html` extension, such as `registration.html`.
2. Open the file in a web browser to view and interact with the form.
3. Fill in the fields and click the "Registration" button to submit the data.

## Conclusion

This example provides a simple, yet functional HTML form for collecting user information. It can be used as a starting point for more complex forms by adding additional input fields, validation, and styling as needed.
