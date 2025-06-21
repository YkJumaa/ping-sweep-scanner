# 🛜 Network Ping Sweep Tool

A lightweight Python tool built by **AJ**, a Computer Science student with a passion for cybersecurity and networking. This project scans your local network to identify which devices are online—simple, clean, and efficient. Designed as part of my personal skills growth journey toward becoming a top-tier networking engineer and cybersecurity analyst.

## 🚀 What It Does

- Scans all IPs in a `/24` subnet (like `192.168.1.0/24`)
- Identifies active hosts by pinging each IP
- Multithreaded for faster results
- Clean CLI output
- Optional: Saves active hosts to a text file

## 🧰 Built With

- 🐍 Python 3
- `ipaddress` – for IP/subnet logic
- `subprocess` – to execute system-level pings
- `concurrent.futures` – for threading

---

## 🔧 Setup Instructions

### Requirements

- Python 3.x installed
- Basic terminal/command line knowledge
- You know, brainpower 💪🏽

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ping-sweep-tool.git
   cd ping-sweep-tool

