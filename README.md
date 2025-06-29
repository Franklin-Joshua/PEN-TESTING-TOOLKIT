🛡️ Penetration Testing Toolkit


📄 Project Description
The Penetration Testing Toolkit is a modular, Python-based command-line application designed to assist cybersecurity professionals, students, and enthusiasts in identifying and analyzing common vulnerabilities across networks and systems. This project serves as a beginner-friendly yet practical toolset for foundational penetration testing tasks and can be easily extended with new modules as needed.

The toolkit is built with a focus on simplicity, modularity, and clarity. It currently includes four major tools: a Port Scanner, FTP Brute-Force Tool, Whois Lookup, and a Subdomain Finder. Each module is self-contained, making it easy to understand, test, and upgrade. Users interact with the toolkit via a simple text-based menu, allowing them to select a tool and provide the necessary input for scanning or testing.

🔍 Features
✅ Port Scanner
This module scans a target IP address for open ports within a specified range (default: 20–1024). It helps in identifying services that are running and may be vulnerable or misconfigured.

✅ FTP Brute-Forcer
Attempts to gain unauthorized access to an FTP server by trying a set of commonly used passwords for a given username. This module demonstrates brute-force attack techniques in a safe and controlled environment.

✅ Whois Lookup
Fetches WHOIS information about a given domain name using the python-whois library. This information is useful for reconnaissance and can reveal domain registration details, contact info, and expiration dates.

✅ Subdomain Finder
Tries to identify subdomains of a given domain by sending HTTP requests to common subdomain prefixes (like mail, ftp, test, dev, etc.). Any valid responses indicate an active subdomain, which could potentially expose hidden services.

⚙️ Technologies Used
Python 3.x

Standard libraries: socket, ftplib

External libraries: requests, python-whois


📁 Project Structure
PentestToolkit/
├── main.py
├── modules/
│   ├── port_scanner.py
│   ├── ftp_bruteforce.py
│   ├── whois_lookup.py
│   └── subdomain_finder.py
└── README.md

💡 Educational Use Only
⚠️ This project is created strictly for educational and ethical testing purposes. 
Do not use this toolkit on networks or systems you do not own or have explicit permission to test. Unauthorized scanning and brute-forcing may be illegal and unethical.

📈 Future Improvements
Add threading support for faster scans.

Implement more brute-force modules (SSH, HTTP forms).

Add vulnerability detection (SQLi, XSS).

Export scan results to files (e.g., CSV, JSON).

Add a GUI version (Tkinter or PyQT).




![Screenshot 2025-06-28 232043](https://github.com/user-attachments/assets/8290a6c6-dcac-4428-9048-3231d634b34a)



![Screenshot 2025-06-28 231941](https://github.com/user-attachments/assets/f126f7de-1e44-4317-a818-46747359f1b4)



![Screenshot 2025-06-28 231932](https://github.com/user-attachments/assets/884f9a1c-67b5-45f8-a0d9-84cfe07ab034)
