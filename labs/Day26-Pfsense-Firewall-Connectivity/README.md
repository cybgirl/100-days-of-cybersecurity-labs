# Day 26 – pfSense Troubleshooting & SSH Configuration 🔧🔐

## 🧠 Overview
Today’s lab focused on troubleshooting and optimizing pfSense connectivity on VMware Workstation, as well as enabling remote access via SSH.

During the setup, I encountered an issue where I couldn’t access the internet. Instead of getting stuck, I analyzed the problem, troubleshot it, and successfully restored connectivity—reinforcing the importance of problem-solving in cybersecurity.

---

## 🎯 Objectives
- Troubleshoot network connectivity issues in pfSense  
- Optimize firewall configuration  
- Explore pfSense interface and features  
- Enable SSH for remote firewall management  
- Practice secure remote access using PuTTY  

---

## 🛠️ Practical Experience
- Identified and resolved internet connectivity issues  
- Performed a walkthrough of pfSense features  
- Enabled SSH access for remote login  
- Practiced connecting to pfSense using PuTTY  

---

## 🔍 Troubleshooting Insight
- Network issues are common during firewall configuration  
- Taking a step back to analyze the problem improves efficiency  
- Troubleshooting is a **core skill for SOC analysts**  

---

## 🔐 Enabling SSH on pfSense

### Step 1: Enable SSH in pfSense
- Log in to the pfSense web interface  
- Navigate to System > Advanced 
- Scroll to the Secure Shell section  
- Enable Secure Shell (SSH)  
- (Optional) Select Public Key Only for better security  
- Save changes  

---

### Step 2: Install PuTTY
- Download and install PuTTY from: https://www.putty.org/  
- Used for remote SSH access and key generation  

---

### Step 3: Generate SSH Keys (Optional)
- Open **PuTTYgen**  
- Click **Generate** and move mouse to create randomness  
- Save:
  - Public key  
  - Private key (keep secure)  

---

### Step 4: Add Public Key to pfSense
- Go to **System > User Manager**  
- Select or create a user  
- Paste the public key into **Authorized SSH Keys**  
- Save and apply changes  

---

### Step 5: Connect via PuTTY
- Open PuTTY  
- Enter pfSense LAN IP (e.g., `192.168.1.1`)  
- Use port **22**  
- Click **Open**  

**Authentication Options:**
- Password-based login (default credentials)  
- Key-based login (load private key under SSH > Auth)  

---

## 🔎 Security Insight
- SSH provides secure remote management of firewalls  
- Key-based authentication is more secure than passwords  
- Proper configuration reduces unauthorized access risks  

---

## 🚀 Key Takeaways
- Troubleshooting is a critical cybersecurity skill  
- Networking fundamentals are essential for firewall management  
- SSH enables secure and flexible remote administration  
- Continuous practice improves problem-solving and technical confidence  

---

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

