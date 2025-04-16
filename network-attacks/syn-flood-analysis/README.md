# 🛡️ SYN Flood Attack – Incident Report

**Certificate Program:** Google Cybersecurity Professional Certificate  
**Course:** Connect and Protect: Networks and Network Security (Course 3)  
**Date Completed:** April 16, 2025

---

## 📘 Overview

This report analyzes a **SYN flood attack**, a type of Denial-of-Service (DoS) attack, that was identified in a simulated network environment. The attack involved overwhelming a web server with TCP SYN packets, preventing it from establishing valid connections with legitimate users. The goal of the exercise was to analyze the behavior in log files and describe the technical impact and response to the incident.

---

## 🔧 Skills Demonstrated

- TCP/IP model and three-way handshake analysis  
- Identification of SYN flood DoS attacks  
- Log review and pattern recognition  
- Cybersecurity incident documentation  
- Root cause and impact assessment  

---

## 📂 Files Included

- [`syn-flood-incident-report.docx`](./syn-flood-incident-report.docx): Professionally formatted incident report (Word)
- [`syn-flood-incident-report.pdf`](./syn-flood-incident-report.pdf): PDF version for easy viewing and sharing

---

## 🧠 Key Takeaways

- SYN flood attacks target server resources by leaving connections half-open, eventually overwhelming the system.
- Recognizing a high volume of SYN requests without ACK responses is a strong indicator of this type of DoS attack.
- Logs showing TCP reset (RST) and timeout (504 Gateway) errors reveal the system’s inability to respond to legitimate traffic.
- Documenting incidents with clarity helps security teams assess vulnerabilities and improve response protocols.

---

✅ *This assignment reinforces foundational skills in network security analysis and DoS mitigation strategies as part of the Google Cybersecurity Professional Certificate.*
