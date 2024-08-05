# Input Checkbox in HTML

## Example Code

Below is a sample HTML code that demonstrates the use of checkboxes in a form:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Checkbox</title>
</head>
<body>
    <form>
        Hobby : <br>

        <input type="checkbox" name="hobby" id="coding" value="Coding">
        <label for="coding"> Coding</label>
        <br>
        <input type="checkbox" name="hobby" id="gaming" value="Gaming">
        <label for="gaming"> Gaming</label>
        <br>
        <input type="checkbox" name="hobby" id="reading" value="Reading">
        <label for="reading"> Reading</label>
        <br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

## Explanation

### HTML Structure

1. **DOCTYPE Declaration**: Defines the document type and version of HTML.
    ```html
    <!DOCTYPE html>
    ```

2. **HTML Tag**: The root element of an HTML page.
    ```html
    <html lang="en">
    ```

3. **Head Section**: Contains meta-information about the document, such as the character set and viewport settings.
    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Input Checkbox</title>
    </head>
    ```

4. **Body Section**: Contains the content of the HTML document.
    ```html
    <body>
        <!-- Content goes here -->
    </body>
    ```

### Form Elements

- **Form Tag**: Defines the start of the form.
    ```html
    <form>
    ```

- **Checkbox Inputs**: Each checkbox is created using the `<input type="checkbox">` element. The `name` attribute groups the checkboxes, the `id` attribute uniquely identifies each checkbox, and the `value` attribute specifies the value to be sent to the server when the form is submitted.
    ```html
    <input type="checkbox" name="hobby" id="coding" value="Coding">
    <label for="coding"> Coding</label>
    <br>
    <input type="checkbox" name="hobby" id="gaming" value="Gaming">
    <label for="gaming"> Gaming</label>
    <br>
    <input type="checkbox" name="hobby" id="reading" value="Reading">
    <label for="reading"> Reading</label>
    <br>
    ```

- **Submit Button**: A button to submit the form data.
    ```html
    <input type="submit" value="Submit">
    ```

### Labels

- **Label Tag**: The `<label>` element is used to provide a label for each checkbox. The `for` attribute is associated with the `id` of the corresponding checkbox.
    ```html
    <label for="coding"> Coding</label>
    ```

### Line Breaks

- **Line Break Tag**: The `<br>` element inserts a line break, ensuring that each checkbox appears on a new line.
    ```html
    <br>
    ```

## Usage

To use this code, simply copy and paste it into an HTML file and open it in a web browser. The form will display three checkboxes labeled "Coding," "Gaming," and "Reading." Users can select one or more options and submit the form.

## Conclusion

Checkboxes are a versatile input type in HTML forms, allowing users to select multiple options from a list. This example provides a basic implementation, which can be expanded and styled further according to specific needs.
