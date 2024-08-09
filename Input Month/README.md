# Month Input in HTML

This project demonstrates how to use the `<input type="month">` element in HTML to create a form that allows users to select a month and year. This type of input is particularly useful for applications that require users to specify a date range without needing a specific day, such as setting expiration dates, scheduling monthly reports, or planning events.

## File Structure

- **index.html**: The HTML file containing the form with a month input.

## Usage

1. **HTML Structure**:
    - The form in `index.html` contains an input field where users can select a month and year.
    - The input field is set to default to December 2024.

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Month</title>
    </head>
    <body>
        <form action="">
            <label for="expired">Expire Month :</label>
            <input type="month" name="expired" id="expired" value="2024-12">
            <input type="submit" value="Submit">
        </form>
    </body>
    </html>
    ```

2. **Input Attributes**:
    - **`type="month"`**: Specifies the type of input, allowing the user to pick a month and year without selecting a specific day.
    - **`name="expired"`**: The name attribute is used to identify the form data after it has been submitted.
    - **`id="expired"`**: Associates the label with the input for accessibility purposes.
    - **`value="2024-12"`**: Pre-fills the input field with December 2024 as the default selection.

3. **Form Submission**:
    - When the user selects a month and submits the form, the selected month and year are sent as a string in the format `YYYY-MM` (e.g., `2024-12`).

## Browser Compatibility

The `<input type="month">` element is supported in most modern browsers, including Chrome, Firefox, Safari, and Edge. However, in some older browsers or mobile devices, the month picker may fall back to a simple text input.

## Customization

- **Default Value**: You can change the default value by modifying the `value` attribute in the HTML code.
- **Min/Max Attributes**: To restrict the range of months available, use the `min` and `max` attributes, like so:
  
    ```html
    <input type="month" name="expired" id="expired" min="2024-01" max="2024-12" value="2024-12">
    ```
