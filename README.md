# Incident Response Toolkit (Bash)

A lightweight Linux Incident Response Toolkit written in Bash for cybersecurity students, SOC analysts, blue teamers, and incident responders.

## Features

* System Information Collection
* Running Process Enumeration
* Network Connection Analysis
* Logged-in User Tracking
* Login History Collection
* Open Files Enumeration
* Cron Job Inspection
* Disk Usage Analysis
* Mounted Filesystem Discovery
* SUID File Detection
* World Writable File Detection
* Compressed Evidence Archive Generation

## Project Structure

```
Incident-Response-Toolkit/
│
├── ir_toolkit.sh
├── reports/
├── screenshots/
├── LICENSE
└── README.md
```

## Requirements

* Linux Operating System
* Bash 4+
* Root Privileges (Recommended)

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Incident-Response-Toolkit.git

cd Incident-Response-Toolkit
```

Make the script executable:

```bash
chmod +x ir_toolkit.sh
```

## Usage

Run as root for maximum visibility:

```bash
sudo ./ir_toolkit.sh
```

Example Output:

```bash
[+] Starting Incident Response Collection...
[+] Collecting system information...
[+] Collecting user information...
[+] Collecting process list...
[+] Collecting network information...
[+] Incident Response Collection Completed!
```

Generated files:

```bash
IR_Report_2026-06-24_12-00-00/
├── system_info.txt
├── logged_in_users.txt
├── processes.txt
├── network_connections.txt
├── login_history.txt
├── suid_files.txt
└── world_writable_files.txt
```

## Sample Report

The toolkit generates:

* Host Information
* User Activity
* Process Listings
* Network Connections
* Scheduled Tasks
* File System Artifacts

## Learning Objectives

This project demonstrates:

* Linux Administration
* Bash Scripting
* Incident Response
* Digital Forensics
* Threat Hunting Fundamentals
* Evidence Collection


## Author

Sunny 

Cybersecurity Enthusiast

## License

MIT License
