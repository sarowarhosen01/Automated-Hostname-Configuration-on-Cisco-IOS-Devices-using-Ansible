# Network Automation with Ansible - Cisco Hostname Configuration

![Ansible](https://img.shields.io/badge/Ansible-EE0000.svg?style=for-the-badge&logo=ansible&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7.svg?style=for-the-badge&logo=cisco&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white)

This project demonstrates foundational **Network Automation** skills using Ansible to configure hostnames on multiple Cisco IOS devices.

---

## 📋 Project Overview

As part of my journey to become a **Network Automation Engineer**, I developed this Ansible playbook to automate hostname configuration on 4 Cisco devices (2 Routers + 2 Switches) instead of doing it manually via CLI.

This is my first major hands-on project in Network Automation.

### 🎯 Objective
- Automate hostname configuration across multiple Cisco devices
- Learn Ansible inventory management and network modules
- Build reusable automation workflows

---

## 🛠️ Lab Environment

- **Control Node**: Docker Container (Ansible installed)
- **Target Devices**: 4 Cisco IOS Devices
  - SW1 → `192.168.10.11`
  - R1  → `192.168.10.12`
  - R2  → `192.168.10.13`
  - SW2 → `192.168.10.14`

---

## 📁 Project Structure

```bash
.
├── host.ini          # Ansible Inventory File
├── hostname.yml      # Main Playbook
├── README.md
└── Screenshots       # (Optional)
