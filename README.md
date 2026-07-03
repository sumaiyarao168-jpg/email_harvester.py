# email_harvester.py
# Email Harvester (Day 2 — RECON & OSINT)

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