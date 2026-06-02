# Secure Coding Review and Vulnerability Assessment

## Project Overview
This project was developed as part of the CodeAlpha Cyber Security Internship. The main objective of this project is to identify security vulnerabilities in insecure source code and implement secure coding practices to improve application security.

## Objective
- Identify security vulnerabilities in code
- Understand risks caused by insecure coding
- Implement secure authentication techniques
- Compare vulnerable and secure coding methods

## Technologies Used
- Python
- Kali Linux
- Terminal / Command Line Interface
- Secure Coding Practices

## Project Files
- `vulnerable_login.py` – Insecure login system with vulnerabilities
- `secure_login.py` – Improved secure login system using password hashing
- `report.pdf` – Project documentation
- `screenshots/` – Output screenshots

## Vulnerabilities Identified
### 1. Hardcoded Credentials
Username and password are directly stored in source code.

**Risk:** Credential exposure

**Solution:** Use secure storage methods.

### 2. Plain Text Password
Passwords are stored in readable format.

**Risk:** Easy password theft

**Solution:** Use password hashing (SHA-256).

### 3. Weak Authentication
Simple login validation is used.

**Risk:** Unauthorized access

**Solution:** Improve authentication logic.

### 4. No Input Validation
User input is accepted without checks.

**Risk:** Security vulnerabilities

**Solution:** Validate and sanitize inputs.

## Security Improvements
- Implemented SHA-256 password hashing
- Improved password security
- Better authentication handling
- Reduced credential exposure

## Learning Outcome
Through this project, I learned:
- Secure coding best practices
- Vulnerability assessment
- Password hashing concepts
- Authentication security
- Application security improvement techniques

## Internship
CodeAlpha Cyber Security Internship# CodeAlpha_SecureCodingReview
