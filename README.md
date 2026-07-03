# email_harvester.py
# Email Harvester (Day 2 — RECON & OS
# 📧 Email Harvester (Day 2 – RECON & OSINT)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Requests](https://img.shields.io/badge/Requests-Library-green)
![Regex](https://img.shields.io/badge/Regex-Email%20Extraction-orange)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)
![License](https://img.shields.io/badge/License-MIT-red)

## 📌 Overview

Email Harvester is a lightweight Python tool that extracts publicly available email addresses from web pages using **Regular Expressions (Regex)**.

This project was developed as part of a **Cyber Security (RECON & OSINT)** learning task to demonstrate basic web scraping, regex, and Python programming concepts.

---

## ✨ Features

- 🌐 Downloads webpage source code
- 📧 Extracts publicly available email addresses
- 🔍 Uses Regular Expressions (Regex)
- 🚀 Fast and lightweight
- 🛡 Handles network and HTTP errors
- ♻ Removes duplicate email addresses
- 📝 Clean and readable code

---

## 📁 Project Structure

```
Email-Harvester/
│── email_harvester.py
│── README.md
```

---

## 🛠 Requirements

- Python 3.x
- Requests Library

Install the required package:

```bash
pip install requests
```

---

## 🚀 Usage

Run the script:

```bash
python email_harvester.py
```

Enter the website URL when prompted:

```text
Enter website URL:
https://example.com
```

---

## 💻 Example Output

```text
Enter website URL:
https://example.com

Emails Found:
admin@example.com
info@example.com
support@example.com
```

If no email addresses are found:

```text
Enter website URL:
https://example.com

No emails found.
```

---

## ⚙️ How It Works

1. Accepts a website URL from the user.
2. Downloads the webpage using the Requests library.
3. Searches the HTML using Regular Expressions.
4. Removes duplicate email addresses.
5. Displays the extracted email addresses.

---

## 🧰 Technologies Used

- Python 3
- Requests
- Regular Expressions (Regex)

---

## 📚 Learning Objectives

This project demonstrates:

- HTTP Requests
- Regular Expressions
- Basic Web Scraping
- Error Handling
- Python Functions
- Cyber Security Reconnaissance Fundamentals

---

## ⚠️ Ethical Use

This project is intended **only for educational purposes and authorized security testing**.

- Test only websites you own or have explicit permission to assess.
- Respect website Terms of Service and applicable laws.
- Do not use this project for phishing, spam, or unauthorized data collection.

---

## 👩‍💻 Author

**Sumaiya Mohsin Rao**

Cyber Security Student

---

## 📄 License

This project is licensed under the MIT License.