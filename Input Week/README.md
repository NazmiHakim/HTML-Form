```markdown
# Input Week in HTML

This project demonstrates how to use the `<input>` element with the `week` type in an HTML form. The `week` input type allows users to select a specific week of the year, which is useful in scenarios where precise week-based date selection is needed.

## Overview

The HTML form in this project contains two `input` fields of type `week`:
- **Start Week**: The starting week selection.
- **End Week**: The ending week selection.

The form is simple and allows the user to select a range of weeks, from a start week to an end week, and submit the form. This can be useful in applications such as booking systems, project planning tools, or any other system that requires input of a week range.

## HTML Code

Here is the HTML code used in this project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Week</title>
</head>
<body>
    <form action="">
        <label for="start">Start :</label>
        <input type="week" name="start" id="start" value="2024-W01"> <br>
        <label for="end">End :</label>
        <input type="week" name="end" id="end" value="2024-W52"> <br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

### Explanation

- **`<label for="start">Start :</label>`**: This label is associated with the start week input field.
- **`<input type="week" name="start" id="start" value="2024-W01">`**: This input field allows the user to select the starting week of the year. The default value is set to the first week of 2024 (`2024-W01`).
- **`<label for="end">End :</label>`**: This label is associated with the end week input field.
- **`<input type="week" name="end" id="end" value="2024-W52">`**: This input field allows the user to select the ending week of the year. The default value is set to the last week of 2024 (`2024-W52`).
- **`<input type="submit" value="Submit">`**: This submit button allows the form to be submitted.

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in your web browser.
3. Use the form to select a start and end week, then submit the form.

## Notes

- The `week` input type is supported in most modern browsers, but it might not be supported in older browsers.
- The default values in the input fields (`2024-W01` and `2024-W52`) ensure that users have a reference for the beginning and end of the year 2024.
