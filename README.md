# email_harvester.py
# Email Harvester (Day 2 — RECON & OSINT)

An ethical OSINT (Open-Source Intelligence) Python script designed to scrape email addresses from a target website using regular expressions (regex). This project is part of the Week 1 (Recon & OSINT) cyber security learning journey as shown in `Screenshot_20260629-163041.jpg`.

## 📌 Objective
The goal of this script is to understand how attackers collect public-facing email addresses from web sources for target profiling and building pretexting frameworks in social engineering campaigns.

> ⚠️ **Disclaimer / Ethics Boundary:** This tool is strictly for educational purposes and authorized penetration testing. Only target domains/websites that you own or have explicit written permission to test.

---

## 🛠️ Features
* Fetches HTML content from a specified URL securely with a timeout limit.
* Uses targeted Regular Expressions (Regex) to extract email addresses.
* Filters out duplicates automatically using Python `sets`.

---

## 🚀 How It Works
The script sends an HTTP `GET` request to the target domain, retrieves the raw HTML structure, and parses it via a regular expression to match standard email structures:
`[\w.+-]+@[\w-]+\.[a-zA-Z]{2,}`

---

## 📋 Prerequisites & Installation

### 1. Requirements
This script utilizes Python 3 standard libraries, along with the `requests` library for handling HTTP interactions.

### 2. Setup
Clone this repository and install the required dependency:

```bash
# Clone the repository
git clone [https://github.com/your-username/email-harvester.git](https://github.com/your-username/email-harvester.git)
cd email-harvester

# Install required packages
pip install requests
📧 Email Harvester

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Requests-Library-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Regex-Email%20Extraction-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Stable-brightgreen?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge">
</p><p align="center">
  <b>A lightweight Python tool to extract publicly available email addresses from web pages using Regular Expressions.</b>
</p>---

⚡ Features

- 🌐 Fetches webpage source code
- 📧 Extracts publicly available email addresses
- 🔍 Uses Regular Expressions (Regex)
- 🚀 Fast and lightweight
- 🛡️ Basic exception handling
- ♻️ Automatically removes duplicate emails

---

📂 Project Structure

Email-Harvester/
│── email_harvester.py
│── README.md

---

🛠 Requirements

- Python 3.x
- Requests

Install dependencies:

pip install requests

---

🚀 Usage

Clone the repository:

git clone https://github.com/your-username/email-harvester.git

Move into the project directory:

cd email-harvester

Edit the target URL:

target_url = "http://example.com"

Run the script:

python email_harvester.py

---

💻 Example Output

[+] Harvesting emails from: http://example.com
----------------------------------------
[+] Found 3 email(s):
 -> admin@example.com
 -> info@example.com
 -> support@example.com

---

⚙️ How It Works

Target URL
     │
     ▼
Download HTML
     │
     ▼
Regex Email Search
     │
     ▼
Remove Duplicates
     │
     ▼
Display Results

---

🧰 Built With

- 🐍 Python
- 🌐 Requests
- 🔎 Regular Expressions (Regex)

---

🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a Pull Request.

---

📜 License

This project is licensed under the MIT License.

---

⚠️ Disclaimer

This project is intended only for educational purposes and authorized security testing.

- Only scan websites that you own or have explicit permission to test.
- Respect website terms of service and applicable laws.
- The author is not responsible for any misuse of this project.

---

<p align="center">
  ⭐ If you found this project useful, consider giving it a star!
</p>