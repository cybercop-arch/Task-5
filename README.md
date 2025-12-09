# Task-5

# 🛡️ DVWA – OWASP Top 10 (2021) Penetration Testing Project  
**Author:** *Samiksha Ganesh Salunke*  
**Platform:** Kali Linux (Apache2 + MySQL)  
**Target:** DVWA @ http://127.0.0.1/DVWA  
**Purpose:** Cybersecurity Internship Capstone Project

---

## 📌 Project Overview

This repository contains a complete **web application penetration test** performed on the Damn Vulnerable Web Application (DVWA).  
All vulnerabilities are mapped to the **OWASP Top 10 – 2021 Edition**.

The primary goals of this project were to practice:

- Web exploitation techniques  
- Vulnerability assessment  
- Secure coding analysis  
- Incident response simulation  
- Professional security reporting  

All testing was conducted inside a **local, isolated VM environment**.

---

## 🧰 Tools Used

- Kali Linux
- Burp Suite Community Edition  
- SQLMap  
- Nmap  
- Browser Developer Tools  
- cURL  
- DVWA (Damn Vulnerable Web App)

---

## 🔎 Testing Methodology

### **1. Reconnaissance**
- Identified parameters, forms, request patterns  
- Observed server responses and error messages  
- Mapped attack surface for each DVWA module  

### **2. Vulnerability Testing**
Each OWASP Top 10 category was tested using DVWA modules and custom payloads.

### **3. Proof of Concept (PoC)**
- Executed exploits manually  
- Collected screenshots  
- Recorded request/response pairs  

### **4. Risk Scoring**
- Used CVSS 3.1  
- Labeled vulnerabilities as Low / Medium / High / Critical  

### **5. Remediation**
- Provided developer-oriented fixes  
- Included secure coding practices  
- Proposed configuration-level hardening

---

## 🔥 OWASP Top 10 (2021) Coverage

This project fully covers the OWASP 2025 categories:

| OWASP 2021 Category | Status | Severity |
|---------------------|---------|-----------|
| A01 – Broken Access Control | ✔ Exploited | High |
| A02 – Cryptographic Failures | ✔ Exploited | High |
| A03 – Injection | ✔ Exploited | **Critical** |
| A04 – Insecure Design | ✔ Observed | High |
| A05 – Security Misconfigurations | ✔ Exploited | Medium |
| A06 – Vulnerable & Outdated Components | ✔ Observed | Medium |
| A07 – Identification & Authentication Failures | ✔ Exploited | High |
| A08 – Software & Data Integrity Failures | ✔ Exploited | **Critical** |
| A09 – Logging & Monitoring Failures | ✔ Observed | Medium |
| A10 – Server-Side Request Forgery (SSRF) | ✔ Exploited | High |

---

## 📄 Deliverables Included

### ✔ **Professional Penetration Test Report (PDF)**  
Includes:
- Executive summary  
- Methodology  
- Detailed findings  
- Screenshots  
- CVSS scoring  
- Mitigation strategies  

### ✔ **Payloads & Commands**  
All necessary SQLi, XSS, LFI, brute-force, SSRF, and upload exploitation payloads.


