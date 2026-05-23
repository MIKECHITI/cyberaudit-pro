# CyberAudit Pro - Cybersecurity Audit Web Application

![Cybersecurity](https://img.shields.io/badge/Security-Audit-brightgreen)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-blue)
![Chart.js](https://img.shields.io/badge/Chart.js-4.0-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

**CyberAudit Pro** is a comprehensive, production-grade cybersecurity audit web application designed for security professionals, network administrators, and penetration testers. It provides a centralized platform for network security assessments, penetration testing analysis, and compliance auditing.

## 🚀 Features

### 1. Interactive Dashboard
- **Real-time Metrics**: Summary cards for total assets, critical vulnerabilities, and compliance scores.
- **Data Visualization**: Interactive charts for vulnerability breakdown, findings by category, and risk score trends.
- **Threat Level Indicator**: Dynamic status indicator based on current findings.

### 2. Network Security Assessment
- **Asset Inventory**: Manage network assets with IP, hostname, OS, and criticality tracking.
- **Port Scan Simulator**: Terminal-style interface for simulating network port scans.
- **Security Checklists**: Comprehensive checklists for Firewall, Segmentation, Wireless, DNS, and VPN security.

### 3. Penetration Testing Analysis
- **Phase Tracker**: Visual stepper for monitoring the 5 phases of a pentest engagement.
- **Finding Log**: CVSS 3.1-based finding logger with automatic severity calculation.
- **Export Tool**: Generate formatted plain-text reports for easy sharing.

### 4. Compliance & Controls
- **Framework Support**: Built-in support for CIS Controls v8, NIST CSF, ISO 27001, PCI-DSS, and HIPAA.
- **Gap Analysis**: Detailed table showing non-compliant controls and remediation steps.
- **Radar Charts**: Visual representation of compliance coverage across categories.

### 5. Report Generator
- **Executive Summary**: Professional summary builder for stakeholders.
- **Risk Matrix**: 5x5 Likelihood vs Impact grid for risk prioritization.
- **PDF Export**: Generate professional audit reports directly from the browser.

## 🛠️ Tech Stack

- **Frontend**: HTML5, Vanilla JavaScript
- **Styling**: Tailwind CSS (CDN)
- **Charts**: Chart.js (CDN)
- **Fonts**: JetBrains Mono (Google Fonts)
- **Icons**: SVG & Unicode

## 📦 Installation & Usage

Since this is a single-file application, no complex installation is required:

1. Clone the repository:
   ```bash
   git clone https://github.com/MIKECHITI/cyberaudit-pro.git
   ```
2. Open `CyberAudit_Pro.html` in any modern web browser.

## 🔒 Security Note

This application uses `localStorage` to persist data within your browser. It does not send any data to external servers, making it suitable for sensitive internal audits. However, always ensure you are using it in a secure environment.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
Developed for professional security auditing and assessment.