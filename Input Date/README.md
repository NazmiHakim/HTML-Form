```markdown
# Date Input Form

This HTML document contains a form with a date input field that allows users to select a date within a specified range. The document is structured to be simple and easy to understand.

## File Overview

- `index.html`: Contains the HTML structure for the date input form.

## HTML Structure

The HTML file consists of the following key elements:

1. **DOCTYPE Declaration**: Specifies the document type and version of HTML.
2. **HTML Element**: The root element of the HTML document.
3. **Head Section**: Contains metadata and the title of the document.
4. **Body Section**: Contains the form element with a date input field.

### DOCTYPE Declaration

```html
<!DOCTYPE html>
```

This declaration defines the document type and version of HTML (HTML5 in this case).

### HTML Element

```html
<html lang="en">
```

The `lang` attribute specifies the language of the document (English in this case).

### Head Section

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Date</title>
</head>
```

- `<meta charset="UTF-8">`: Sets the character encoding for the document to UTF-8.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the document is properly scaled on all devices.
- `<title>Input Date</title>`: Sets the title of the document displayed in the browser tab.

### Body Section

```html
<body>
    <form>
        <label for="join-date">Join Date :</label>
        <input type="date" name="join-date" id="join-date" value="2024-08-05" min="2021-01-01" max="2026-01-01">
    </form>
</body>
```

- `<form>`: The container for the form elements.
- `<label for="join-date">Join Date :</label>`: Associates a label with the date input field.
- `<input type="date" name="join-date" id="join-date" value="2024-08-05" min="2021-01-01" max="2026-01-01">`: Creates a date input field with specific attributes:
  - `type="date"`: Specifies that the input field is a date picker.
  - `name="join-date"`: Sets the name of the input field.
  - `id="join-date"`: Sets the ID of the input field.
  - `value="2024-08-05"`: Sets the default value of the input field.
  - `min="2021-01-01"`: Sets the minimum selectable date.
  - `max="2026-01-01"`: Sets the maximum selectable date.

## Usage

1. Open the HTML file in a web browser.
2. Select a date from the date picker within the specified range (January 1, 2021, to January 1, 2026).
3. The default date is set to August 5, 2024.

## Customization

You can customize the date input field by modifying the attributes of the `<input>` element:

- Change the `value` attribute to set a different default date.
- Change the `min` and `max` attributes to adjust the selectable date range.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Date</title>
</head>
<body>
    <form>
        <label for="join-date">Join Date :</label>
        <input type="date" name="join-date" id="join-date" value="2024-08-05" min="2021-01-01" max="2026-01-01">
    </form>
</body>
</html>
```

This example demonstrates a simple form with a date input field. You can integrate it into your project as needed.
