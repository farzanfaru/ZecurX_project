# 🔐 Web Vulnerability Scanner

## 📌 Overview

This project is a Python-based web vulnerability scanner developed as part of a penetration testing internship.
The tool is designed to identify common web vulnerabilities in a controlled lab environment.

---

## ⚙️ Requirements

* Python 3 installed
* Internet connection

---

## 📦 Installation

1. Download or clone the project files
2. Navigate to the project folder
3. Install required library:

pip install requests

---

## ▶️ How to Run the Tool

1. Open terminal
2. Navigate to tool directory:

cd tool

3. Run the script:

python3 advanced_scanner.py

---

## 🌐 Input Format

Enter a target URL when prompted.

👉 The URL should contain a parameter for testing.

### Examples:

http://localhost/DVWA/vulnerabilities/xss_r/?name=
http://localhost/DVWA/vulnerabilities/sqli/?id=
http://testphp.vulnweb.com/listproducts.php?cat=

---

## 🔍 Features

* Directory scanning
* Cross-Site Scripting (XSS) testing
* SQL Injection testing
* Displays successful payloads
* Generates summary output

---

## 📊 Output

The tool provides:

* List of discovered directories
* Successful XSS payloads
* Successful SQL injection payloads
* Final summary report

---

## ⚠️ Limitations

* Does not handle login/session-based applications
* Limited support for modern JavaScript-based websites
* Works best with simple parameter-based URLs

---

## ⚠️ Disclaimer

This tool is developed for educational purposes only.
Testing must be performed only on authorized environments such as DVWA or other vulnerable test applications.
