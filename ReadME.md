# Google Sheets Student Filtering Tool

This project is a Google Sheets Add-on that allows users to filter student data based on multiple constraints across selected columns. It provides a user-friendly interface to specify filtering conditions, sort data, and create a new sheet with the filtered results.

## Features

- **Custom Menu**: Adds a custom menu to Google Sheets for easy access.
- **Dynamic Filtering**: Allows users to apply multiple constraints for each column (e.g., filtering by branch and gender).
- **Sorting Options**: Users can sort the filtered results based on a specified column and order (ascending or descending).
- **Unique Sheet Creation**: Generates a new sheet with a unique name based on the applied constraints.

## Usage

1. **Open Google Sheets** and create or select a spreadsheet with student data.
2. **Add the Script**:
   - Go to `Extensions > Apps Script`.
   - Replace the default code with the provided script in `Code.gs`.
   - Create an HTML file named `FilterStudents.html` and include the HTML code for the dialog interface (not provided in this README).
3. **Authorize the Script**: When you run the script for the first time, you will need to authorize it to access your Google Sheets data.
4. **Use the Filter**:
   - After adding the script, refresh the Google Sheets page.
   - Click on the custom menu `Custom Menu > Filter Students`.
   - Follow the prompts to select columns and define constraints.
   - A new sheet will be created with the filtered data based on your criteria.

## Constraints Supported

- **equals**: Matches the exact value.
- **not equals**: Excludes rows matching the specified value.
- **greater than**: Values greater than the specified number.
- **less than**: Values less than the specified number.
- **between**: Values within a specified range (e.g., `60,70`).
- **contains**: Matches substrings within text fields.

## Prerequisites

- A Google account to use Google Sheets.
- Basic knowledge of Google Apps Script and Google Sheets functionality.

## Contribution

Feel free to fork the repository and submit pull requests if you want to contribute to the project or suggest improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

- Thanks to the Google Apps Script documentation for guidance on building the add-on.
- Inspired by the need for a more efficient way to filter student data in educational environments.
