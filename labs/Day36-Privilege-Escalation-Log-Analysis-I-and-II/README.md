# 📅 Day 36 – Log Analysis & Privilege Escalation (Part II)

## 🧠 Overview  
Today’s lab focused on analyzing attacker behavior through logs and identifying privilege escalation techniques. The exercise highlighted how misconfigurations and poor file handling can be exploited to gain unauthorized access.

---

## 🎯 Objectives  
- Analyze system activity to identify attacker actions  
- Understand how packet sniffing tools are used maliciously  
- Identify file upload bypass techniques  
- Detect privilege escalation through misconfigurations  
- Strengthen understanding of system hardening and security gaps  

---

## 📚 Key Concepts Learned  

### 🔍 Attacker Enumeration Techniques  
- The attacker explored network configurations using:  
  - ifconfig – View network interfaces  
  - iptables -L – List firewall rules  
  - lsof -i – Check open network connections  

---

### 🌐 Packet Analysis Tool  
- The attacker attempted to use:  
  - tcpdump – A packet-sniffing tool used to capture network traffic  

---

### 📂 File Upload Bypass Technique  
- The attacker used the .phtml file extension  
- This bypass works because some servers execute .phtml as PHP  
- Example:  
  - /var/www/html/uploads/x.phtml  

---

### 🔐 Privilege Escalation (SUID Misconfiguration)  
- The attacker exploited a misconfigured Python binary  
- The binary had the SUID (Set User ID) bit set  
- This allowed execution with root privileges, leading to a root shell  

---

## 🚨 Identifying Security Weaknesses  
- Misconfigured binaries (SUID) can lead to privilege escalation  
- Weak file upload filters can be bypassed using alternative extensions  
- System commands can reveal sensitive configuration details  

---

## 🧠 Lessons Learned  
- bash_history is a valuable forensic artifact if not cleared  
- Misconfigurations can create critical security vulnerabilities  
- File upload restrictions must be properly enforced  
- Monitoring logs is essential for detecting attacker activity  

---

## 🚀 Key Takeaways  
- Small misconfigurations can lead to full system compromise  
- Attackers rely on system visibility and weak controls  
- Proper permissions and system hardening are critical for defense  

---

## 📸 Screenshots  
Screenshots are available in the `screenshots` folder.  

---

## 📌 Status  
✅ Completed  

