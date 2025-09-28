# ELEVATE-LABS-INTERNSHIP-TASK-3:
# Basic Vulnerability Scanning:

# Overview:
This project demonstrates a basic vulnerability assessment on a Windows 11 machine using Tenable Nessus Essentials. The purpose of this task is to identify security weaknesses, understand severity levels (using CVSS), and suggest remediation steps.

# Tools Used:
-> Nessus Essentials (Free Edition)
-> Google (for research)
-> ChatGPT (for guidance and documentation)

# Objectives:
-> Understand how vulnerability scanning tools work.
-> Identify security issues in the system.
-> Learn to interpret severity scores (CVSS).
-> Suggest basic remediation steps to improve security.

# Scan Details:
Tool Used: Nessus Essentials (Free)
Scan Policy: Basic Network Scan
Target: Local system (127.0.0.1 / 172.20.x.x)
Duration: 8 minutes
Total Vulnerabilities Found: 22

# Task Steps:
1. Installed Nessus Essentials on Windows 11.
2. Updated plugin database to ensure latest vulnerability checks.
3. Configured a Basic Network Scan on 127.0.0.1 (localhost).
4. Launched the scan and waited for completion.
5. Reviewed vulnerabilities by severity (Critical, High, Medium, Low, Info).
6. Researched possible remediation methods.
7. Documented findings and solutions in the report.

# Findings: 
Medium Severity (CVSS 6.5):
   -> SSL Certificate Cannot Be Trusted
   -> Remediation: Replace with a trusted certificate from a Certificate Authority (CA).
Informational Findings:
   -> SSL Certificate Information
   -> SSL Cipher Suites Supported
   -> SSL Perfect Forward Secrecy Ciphers

(Screenshots of scan setup, progress, and results are included in the screenshots/ folder.)

# Conclusion:
The task showed how automated security tools like Nessus Essentials can detect vulnerabilities in a system. Even though no Critical or High vulnerabilities were found, the Medium severity issue highlights the importance of proper configuration. Regular scanning, patching, and system hardening are necessary to maintain a secure environment.
