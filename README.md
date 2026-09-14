# Metasploitable2(DVWA), WSL and Wazuh Security Assessment

## About the Project

This project is a security assessment performed in a controlled lab environment. 
The main target used for testing was Metasploitable2 with DVWA, and Wazuh was used for security monitoring and log analysis.

## Objective

The main objectives of this project were:

- Identify open ports and services using Nmap.
- Test common vulnerabilities in DVWA.
- Perform controlled brute force attacks on FTP and SSH ports.
- Collect screenshots and log evidence for the attacks.
- Monitor security-related logs using Wazuh.
- Understand how attacks can affect the security of a system.
- Provide security recommendations based on the findings.

## Lab Environment

- Metasploitable2
- DVWA
- Wazuh
- Docker
- VirtualBox
- WSL Ubuntu
- Nmap

## Attacks and Tests Performed

The following tests were performed during the assessment:

1. Nmap Reconnaissance
2. DVWA Brute Force
3. SQL Injection
4. Stored XSS
5. Command Injection
6. FTP Brute Force
7. SSH Brute Force
8. File Upload
9. CSRF
10. File Inclusion
11. Reflected XSS
12. Blind SQL Injection

## Evidence

The `Attack-Evidence` folder contains the screenshots and text files collected during the testing.

Each attack has its own folder so that the evidence can be easily checked.

## Project Report

The complete details of the assessment, findings, evidence, risks and recommendations are available in the project report.

[View Project Report](./Project-Report.pdf)

## Security Recommendations

Some of the main recommendations from the assessment are:

- Use strong passwords and limit repeated login attempts.
- Use proper input validation for web applications.
- Use parameterized queries to prevent SQL injection.
- Properly filter user input and encode output to prevent XSS.
- Avoid unsafe command execution from user input.
- Keep FTP and SSH services properly secured.
- Monitor important system and application logs using a security monitoring solution.

## Disclaimer

All testing in this project was performed only in a controlled lab environment for educational and security assessment purposes.
