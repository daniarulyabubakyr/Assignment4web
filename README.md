# Assignment #4 — Forms and Validation

## Project Description

This project was developed as part of the Front-End Development course.

The main objective is to practice creating HTML forms, applying HTML5 validation, styling forms with Bootstrap 5, and displaying validation feedback messages.

The project consists of five tasks, each implemented on a separate HTML page.

## Technologies Used

- **HTML5** — Creating forms and page structure
- **CSS3** — Custom styling
- **Bootstrap 5** — Responsive layout and form styling


JavaScript code is included directly in the relevant HTML files using `<script>` tags. No separate `script.js` file is required.

## Project Structure

```text
Assignment4web/
├── index.html
├── validation.html
├── bootstrap-form.html
├── bootstrap-validation.html
├── registration.html
├── bootstrap.css
├── style.css
└── README.md
```

## Assignment Tasks

### Task 0 — Simple Contact Form

A basic HTML contact form containing Name, Email, Message, and a Submit button.

### Task 1 — HTML5 Validation

A contact form with built-in HTML5 validation using `required`, `type="email"`, `minlength`, and `maxlength`.

### Task 2 — Bootstrap Form Styling

A responsive contact form styled with Bootstrap Grid, form controls, placeholders, and helper text.

### Task 3 — Bootstrap Validation Styles

A contact form with validation feedback:

- `is-valid` — Green border for valid input
- `is-invalid` — Red border for invalid input
- `valid-feedback` — Success messages
- `invalid-feedback` — Error messages

JavaScript checks input validity directly within the HTML page.

### Task 4 — Registration Form

A responsive registration form containing:

- First Name and Last Name
- Email Address
- Password and Confirm Password
- Gender (Radio Buttons)
- Hobbies (Checkboxes)
- Country (Dropdown)
- Register and Reset Buttons

The form includes HTML5 validation, Bootstrap validation feedback, and JavaScript password confirmation.

## Navigation

A Bootstrap navigation bar connects all five task pages, allowing users to switch between them.

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Use the navigation bar to access the different tasks.

No additional installation is required because Bootstrap CSS is included locally.

