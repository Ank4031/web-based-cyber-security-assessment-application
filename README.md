# web-based-cyber-security-assessment-application

A Web-Based Cybersecurity Assessment Application is designed to help users analyze and secure their networks by identifying active hosts, detecting open ports, and performing packet sniffing. Built using Flask and Python, this application provides a user-friendly web interface for conducting essential network security assessments.

Features:
Active Host Discovery:
The tool scans the network to identify live devices, helping users detect unauthorized or potentially malicious systems.

Port Scanning:
It checks for open ports on detected hosts, which can indicate services running on a machine. Open ports can be entry points for attackers, making it crucial to identify and secure them.

Packet Sniffing:
The application captures and analyzes network packets to monitor data traffic. Packet sniffing helps in detecting suspicious activities, unauthorized data transfers, and potential security breaches.

Key Concepts:
Ports: Ports are virtual communication endpoints used by devices to send and receive data. Some common ports include HTTP (80), HTTPS (443), SSH (22), and FTP (21). Attackers often target open ports to exploit vulnerabilities.

Packet Sniffing: This process involves capturing network packets to inspect transmitted data. It helps in analyzing network traffic, detecting intrusions, and identifying vulnerabilities.

Technology Stack:
Flask (Python) – For developing the web interface and handling requests.
Scapy & Socket – For network scanning and packet sniffing.
Python-Nmap – To perform host and port discovery.
This tool is ideal for penetration testers, cybersecurity analysts, and network administrators looking to enhance security by assessing network vulnerabilities in a streamlined and interactive way.
