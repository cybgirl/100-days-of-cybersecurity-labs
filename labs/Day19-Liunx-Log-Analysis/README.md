# Day 19 – Deep Dive into Linux Logs 🛠️🔍

## 🧠 Overview
Today’s lab focused on **Linux log analysis** using hands-on challenges from CyberDefenders. This session highlighted how logs serve as a critical source of information for detecting threats, investigating incidents, and monitoring system activity.

---

## 🎯 Objectives
- Understand the importance of Linux logs in cybersecurity  
- Identify key log files and their purposes  
- Learn how to navigate and filter logs efficiently  
- Use command-line tools for log analysis  
- Detect suspicious activities from log data  

---

## 📚 Key Concepts Learned

### 📂 Important Linux Log Files
- **/var/log/auth.log**  
  Tracks authentication events such as login attempts and privilege usage  
  Useful for detecting brute-force attacks 🚨  

- **/var/log/syslog**  
  General system activity log for monitoring overall operations  

- **journalctl**  
  A powerful tool for querying and filtering logs by:
  - Time  
  - Service  
  - User  

---

## 🔍 Log Analysis Techniques

### 🛠️ Command-Line Tools
- `grep` – Search for specific patterns in logs  
- `awk` – Analyze and process structured data  
- `sed` – Edit and transform text streams  

---

## 🧠 Detection Insights
- Logs reveal:
  - Failed login attempts  
  - Unauthorized access  
  - Privilege escalation activity  
  - Suspicious system behavior  

- Efficient filtering helps reduce noise and focus on relevant events  

---

## 🚨 Identifying Suspicious Activity
- Indicators to watch for:
  - Multiple failed login attempts (possible brute-force attack)  
  - Unusual login times or locations  
  - Unknown users or privilege escalation  
  - Repeated or abnormal system events  

---

## 🧪 Lab Experience
- Completed the **Hammered** challenge on CyberDefenders  
- Applied log analysis techniques to investigate system activity  
- Practiced extracting meaningful insights from large log datasets  

---

## 🚀 Key Takeaways
- Linux logs are a **goldmine for threat detection**  
- Knowing log locations speeds up investigations  
- CLI tools are essential for efficient analysis  
- Log analysis is a **core skill for blue teamers**  

---

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

