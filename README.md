# Snort-based Intrusion Detection System (IDS) Project

This project is a basic network-based intrusion detection system (NIDS) using Snort. It includes rules to detect suspicious network activities like SSH brute force attacks, HTTP GET requests for sensitive files, ICMP Ping Flood, port scans, and SQL injection attempts.

## Features
- SSH Brute Force Detection
- HTTP Suspicious Requests Detection
- ICMP Ping Flood Detection
- Port Scanning Detection
- SQL Injection Detection
- SSL Traffic Monitoring

## How to Use
1. Install Snort on your system.
2. Copy the `snort.conf` file to `/etc/snort/snort.conf`.
3. Copy the `local.rules` file to `/etc/snort/rules/local.rules`.
4. Run Snort using the command:
sudo snort -c /etc/snort/snort.conf -A fast

5. Monitor logs in `/var/log/snort/`.

## Requirements
- Snort 2.9.15.1 or later
- Kali Linux or any system supporting Snort

## License
This project is open-source and free to use.
