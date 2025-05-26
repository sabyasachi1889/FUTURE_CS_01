# Security Testing Demo: SQL Injection, XSS, and Authentication Flaws

This project is a simple web application demonstration designed to showcase common web security vulnerabilities such as **SQL Injection**, **Cross-Site Scripting (XSS)**, and **Authentication Flaws**. It also provides automated test functions to simulate attacks and detect these issues right in the browser.

---

## Features

### 1. Simulated SQL Injection Vulnerable Search
- A search input that looks up users by name.
- Vulnerable to SQL injection via naive string matching.
- Includes a test button that runs common SQL injection payloads to detect vulnerability.

### 2. Stored Cross-Site Scripting (XSS) Vulnerability
- A comment posting area that stores and displays user comments without sanitization.
- Vulnerable to stored XSS attacks.
- Includes a test button that posts an XSS payload automatically to check for script execution.

### 3. Authentication Flaws Demo
- A basic login form with hardcoded credentials.
- Weak password usage demonstration.
- No account lockout or throttling (brute-force vulnerability).
- Includes a test button that simulates weak password detection and brute force attempts.

---

## How to Use

1. Download or clone this repository.
2. Open the `security_testing_demo.html` file in any modern web browser.
3. Explore each section:
   - Perform manual inputs and observe vulnerable behavior.
   - Use the **Test** buttons to run automated vulnerability tests.
4. View test results in the output areas below each test button.

---

## Technical Details

- Fully frontend implementation; all functionality is contained in a single, self-contained HTML file.
- No backend or server required.
- Vulnerabilities and tests are simulated using JavaScript for educational purposes.
- Designed for demo and learning only; **do not use in production**.

---

## Why This Is Useful

- Understand how SQL injection, XSS, and authentication flaws look in practice.
- Learn how automated testing can detect common vulnerabilities.
- Use as a base for security training or demoing attack vectors safely.

---

## Disclaimer

This demonstration is intentionally vulnerable for educational and testing purposes. Always follow secure coding practices and use proper validation, sanitization, and authentication mechanisms in real applications.

---

## License

This project is released under the MIT License.

---

Feel free to contribute improvements or suggest additional security tests!

