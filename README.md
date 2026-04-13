# 🔐 PassGuard – Password Strength Checker

PassGuard is a simple and interactive Flask-based web application that evaluates password strength using rule-based validation. It provides real-time feedback to help users create secure passwords.

---

## 🚀 Live Demo

👉 https://passguard-cmlm.onrender.com

---

## 📌 Features

* Validates passwords based on 5 security criteria:

  * Minimum 8 characters
  * At least one uppercase letter
  * At least one lowercase letter
  * At least one digit
  * At least one special character
* Computes a strength score
* Categorizes passwords into:

  * Weak
  * Medium
  * Strong
* Simple and clean web interface using Flask

---

## 🛠️ Tech Stack

* Backend: Python, Flask
* Frontend: HTML, CSS
* Version Control: Git, GitHub
* Deployment: Render

---

## ⚙️ How It Works

1. User enters a password in the input field
2. Backend uses regular expressions to validate criteria
3. A score is calculated based on conditions met
4. Password is classified as Weak, Medium, or Strong
5. Result is displayed instantly on the web interface

---

## 🧪 Run Locally

1. Clone the repository
   git clone https://github.com/Neo-04/PassGuard.git
   cd PassGuard

2. Install dependencies
   pip install -r requirements.txt

3. Run the app
   python app.py

4. Open in browser
   http://localhost:5000
