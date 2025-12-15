# 🦢 Black Swan Antivirus — Web Utilities Edition

# URL: [https://surja15.github.io/BlackSwanWeb/](https://surja15.github.io/BlackSwanWeb/index.html)

**Black Swan Antivirus** is a lightweight, fast, and customizable cybersecurity tool built as a final-year project. It not only delivers a powerful real-time scanning engine but also includes useful web utilities like a **QR Code generator**, **secure password generator** and a **URL safety checker**, all packaged into a clean, responsive web interface.

## 🌐 Website Overview

> **"Light, dynamic, and built for precision."**

The **Black Swan web portal** serves as a security-focused toolkit for both everyday users and security professionals. It's built to showcase core cybersecurity functionalities in a user-friendly interface.

### 🔑 Key Utilities
- **🔒 Password Generator**: Create secure, complex passwords instantly.
- **🌐 URL Safety Checker**: Verify if a link is suspicious or blacklisted.
- **🛡️ QR Code Generator**: Generates QR Code from any given link using qrcode.js.

---

## 🧩 Features

### ✅ Real-Time Scanning
Continuously monitors file activity and system behavior using a lightweight scanning engine.

### 🧠 Custom Rule Support
Leverages YARA to write and apply custom rules for malware and ransomware detection.

### 🚀 Ultra-Light Performance
Runs with minimal CPU usage and no impact on user experience.

### 🗂️ File Classification
Utilizes YARA’s pattern-matching capabilities to categorize files by threat level.

---

## 🔬 Benchmark Testing

- **🧪 EICAR Virus Flagging**  
  All EICAR test files were correctly flagged, proving accurate signature detection.

- **📄 File Detection Accuracy**  
  Logs include file paths, types, and threat levels for full visibility.

- **🎯 Rule-Based Precision**  
  No false positives were recorded in custom rule evaluations.

---

## 🛠 Tech Stack

| Component      | Purpose                                   |
|----------------|-------------------------------------------|
| `C (engine.c)` | Core scanning engine, optimized for speed |
| `Python`       | GUI via Tkinter, rules parsing, I/O       |
| `YARA`         | Malware signature detection and classification |
| `HTML/CSS`     | Front-end for the Web Utilities portal    |
| `JavaScript`   | Logic for password, QR Code generation, URL check |
| `GitHub`       | Code hosting, open-source collaboration   |

---

## 🌐 Live Utilities Preview

> ⚙️ **Web Utilities Available**:
- **Password Generator**  
  Custom length, complexity toggles, copy to clipboard.

- **URL Safety Checker**  
  Real-time validation using threat intelligence APIs (if integrated) or regex-based detection for basic demos.

- **QR Code Generator**  
  Real-Time generation of QR Code from given link.
---

## 📁 Project Structure

.
├── antivirus/
│ ├── engine.c
│ ├── rules.yar
│ └── gui.py
├── web/
│ ├── index.html
│ ├── style.css
│ ├── password.js
├ ├── QRCode.js
│ └── url_checker.js
├── README.md


---

## 📦 Installation

### 🖥 Antivirus Engine
```bash
gcc engine.c -o scanner
python gui.py

# 🌐 Web Utilities
Just open index.html in a browser to use the password generator and URL checker.

🔐 License
MIT License
