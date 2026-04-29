# Security-audit-and-risk-analysis

## 📌 Overview
This project is a cybersecurity audit conducted in a controlled lab environment as part of a penetration testing practice scenario. The objective was to simulate a basic infrastructure assessment and identify potential security weaknesses.

## 🎯 Objectives
- Perform network reconnaissance and service enumeration
- Identify potential vulnerabilities in exposed services
- Evaluate authentication security
- Provide remediation and hardening recommendations

## 🛠️ Tools Used
- Nmap – network scanning and service detection
- Nessus – vulnerability assessment
- Hydra – brute-force authentication testing
- John the Ripper – password cracking analysis

## 🔍 Methodology
- Performed network enumeration using Nmap to identify open ports and services
- Ran vulnerability scans with Nessus to detect known security issues
- Tested authentication strength using Hydra against exposed services
- Analyzed password hashes using John the Ripper
- Correlated results to evaluate overall system exposure

## 🚨 Key Findings
- Multiple exposed services detected (SSH, FTP, Telnet, HTTP)
- Weak authentication policies enabling brute-force attempts
- Service misconfigurations increasing attack surface

## ⚠️ Risk Assessment
The system was classified as **high risk** in a lab scenario due to the number of exposed services and weak authentication controls.

## 🛡️ Recommendations
- Disable legacy protocols such as Telnet and FTP
- Enforce strong password policies and account lockout mechanisms
- Restrict access via firewall rules and network segmentation
- Apply regular security patches and updates

## 📄 Report
Full technical report is available in the `/report` directory.
