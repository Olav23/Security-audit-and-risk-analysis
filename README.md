# Security-audit-and-risk-analysis

## 📌 Overview
This project is a hands-on cybersecurity audit carried out in a controlled lab environment. The goal was to simulate a real-world infrastructure assessment, identify vulnerabilities, and evaluate their potential impact.

## 🎯 Objectives
- Discover exposed services and open ports
- Identify known vulnerabilities in running services
- Assess exploitation risk in a lab environment
- Provide mitigation and hardening recommendations

## 🛠️ Tools Used
- Nmap (network reconnaissance and port scanning)
- Nessus (vulnerability scanning)
- Hydra (brute-force testing)
- John the Ripper (password cracking)

## 🔍 Methodology
1. Performed network scanning using Nmap to identify active hosts and services
2. Conducted vulnerability analysis with Nessus
3. Tested authentication strength using Hydra
4. Attempted password analysis with John the Ripper
5. Correlated findings to assess overall system risk

## 🚨 Key Findings
- Exposed services detected including SSH, FTP, Telnet, and HTTP
- Weak authentication mechanisms susceptible to brute-force attacks
- Service misconfigurations potentially exposing sensitive information

## ⚠️ Risk Assessment
The target system was assessed as **high risk** due to the presence of multiple critical vulnerabilities and insecure services.

## 🛡️ Recommendations
- Disable insecure protocols such as Telnet and FTP
- Enforce strong password policies and account lockout mechanisms
- Restrict access using firewall rules
- Regularly apply security patches and updates

## 📄 Report
Full technical report is available in the `/report` directory.
