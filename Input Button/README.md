# HTML Input Button Example

This project demonstrates the use of input buttons in HTML, which trigger JavaScript functions upon user interaction. Input buttons can be used to perform various actions, such as displaying alerts, submitting forms, or triggering other JavaScript functions.

## Example

Below is an HTML example that includes two input buttons. When each button is clicked, it triggers an alert displaying the corresponding message.

### HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Button</title>
</head>
<body>
    <form>
        <input type="button" value="hello" onclick="alert('Hello')">
        <input type="button" value="world" onclick="alert('World')">
    </form>
</body>
</html>
```

### Explanation

- **DOCTYPE Declaration**: Defines the document type and version of HTML.
- **html Tag**: The root element of an HTML document.
- **head Tag**: Contains meta-information about the HTML document, such as the character set and title.
- **meta charset="UTF-8"**: Specifies the character encoding for the HTML document.
- **meta name="viewport"**: Ensures the webpage is responsive by setting the viewport to the device's width and initial scale.
- **title Tag**: Defines the title of the HTML document that appears in the browser's title bar or tab.
- **body Tag**: Contains the content of the HTML document.
- **form Tag**: Represents an HTML form, used to collect user input.
- **input type="button"**: Defines an input button that users can click to trigger an action.
    - **value**: Sets the text displayed on the button.
    - **onclick**: Specifies the JavaScript function to execute when the button is clicked. In this example, `alert('Hello')` and `alert('World')` are called, displaying a simple alert box with the respective messages.

## Usage

To use the provided HTML code:

1. Copy the HTML code into an `.html` file (e.g., `index.html`).
2. Open the `.html` file in a web browser.
3. Click the "hello" button to see an alert with the message "Hello".
4. Click the "world" button to see an alert with the message "World".

## Additional Resources

- [MDN Web Docs: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs: input element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
- [MDN Web Docs: alert function](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert)
