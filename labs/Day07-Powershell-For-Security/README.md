# Day 07 – Windows PowerShell Fundamentals for Cybersecurity

## 🧠 Overview
Today’s lab focused on Windows PowerShell, a powerful command-line and scripting tool used for system administration, automation, and cybersecurity operations.

---

## 📚 Topics Covered

### ⚡ PowerShell Basics
- Navigated directories using:
  - `cd`, `pwd`, `clear`
- Used:
  - `get-alias (gal)`
  - `get-help`
- Opened File Explorer using:
  - `explorer .`

---

### 🧮 Variables & Data Types
- Created and used variables:
  - Boolean → `$ison = $true`
  - Integer, Float, String
- Learned differences between:
  - Single quotes `' '` (literal)
  - Double quotes `" "` (interpreted)

---

### ⚙️ Cmdlets & System Interaction
- Used PowerShell cmdlets:
  - `Get-Process`
  - `Get-Service`
  - `Stop-Process`
- Learned how cmdlets help automate tasks and interact with the OS

---

### 🔍 Security & Incident Response

#### Key Commands:
- View recent security logs:
  - `Get-EventLog -LogName Security -Newest 10`

- Identify high CPU processes:
  - `Get-Process | Where-Object { $_.CPU -gt 50 }`

- System information:
  - `Get-CimInstance Win32_OperatingSystem`
  - `Get-CimInstance Win32_ComputerSystem`

- Network information:
  - `Get-NetIPAddress`
  - `Get-NetTCPConnection`
  - `Get-NetUDPEndpoint`

---

## 🛡️ PowerShell in Cybersecurity

- Used for:
  - Threat detection
  - Log analysis
  - System auditing
  - Automation

- Security Risk:
  - Attackers use PowerShell for fileless malware

- Mitigation:
  - Restrict script execution:
    - `Set-ExecutionPolicy Restricted`

---

## 🚀 Key Takeaways
- PowerShell is essential for cybersecurity operations
- Cmdlets simplify system monitoring and automation
- Understanding PowerShell helps detect and defend against attacks

---

## 📸 Screenshots
All screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

