# Input Time in HTML

This project contains a simple HTML form that allows users to input entry and clock-out times. The form includes two fields for time input, using the `<input type="time">` element, which allows users to select or manually enter time values in a specified format.

## Project Structure

- **index.html**: Contains the HTML code for the time input form.

## Features

- **Entry Time Input**: Users can select or enter the time they start work.
- **Clock Out Time Input**: Users can select or enter the time they finish work.
- **Responsive Design**: The form is designed to be responsive and adjusts to different screen sizes.

## HTML Explanation

### Form Elements

1. **Entry Time:**
    - The label is associated with the input field via the `for` attribute, which matches the `id` of the input field.
    - The input type is set to `time`, which provides a time picker UI in browsers that support it.

    ```html
    <label for="entry_time">Entry Time :</label>
    <input type="time" name="entry_time" id="entry_time" value="07:00">
    ```

2. **Clock Out Time:**
    - Similar to the entry time, this field allows users to input their clock-out time.

    ```html
    <label for="clock_out">Clock Out</label>
    <input type="time" name="clock_out" id="clock_out" value="17:00">
    ```

3. **Submit Button:**
    - Submits the form data when clicked. Currently, the form has no action specified, so it will not submit to any server-side script unless modified.

    ```html
    <input type="submit" value="Submit">
    ```

### Default Values

- The `value` attribute for the `entry_time` input is set to "07:00", representing a default start time of 7:00 AM.
- The `value` attribute for the `clock_out` input is set to "17:00", representing a default end time of 5:00 PM.

## How to Use

1. Open `index.html` in a web browser.
2. Use the time pickers to select your entry and clock-out times.
3. Click "Submit" to submit the form. (Note: Without further development, this action currently won't submit data to a server.)

## Compatibility

The time input feature is supported in most modern web browsers. However, in older browsers that do not support `<input type="time">`, the input field will default to a standard text box.
