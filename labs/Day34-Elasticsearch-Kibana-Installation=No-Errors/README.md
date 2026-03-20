# Day 34 – Troubleshooting Elasticsearch & Kibana 🔍

## 🧠 Overview
Today, I revisited Elastic Stack (Elasticsearch & Kibana) after upgrading my RAM. Initially, everything was running smoothly, but I encountered a new challenge: I couldn’t log in because my previous password no longer worked.

As a Cybersecurity Analyst, systematic troubleshooting and problem-solving are essential skills. Today was all about applying those skills to a real-world issue.

---

## 🎯 Objectives
- Troubleshoot login issues with Elasticsearch & Kibana  
- Identify misconfigurations, corrupted files, and credential issues  
- Learn best practices for problem-solving in cybersecurity  

---

## 🛠️ Troubleshooting Process
1. **Checked logs** – Reviewed Elasticsearch logs to identify login errors.  
2. **Password reset** – Attempted to reset the built-in user password using:  
```bash
elasticsearch-reset-password -u elastic

