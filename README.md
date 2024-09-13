# RegEx Form Validation

This project is a simple user registration form that validates input fields using regular expressions (RegEx). It ensures that the user provides valid information for the username, email, password, and mobile number fields. The validation is visually represented by changing the border color of input fields based on the validity of the input.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [How to Use](#how-to-use)

## Features
- **Username Validation:** Ensures that the username is between 5 to 12 characters long.
- **Email Validation:** Verifies that the email address follows a standard format (e.g., hello@mydomain.com).
- **Password Validation:** Enforces password rules, ensuring it is alphanumeric with optional special characters (`@`, `_`, `-`) and between 8 to 25 characters long.
- **Mobile Number Validation:** Checks for a valid 10-digit mobile number.
- **Real-time Feedback:** Displays feedback as users type in each input field, highlighting valid or invalid entries using different border colors.

## Technologies Used
- HTML5
- CSS3
- JavaScript (for real-time input validation)

## File Structure

 - index.html
 - styles.css
 - script.js
 - css

### `index.html`
This file contains the structure of the form and links the CSS and JavaScript files.

### `styles.css`
This file styles the form and inputs, and defines the visual feedback for valid and invalid inputs.

### `script.js`
This file contains the validation logic, using RegEx patterns to check the user's input and applying appropriate styles based on validity.

## How to Use
1. Clone or download this repository.
2. Open the `index.html` file in a web browser.
3. Fill out the form fields, and the form will provide real-time validation feedback.
