# 📧 Phishing Email Detection & Awareness Report

**Author:** Mokshagna  
**Program:** Future Interns — Cybersecurity Internship Task 2  
**Date:** May 2026  

## 📋 About This Assessment
This repository documents the analysis of three real-world-style phishing email samples impersonating major global brands (Bank of America, PayPal, and Microsoft 365). The project focuses on email header analysis, domain verification, and establishing actionable awareness guidelines to prevent credential harvesting and financial fraud.

## 🛠️ Tools Used
* Google Admin Toolbox (Email header analysis: SPF, DKIM, DMARC)
* WHOIS Lookup (Domain registration verification)
* VirusTotal (URL and link safety checking)

## 📊 Key Findings
* All three samples failed standard SPF, DKIM, and DMARC authentication checks.
* The analysis detected the use of known phishing tools (PhishKit v2.3) in the email headers.
* Two out of the three sender domains were completely unregistered and available for purchase, confirming they were fabricated for fraud.
* Identified common social engineering tactics, including extreme urgency and fear-based manipulation.

## 📁 Repository Contents
* `report.pdf` — The complete 14-page Phishing Awareness Report including "Do's and Don'ts" for employees.
* `evidence/` — Screenshots of header analysis results and WHOIS domain lookups.
