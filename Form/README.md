```markdown
# HTML Form Example

This project demonstrates a basic HTML form setup. The form is configured to submit data to a specified URL using the POST method and opens the submission result in a new tab.

## HTML Code

The following is the HTML code for the form:

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
    </form>
</body>
</html>
```

## Explanation

- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html lang="en">`: Specifies the language of the document as English.
- `<head>`: Contains meta-information about the document.
    - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the page is responsive on all devices.
    - `<title>Form</title>`: Sets the title of the document.
- `<body>`: Contains the content of the document.
    - `<form>`: Represents the form itself.
        - `name="example"`: Sets the name of the form.
        - `action="form-submit.html"`: Specifies the URL where the form data will be sent.
        - `enctype="application/x-www-form-urlencoded"`: Sets the encoding type for the form data.
        - `method="post"`: Specifies the HTTP method to use when sending form data.
        - `target="_blank"`: Opens the form submission result in a new tab.

## Customization

To customize this form, you can add various input elements such as text fields, checkboxes, radio buttons, etc., within the `<form>` tag. Here’s an example:

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
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

In this customized example:
- A label and text input field for "Name".
- A label and email input field for "Email".
- A submit button to send the form data.

## Usage

1. Copy the HTML code into an `.html` file (e.g., `index.html`).
2. Open the file in a web browser to view and test the form.
3. Customize the form fields as needed.
