# SOC Monitoring & SIEM Threat Detection Platform

## Overview

A real-time SSH threat monitoring and security analytics platform developed using Python on Ubuntu EC2.

The system monitors Linux authentication logs, detects SSH brute-force attacks, enriches attacker data using GeoIP lookup, generates SOC-style alerts, and visualizes attack statistics through a Streamlit dashboard.

This project simulates real-world SOC monitoring and incident detection workflows.

---

## Features

- AWS EC2 Ubuntu Monitoring
- Splunk SIEM Integration
- SSH Threat Detection
- Top Attacker IP Analysis
- Threat Hunting using SPL
- Detection Engineering
- SOC Dashboard Monitoring

---

## Technologies Used

- Python
- Linux (Ubuntu)
- AWS EC2
- Streamlit
- Pandas
- Matplotlib
- Colorama

---

## Project Structure

```text
SSH-Threat-Monitor/
│
├── main.py
├── parser.py
├── alerts.py
├── dashboard.py
├── requirements.txt
├── README.md
│
├── logs/
├── reports/
│
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPO_URL
cd SSH-Threat-Monitor
```

Install dependencies:

```bash
pip3 install -r requirements.txt --break-system-packages
```

---

## Usage

Run the monitoring system:

```bash
sudo python3 main.py
```

Run dashboard:

```bash
streamlit run dashboard.py
```

---

## Sample Output

```text
[ALERT] Possible Brute Force Attack Detected from 161.129.211.56
Location: New York, United States
Failed Attempts: 442
```

---

## Screenshots

### Real-Time SSH Monitoring

Add screenshot here.

### Streamlit Dashboard

Add dashboard screenshot here.

---

## Future Improvements

- Email alert integration
- Telegram notifications
- Threat intelligence feed integration
- Docker deployment
- Real-time streaming log ingestion
- Attack trend visualization

---

## Author

mahi
