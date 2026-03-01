# 🔐 Random Password Generator - Flask Web App

A simple and secure Random Password Generator built using **Python** and **Flask**.  
This web application runs locally on **localhost** and allows users to generate strong passwords of customizable length.

---

## 🚀 Features

- 🔢 User-defined password length
- 🔐 Generates strong random passwords
- 🔤 Includes uppercase and lowercase letters
- 🔢 Includes numbers
- 🔣 Includes special characters
- 🌐 Runs in web browser (localhost)
- ⚡ Simple and beginner-friendly project

---

## 🛠 Technologies Used

- Python 3.x
- Flask
- HTML
- CSS
- Jinja2 Templating

---

## 📂 Project Structure



password_generator_web/
│── app.py
│── README.md
└── templates/
└── index.html




---

## 🎯 How It Works

1. Enter the desired password length.
2. Click **Generate**.
3. The application creates a random password using:
   - Letters (A–Z, a–z)
   - Numbers (0–9)
   - Special characters (!@#$%^&*)
4. The generated password is displayed on the screen.

---

## 🧠 Backend Logic

- Uses Python's `random` and `string` modules.
- Combines:
  - `string.ascii_letters`
  - `string.digits`
  - `string.punctuation`
- Randomly selects characters based on user-defined length.

Generate strong passwords and stay secure! 🔒

---
