<div align="center">

# 🛡️ Python Honeypot

### A Flask-based Honeypot for Security Monitoring and Threat Analysis

<p>

A cybersecurity project that simulates a login system to monitor suspicious login attempts, capture attacker metadata, and record security events for analysis. The project demonstrates the fundamentals of defensive cybersecurity through a lightweight Python and Flask implementation.

</p>

<p>

<img src="https://img.shields.io/badge/Python-3.11-blue?logo=python">
<img src="https://img.shields.io/badge/Flask-Web%20Application-black?logo=flask">
<img src="https://img.shields.io/badge/Cybersecurity-Honeypot-red">
<img src="https://img.shields.io/badge/License-MIT-green">

</p>

</div>

---

# 📌 Overview

Traditional honeypots help organizations understand malicious behavior without exposing production systems.

This project implements a lightweight Flask-based honeypot that simulates a login portal, records suspicious login attempts, captures attacker information, and stores security logs for later analysis.

The objective is to demonstrate defensive cybersecurity concepts such as attack monitoring, intrusion awareness, and security event collection.

---

# ✨ Features

## 🔐 Secure Login Simulation

- Simulated authentication portal
- Login attempt tracking
- Session management
- Failed login detection

---

## 🛡 Honeypot Monitoring

- Detect repeated failed login attempts
- Trigger honeypot monitoring after configurable threshold
- Capture attacker metadata
- Store security logs

---

## 🌐 Threat Intelligence

- IP Address Collection
- Geolocation Lookup
- Timestamp Logging
- Security Event Recording

---

## 📷 Monitoring Features

- Screenshot capture
- Activity logging
- Structured JSON storage
- Login history

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Language | Python |
| Backend | Flask |
| Data Storage | JSON |
| Security | Hashing, Session Tracking |
| Utilities | IP Lookup, Logging |

---

# 🏗 System Workflow

```text
User Login

↓

Authentication Check

↓

Successful Login
        │
        │
        ▼

Failed Login Counter

↓

Threshold Reached

↓

Honeypot Activated

↓

IP Collection

↓

Security Event Logging

↓

Screenshot Capture

↓

Store Logs
```

---

# 📂 Project Structure

```text
Python-Honeypot/

├── app.py
├── start_logging.py
├── keylogger.py
├── CaptureImage.py
├── save_ip_info.py
├── HashConversion.py
├── data.json
├── log.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone <repository-url>

cd Python-Honeypot
```

Create virtual environment

```bash
python -m venv venv
```

Activate environment

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install flask
```

Run the application

```bash
python app.py
```

---

# 💻 How It Works

1. User opens the login page.
2. Credentials are validated.
3. Failed login attempts are counted.
4. After multiple failed attempts, the honeypot is triggered.
5. The application records:

- IP Address
- Location Information
- Login Timestamp
- Security Logs
- Monitoring Data

6. Logs are stored for later analysis.

---

# 📊 Security Features

- Login Monitoring
- Failed Login Detection
- Session Tracking
- IP Address Logging
- Geolocation Collection
- Screenshot Capture
- JSON-based Event Storage

---

# 📈 Future Improvements

- SQLite/PostgreSQL logging
- Interactive security dashboard
- Email alerts
- Admin panel
- Docker deployment
- Threat intelligence integration
- Real-time monitoring
- SIEM integration

---

# 👥 Project Contributions

This project was developed collaboratively by **Preksha Dewoolkar** and **Chirag Patankar**.

## 👩‍💻 Preksha Dewoolkar

- Developed significant portions of the Flask web interface.
- Contributed to backend workflows and login simulation.
- Implemented security event logging and monitoring features.
- Assisted with testing, debugging, and improving the overall user experience.
- Collaborated on project architecture and feature integration.

---

## 👨‍💻 Chirag Patankar

- Contributed to backend development and honeypot implementation.
- Worked on logging mechanisms, security utilities, and monitoring scripts.
- Assisted with data collection, application logic, and testing.
- Collaborated on integration and project optimization.

> **This was a collaborative cybersecurity project where both contributors worked across the backend, security logic, and application development, with responsibilities overlapping throughout implementation.**

---

# 📄 License

MIT License

---

<div align="center">

## ⭐ If you found this project useful, consider giving it a star!

Built with ❤️ using Python & Flask

</div>

### **Image Capture:**

![](/images/11.jpg)

