![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Last Commit](https://img.shields.io/github/last-commit/DecryptMike/DecryptMike-Password-Manager)
![License](https://img.shields.io/github/license/DecryptMike/DecryptMike-Password-Manager)
![Flask](https://img.shields.io/badge/Flask-2.3+-informational?logo=flask)
![Real-Time](https://img.shields.io/badge/Feature-Real--Time%20Dashboard-green)

<p align="center">
  <img src="DecryptMikeLogo.png" alt="DecryptMike Logo" style="max-width: 100%; height: auto;"/>
</p>

<h2 align="center">
    📊 Log Analyzer with Real-Time Threat Detection
</h2>

---

## 🛠️ Features

- ✅ Detects brute-force login attempts
- ✅ Identifies suspicious IP activity
- ✅ Flags directory traversal attacks
- ✅ Real-time dashboard using Flask
- ✅ Color-coded terminal alerts
- ✅ Simulated attacker log entries

---

## 📸 Screenshot

<p align="center">
  <img src="Decrypt Mike Threat Log Streams.gif" width="80%" alt="Log Analyzer in Action">
</p>

--- 

## 🧱 Project Structure

```
log-analyzer/
├── logs/
│   └── test.log
├── templates/
│   └── index.html
├── static/
│   └── DecryptMikeLogo.png
├── analyzer.py
├── dashboard.py
├── simulator.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Tech Stack

```bash
Python 3.11
Flask
Colorama
HTML/CSS (for dashboard)
```

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/DecryptMike/Log-Analyzer-Threat-Detection.git
cd log-analyzer
```

### 2. Set Up Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Start the Real-Time Dashboard

```bash
python dashboard.py
```

Visit: `http://127.0.0.1:5000`

### 5. Simulate Attack Log Entries

In a separate terminal tab:

```bash
python simulator.py
```

---

## 📄 Why I Built It

This project was built to showcase real-world cybersecurity monitoring skills. It simulates a functioning honeypot that detects and logs threats in real time while displaying them on a visual dashboard.

---

## ⚠️ Legal Disclaimer

This tool is intended for **educational and authorized personal use only**.  
Do not use it to store sensitive or production passwords without enhancements.

---

## 💻 Built by [@DecryptMike](https://github.com/DecryptMike)

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20for-Cybersecurity-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Made%20By-DecryptMike-limegreen?style=for-the-badge&logo=github"/>
</p>
