# Create Profile Form

This project is a simple HTML-based profile creation form that allows users to input their personal information, such as name, username, email, phone number, PIN, and password. The form includes client-side validation using JavaScript and regular expressions to ensure that the data entered is in the correct format.

## Features

- **Dynamic Form Validation**: The form uses regular expressions to validate:
  - **Name**: Up to 20 characters.
  - **Username**: Lowercase, up to 20 characters.
  - **Email**: Valid email format.
  - **Phone Number**: Valid Bangladeshi phone number format.
  - **PIN**: A strong 8-character PIN that includes uppercase, lowercase, special characters, and numbers.
  - **Password**: Ensures password confirmation matches.

- **Generate Strong PIN**: The form has a "Generate PIN" button that creates a secure PIN using a combination of uppercase, lowercase, special characters, and numbers.

- **Inline Error Messages**: Error messages are shown dynamically below the relevant input fields, providing immediate feedback to the user.

## Prerequisites

- Basic understanding of HTML, CSS, and JavaScript (for modifying the form).

![Alt text](img/create_profile.jpg)
![Alt text](img/create_profile_validation.jpg)
