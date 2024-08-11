```markdown
# HTML Hidden Input Example

This project demonstrates the usage of the `<input type="hidden">` element in an HTML form. The hidden input field is used to store data that is not visible to the user but is still sent to the server when the form is submitted.

## File Structure

- **index.html**: The main HTML file that contains the form with a hidden input.

## Code Explanation

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Hidden</title>
</head>
<body>
    <form action="">
        <input type="hidden" name="user_id" value="Nazmi">
        <label for="name">Name : </label>
        <input type="text" name="name" id="name"> <br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
```

### Explanation of `<input type="hidden">`

- **Purpose**: The `<input type="hidden">` element is used to include data that should be submitted with the form but is not visible to the user. This can be useful for sending additional data to the server, like user IDs, tokens, or any other information that should not be altered by the user.

- **Attributes**:
  - `name`: This attribute defines the name of the input field, which will be sent to the server as a key in the form data.
  - `value`: This attribute holds the value that will be sent to the server along with the form data.

### Example Usage

In this example, the hidden input field with the name `user_id` and value `Nazmi` is included in the form. When the form is submitted, the data sent to the server will include the value of `user_id` along with the other visible fields in the form.

```plaintext
user_id=Nazmi&name=UserInput
```

### Practical Use Cases

- **Tracking User Data**: Hidden inputs can be used to track user-related information, such as user IDs, session tokens, or other metadata, without displaying it to the user.
- **Passing Static Data**: Use hidden inputs to pass static data or configuration values that need to be included with the form submission.
- **Form State Management**: Hidden inputs can be used to manage form state or preserve data across different form submissions.

## Conclusion

The `<input type="hidden">` is a simple yet powerful element in HTML forms that allows developers to include non-visible data in form submissions. This can be useful in many scenarios, such as tracking user information, maintaining form state, or passing additional data to the server.
