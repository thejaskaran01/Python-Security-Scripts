# Python-Security-Scripts
A collection of Python scripts for automating basic security tasks.
1. log_analyzer.py
Purpose: Parses a sample log file (e.g., from a firewall or web server) to identify suspicious activity.
Features:

Counts failed SSH login attempts per IP address.

Flags IPs with more than 5 failed attempts as potential threats.

Outputs a simple report.
Usage: python3 log_analyzer.py sample_log.txt

2. port_scanner.py
Purpose: A simple TCP port scanner to check for open ports on a target host.
Features:

Scans a range of ports specified by the user.

Uses threading to speed up the process.
Usage: python3 port_scanner.py --target 192.168.1.1 --ports 1-100

Prerequisites
Python 3.x

No external libraries required for basic functionality (uses socket and threading).
