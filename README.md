# Student Registration Form

## Description
The Student Registration Form is a simple web-based application developed using HTML, CSS, and JavaScript. It allows students to enter their personal details and upload their academic certificates.

The project uses JavaScript form validation to ensure that all required information is entered correctly before registration is considered successful.

## Features
- **Full Name:** Accepts letters and spaces only.
- **Date of Birth:** Requires a valid date that is not in the future.
- **Mobile Number:** Requires exactly 10 digits.
- **Password:** Requires a minimum of 8 characters.
- **Certificate Upload:** Allows PDF, JPG, JPEG, and PNG files.
- **Form Validation:** Displays error messages when information is missing or invalid.
- **Success Message:** Displays a confirmation when all fields pass validation.

## Technologies Used
- **HTML5** – Creates the registration form structure.
- **CSS3** – Handles styling, layout, colors, and input appearance.
- **JavaScript** – Performs form validation and handles submission.

## How to Run
1. Download or clone the project.
2. Locate the `index.html` file.
3. Open the file using a web browser such as Google Chrome or Microsoft Edge.
4. Fill in all the required fields.
5. Upload a certificate.
6. Click the **Submit** button to validate the information.

## Project Structure
```text
Student-Registration/
│
└── index.html
```

## Note
This project performs client-side validation only. It does not store student information or upload certificates to a server. The success message indicates that the entered information has passed the validation checks.

## Author
Developed as a web development practice project.
