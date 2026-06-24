# Secure Login System

## Project Overview

The Secure Login System is a web-based authentication application developed using Python Flask and SQLite. The project demonstrates secure user authentication by implementing password hashing, session management, input validation, and protection against common web security vulnerabilities such as SQL Injection.

The application allows users to register, log in securely, access protected content through authenticated sessions, and log out safely. Passwords are securely stored using bcrypt hashing, ensuring that plain-text passwords are never stored in the database.

---

## Objectives

* Develop a secure user authentication system.
* Implement user registration and login functionality.
* Store passwords securely using bcrypt hashing.
* Protect against SQL Injection attacks using parameterized queries.
* Implement session management for authenticated users.
* Demonstrate cybersecurity best practices in web application development.

---

## Features

### User Registration

* Create new user accounts
* Prevent duplicate usernames
* Secure password storage using bcrypt hashing

### Secure Login

* Authenticate registered users
* Verify credentials securely
* Redirect authenticated users to a protected dashboard

### Password Hashing

* Uses bcrypt hashing algorithm
* Passwords are never stored in plain text

### Session Management

* Maintains active user sessions
* Restricts dashboard access to authenticated users only

### Logout Functionality

* Securely terminates user sessions
* Redirects users back to the login page

### SQL Injection Protection

* Uses parameterized SQL queries
* Prevents malicious database manipulation

---

## Technologies Used

* Python
* Flask
* SQLite
* Flask-Bcrypt
* HTML
* CSS
* Git
* GitHub
* Visual Studio Code

---

## Project Structure

```text
Secure-Login-System
│
├── app.py
├── requirements.txt
│
├── templates
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
│
└── static
    └── style.css
```

---

## Installation and Setup

### Clone Repository

```bash
git clone https://github.com/KarunaDhende31/Secure-Login-System.git
cd Secure-Login-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

### Access Application

Open your browser and navigate to:

```text
http://127.0.0.1:5000
```

---

## How It Works

### Registration Process

1. User enters a username and password.
2. Password is hashed using bcrypt.
3. User information is stored securely in SQLite database.
4. User is redirected to the login page.

### Login Process

1. User enters credentials.
2. Application retrieves user information from database.
3. bcrypt verifies the entered password against the stored hash.
4. Upon successful authentication, a session is created.
5. User is redirected to the dashboard.

### Logout Process

1. User clicks Logout.
2. Session data is cleared.
3. User is redirected to the login page.

---

## Security Features

| Security Feature         | Description                             |
| ------------------------ | --------------------------------------- |
| Password Hashing         | Uses bcrypt to securely hash passwords  |
| SQL Injection Protection | Parameterized SQL queries               |
| Session Management       | Maintains secure authenticated sessions |
| Logout Functionality     | Secure session termination              |
| Input Validation         | Prevents invalid form submissions       |

---

## Testing Results

### Registration Test

* Successfully created new user accounts
* Verified secure password hashing

### Login Test

* Successfully authenticated registered users
* Rejected invalid credentials

### Session Test

* Verified access control for authenticated users
* Restricted unauthorized dashboard access

### Logout Test

* Successfully terminated active sessions

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Web Application Security
* Authentication Mechanisms
* Password Hashing with bcrypt
* Session Management
* SQL Injection Prevention
* Flask Web Development
* SQLite Database Integration
* Git and GitHub Version Control

---

## Future Enhancements

* Password Strength Validation
* Account Lockout After Multiple Failed Attempts
* Email Verification
* Two-Factor Authentication (2FA)
* Password Reset Functionality
* Bootstrap-based Responsive UI

---

GitHub: https://github.com/KarunaDhende31
# Secure-Login-System
