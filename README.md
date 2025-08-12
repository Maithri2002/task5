# Contact Form with JavaScript Validation

## 📌 Objective
Build a responsive contact form with **client-side validation** for Name, Email, and Message fields using HTML, CSS, and JavaScript.

## 🛠 Tools Used
- **VS Code** (Editor)
- **Chrome Browser** (Testing)
- HTML5
- CSS3
- JavaScript (Vanilla JS)

## 🎯 Features
- Responsive, clean contact form UI.
- Validation for:
  - Name (required)
  - Email (required + valid format using regex)
  - Message (required)
- Error messages displayed below each field.
- Prevents form submission if inputs are invalid.
- Success message shown on valid submission.
- Handles edge cases: empty fields, invalid emails, special characters.
- No backend — purely client-side demo.

## 📂 Project Structure
project-folder/
│
├── index.html # Main form HTML + CSS + JS
└── README.md # Project documentation

markdown
Copy
Edit

## 🚀 How to Run
1. Clone or download this repository.
2. Open the `index.html` file in your browser.
3. Fill out the form and click **Submit** to see validation in action.

## 📜 Validation Rules
- **Name**: Cannot be empty.
- **Email**: Must be in valid format (`example@domain.com`).
- **Message**: Cannot be empty.

## 🔍 Regex for Email
```javascript
const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
