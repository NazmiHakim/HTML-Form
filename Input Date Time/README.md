# HTML Date and Time Input

This project demonstrates how to use the `<input type="datetime-local">` element in HTML to allow users to select a date and time.

## Overview

The HTML `<input type="datetime-local">` element is used to create a control for entering a date and time, including the year, month, day, hours, and minutes.

## Code Example

Here is a basic example of how to use the `datetime-local` input in an HTML form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Date Time</title>
</head>
<body>
    <form>
        <label for="time_submitted">Time Submitted :</label>
        <input type="datetime-local" name="time_submitted" id="time_submitted">
        <input type="submit" value="Submit">
    </form>
</body>
</html>
