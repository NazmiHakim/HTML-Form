## HTML Input Form

This README file explains the structure and functionality of an HTML input form. The form is designed to collect user input and submit it to a specified action URL.

### Structure of the HTML File

The HTML file is structured as follows:

1. **DOCTYPE Declaration**: The document type declaration `<!DOCTYPE html>` defines the document as an HTML5 document.
2. **HTML Element**: The `<html>` element is the root element of the HTML document. It contains the `lang` attribute to specify the language of the document (in this case, English).
3. **Head Element**: The `<head>` element contains metadata about the HTML document, such as character set and viewport settings.
4. **Body Element**: The `<body>` element contains the content of the HTML document, including the form element.

### HTML Form Details

The form in this HTML document is used to collect a search query from the user. Here is a breakdown of the form's components:

1. **Form Element**: The `<form>` element defines the form and its attributes:
   - `name="example"`: Assigns a name to the form.
   - `action="form-submit.html"`: Specifies the URL where the form data will be submitted.
   - `enctype="application/x-www-form-urlencoded"`: Sets the encoding type for the form data.
   - `method="post"`: Specifies the HTTP method to be used when submitting the form (POST in this case).
   - `target="_blank"`: Opens the form submission response in a new browser tab or window.

2. **Input Element**: The `<input>` element within the form collects the user's search query:
   - `type="text"`: Specifies that the input field is a text input.
   - `name="search"`: Assigns a name to the input field, which will be used as the key when submitting the form data.

### Example HTML Code

Below is the full HTML code for the input form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <form name="example" action="form-submit.html" enctype="application/x-www-form-urlencoded" method="post" target="_blank">
        <input type="text" name="search">
    </form>
</body>
</html>
```

### Usage

1. **Opening the HTML File**: Open the HTML file in a web browser to view the form.
2. **Entering Data**: Enter a search query into the text input field.
3. **Submitting the Form**: Upon form submission, the data will be sent to the specified `action` URL (`form-submit.html`) using the POST method, and the response will be opened in a new tab or window.

### Conclusion

This HTML form provides a simple and effective way to collect user input and submit it to a specified URL. By following the structure and details provided in this README, you can understand and utilize the form in your web projects.
