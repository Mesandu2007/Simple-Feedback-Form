📋 Simple Feedback Form

This is a clean and responsive Feedback Form built with HTML, CSS, and JavaScript.
It collects user details such as Name, Email, Contact Number, and Message and submits them via FormSubmit
 without requiring a backend server.

🚀 Features

✅ Clean and responsive UI with hover effects

✅ Collects Name, Email, Contact Number, and Message

✅ Client-side validation (checks empty fields, valid email, numeric contact)

✅ Submits responses directly to your email using FormSubmit

✅ Lightweight – only HTML, CSS, and JavaScript

🖥️ Preview
Form Layout
Enter Name:       [_____________________]
Enter Email:      [_____________________]
Enter Contact No: [_____________________]
Enter Message:    [_____________________]

                [ Submit ]

📂 Project Structure
├── index.html   # Main feedback form page

⚙️ How It Works

Users fill out the form fields.

JavaScript validates inputs before submission:

Name, Email, Contact cannot be empty

Email must contain @

Contact must be numeric

On successful validation, the form is submitted to your email via FormSubmit.

📬 Setup Instructions

Clone this repo:

https://github.com/Mesandu2007/Simple-Feedback-Form
cd feedback-form


Open index.html in your browser.

Replace the form action email with your own:

<form action="https://formsubmit.co/your-email@example.com" method="POST">


Done ✅ – your feedback form is ready!

live Demo: https://mesandu2007.github.io/Simple-Feedback-Form/
  

🖌️ Customization

Change colors in the CSS for your theme.

Add more fields inside the <form> if needed.

Style the form further with animations or custom layouts.

📜 License

This project is licensed under the MIT License – free to use and modify
