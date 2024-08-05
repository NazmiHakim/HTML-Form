```markdown
# Input Reset in HTML

This document provides an overview of an HTML form with an input reset functionality. The form includes fields for name, email, and phone number, with a default phone number prefix. It also includes buttons to reset the form and submit the form.

## HTML Structure

The form is structured using standard HTML tags and attributes. The key components of the form are:

- **Form Element**: The `<form>` element encapsulates all the input fields and buttons.
- **Label and Input Elements**: Each input field has a corresponding `<label>` for better accessibility.
- **Reset and Submit Buttons**: The form includes a reset button to clear the input fields and a submit button to submit the form data.

## Code Explanation

### Form Element

```html
<form name="registration">
```
The form element with the name attribute set to "registration". This is the container for all the input fields and buttons.

### Input Fields

```html
<label for="name">Name :</label><br>
<input type="text" name="name" id="name"><br>

<label for="email">Email :</label><br>
<input type="text" name="email" id="email"><br>

<label for="phone">Phone Number :</label><br>
<input type="text" name="phone" id="phone" value="+62"><br>
```
Each input field is associated with a label for better user experience and accessibility. The `value` attribute of the phone input field is set to "+62" as a default prefix.

### Reset and Submit Buttons

```html
<input type="reset" value="reset">
<input type="submit" value="registration">
```
- **Reset Button**: `<input type="reset" value="reset">` resets all input fields to their initial values. This is useful for clearing the form quickly.
- **Submit Button**: `<input type="submit" value="registration">` submits the form data for processing.

## Example HTML Code

Below is the complete HTML code for the form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Reset</title>
</head>
<body>
    <form name="registration">
        <label for="name">Name :</label><br>
        <input type="text" name="name" id="name"><br>
        <label for="email">Email :</label><br>
        <input type="text" name="email" id="email"><br>
        <label for="phone">Phone Number :</label><br>
        <input type="text" name="phone" id="phone" value="+62"><br>
        <input type="reset" value="reset">
        <input type="submit" value="registration">
    </form>
</body>
</html>
```

## Usage

1. Open the HTML file in a web browser.
2. Fill in the input fields with the desired information.
3. Click the "reset" button to clear all input fields and return them to their default values.
4. Click the "registration" button to submit the form data.

## Conclusion

This HTML form demonstrates the use of the reset button to clear input fields. This feature is useful for users who want to quickly reset the form without manually clearing each field.
