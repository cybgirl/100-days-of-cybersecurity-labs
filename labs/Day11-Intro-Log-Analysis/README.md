# Day 11 – Introduction to Log Analysis 

## 🧠 Overview
Today’s lab focused on Log analysis. exploring how logs paly crucial role in detecting threats, troubleshooting incidents, and strengthening security defenses.


---

## 🎯Objectives
- Understand the importance of log analysis in cybersecurity
- Identify key components of log files
- learn where logs are stored on Linux systems
- Use command-line tools to analyze logs 
- Detect suspicious patterns and attack indicators

---

## 📚 Key Concepts Learned 
### Log file Components 
- Log files typically contain:
  - Timestamps- When the event occurred 
  - IP Addresses - Source or Destination of traffic
  - Request Methods - e.g, GET, POST
  - File Hashes and Domains - Indicators of compromise 
  - Status Codes - Response from the server

---

## 📂 Common Log Locations (Linux)
- Understanding log locations is essential for investigation:
  - /var/log/nginx/access.log – Nginx web server logs
  - /var/log/apache2/access.log – Apache web server logs
  - /var/log/syslog – General system activity logs

---

##🔍 Log Analysis Techniques
### 🛠️ Command-Line Tools
- grep – Search for specific patterns
- cut – Extract specific fields
- awk – Process and analyze structured data

### 🧠 Detection Engineering
- Identifying common attack patterns
- Recognizing known signatures
- Locating relevant logs quickly for investigation

---

## 🚨 Identifying Suspicious Activity
- Examples of anomalies in log:
  - Unauthorized access attempts
  - Repeated failed login requests
  - Unusual IP activity
  - Base64-encoded payloads (often used to obfuscate attacks)

---
## 🧰 Tools for Log Analysis
- Regular Expressions (Regex) – Pattern matching
- CyberChef – Data decoding and transformation
- YARA – Malware pattern detection
- Sigma – SIEM rule creation and threat detection

---

## 🚀 Key Takeaways
- Logs don’t lie. Every action leaves a footprint.
- Mastering log analysis is essential for incident response, threat detection, and digital forensic.

---

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

