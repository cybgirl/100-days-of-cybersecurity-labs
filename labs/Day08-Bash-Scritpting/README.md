# Day 08 – Introduction to Bash Scripting for Cybersecurity Analysts

## 🧠 Overview
Today’s lab focused on Bash scripting, a powerful tool for automating tasks and improving efficiency in cybersecurity operations. Bash scripting enables analysts to streamline workflows, analyze logs, and respond to incidents more effectively.

---

## 💡 What is Bash?
Bash (Bourne Again Shell) is a command-line interpreter used in Linux/Unix systems. It allows users to execute commands and create scripts to automate repetitive tasks.

---

## 🛠 Why Bash is Important in Cybersecurity

- ⚡ Automates security tasks (log monitoring, scans, updates)
- 🔍 Enhances log analysis and threat hunting
- 👤 Helps monitor users and system processes
- 🚨 Supports faster incident response

---

## 📚 Topics Covered

### 📁 Navigation & File Management
- `cd` – change directory  
- `pwd` – print working directory  
- `ls` – list files  
- `tree` – view directory structure  

---

### 📂 File Operations
- `touch` – create files  
- `mkdir` – create directories  
- `rm` – delete files  
- `cp` – copy files  
- `mv` – move/rename files  

---

### 🔐 Permissions & Access Control
- `chmod` – change file permissions  
- `chown` – change file ownership  
- `setfacl` – manage advanced permissions  

---

### 🔍 Log Analysis & File Inspection
- `grep` – search within files  
- `awk` – text processing  
- `cat`, `less`, `more` – view file content  
- `file`, `stat` – file information  

---

### ⚙️ Process Management
- `ps aux` – list running processes  
- `top`, `htop` – monitor system usage  
- `kill`, `killall`, `pkill` – terminate processes  
- `bg`, `fg`, `jobs` – manage jobs  
- `nice`, `renice` – adjust process priority  

---

### 🔗 Command Integration (Pipes)
- Used `|` to chain commands
- Example:
  ```bash
  ps aux | grep ssh

