NAME:D BALAKUMAR
COMPANY: CODTECH IT SOLUTIONS
ID:CT4CSEH4347
DOMAIN:CYBER SECURITY&ETHICAL HACKING
DURATION:JULY 2024 TO AUGUST 2024
MENTOR: Muzammil Ahmed

##Overview of the Vulnerability Scanning Tool Project
This Python-based vulnerability scanning tool is designed to identify common security vulnerabilities in a network or website. The tool includes features such as scanning for open ports, checking for outdated software versions, identifying common misconfigurations, verifying SSL/TLS certificate details, brute forcing directories, testing for basic SQL injection vulnerabilities, and checking HTTP headers for security configurations.

Key Features
1.Open Port Scanning:

Uses nmap to scan the target for open ports within a specified range (ports 1-1024).
Identifies which ports are open and potentially vulnerable to exploitation.
Outdated Software Version Check:

Sends an HTTP request to the target and checks the Server header in the response.
Helps in identifying if the server software is outdated, which could be vulnerable to known exploits.
2.Common Misconfigurations Scan:

Checks for simple misconfigurations, such as whether the target responds to ICMP echo requests (ping).
This feature can be expanded to include additional misconfiguration checks as needed.
3.SSL/TLS Certificate Verification:

Checks the SSL/TLS certificate of the target to determine its validity and expiry date.
Warns if the certificate is expiring soon or has already expired, which could indicate a security risk.
4.Directory Brute Forcing:

Attempts to discover hidden directories and files on the target by trying a predefined list of common directory names.
Can be useful for identifying unsecured or forgotten directories that might contain sensitive information.
5.Basic SQL Injection Test:

Performs a simple SQL injection test by sending a payload to the target and checking the response for SQL error messages.
Helps in identifying basic SQL injection vulnerabilities that could allow attackers to access or manipulate the database.
6.HTTP Header Security Check:

Checks for the presence of common security-related HTTP headers such as Content-Security-Policy, X-Frame-Options, X-XSS-Protection, Strict-Transport-Security, and X-Content-Type-Options.
Ensures that these headers are correctly configured to enhance the security of the web application.
