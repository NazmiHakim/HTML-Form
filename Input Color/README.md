```markdown
# HTML Color Input Example

This repository contains a simple HTML example demonstrating the use of the `<input type="color">` element. This element allows users to select a color from a color picker.

## File Description

- `index.html`: The main HTML file containing the color input form.

## Usage

To use the color input form, follow these steps:

1. Open the `index.html` file in your web browser.
2. You will see a form with a color input field labeled "Favourite Color".
3. Click on the color input field to open the color picker.
4. Select your desired color from the color picker.
5. The selected color will be displayed in the input field.
6. Click the "submit" button to submit the form.

## Code Explanation

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Color</title>
</head>
<body>
    <form>
        <label for="favourite">Favourite Color : </label>
        <input type="color" name="favourite" id="favourite" value="#ff0000">
        <input type="submit" value="submit">
    </form>
</body>
</html>
```

### HTML Structure

- `<form>`: The form element that contains the input field and the submit button.
- `<label for="favourite">Favourite Color : </label>`: A label for the color input field.
- `<input type="color" name="favourite" id="favourite" value="#ff0000">`: The color input field. The `type="color"` attribute specifies that this is a color input. The `value="#ff0000"` attribute sets the default color to red (#ff0000).
- `<input type="submit" value="submit">`: A submit button to submit the form.

## Customizing the Color Input

You can customize the default color by changing the `value` attribute of the color input field. For example, to set the default color to blue, change the value to `#0000ff`:

```html
<input type="color" name="favourite" id="favourite" value="#0000ff">
```

## Browser Compatibility

The color input type is supported in most modern web browsers. However, some older browsers may not support this feature. In such cases, a text input field may be displayed instead.
