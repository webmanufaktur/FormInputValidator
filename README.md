# ProcessWire Form Validation API Module (pre-Alpha)

## Description

This ProcessWire module provides a robust API for validating form inputs of various types (e.g., email, passwords, etc.) and delivering feedback in multiple formats. It is designed to seamlessly integrate with modern JavaScript frameworks and libraries, allowing developers to build dynamic and responsive forms with ease.

### Key Features:

- **Input Validation**: Validate form inputs on the server side for security and accuracy.
- **Feedback Rendering**: Return validation feedback in the following formats based on configuration:
  - Rendered HTML
  - PHP
  - Twig
  - Latte
- **AJAX Integration**: Supports dynamic form validation via:
  - HTMX
  - Alpine.js AJAX
  - Vanilla JavaScript AJAX
- **Customizable Configuration**: Easily configure the output format and validation rules through the module settings.
- **Real-time Feedback**: Enable instant feedback for users as they interact with forms.

## How It Works

1. **API Endpoints**: The module creates API endpoints for validating specific input fields or entire forms.
2. **Request Handling**: Accepts AJAX requests from HTMX, Alpine.js, or Vanilla JavaScript.
3. **Validation Logic**: Processes input validation on the server side using customizable rules.
4. **Response**: Returns validation results in the configured format, ready to be displayed dynamically in the frontend.

## Example Use Cases:

- Validate email addresses for proper formatting and uniqueness.
- Check password strength and enforce security policies.
- Provide real-time feedback on form fields using HTMX or Alpine.js.

This module is ideal for developers looking to enhance their ProcessWire projects with flexible and modern form validation capabilities.
