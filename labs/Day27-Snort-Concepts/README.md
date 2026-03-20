# Day 27 – Introduction to Snort IDS/IPS 🔍🛡️

## 🧠 Overview
Today’s lab focused on **Snort**, a powerful open-source **Intrusion Detection and Prevention System (IDS/IPS)** used to monitor and analyze network traffic in real time.

I explored its core concepts, operational modes, rule structure, and deployment considerations—building a solid foundation for network-based threat detection.

---

## 🎯 Objectives
- Understand what Snort is and how it works  
- Learn Snort operational modes  
- Explore Snort versions and implementations  
- Understand Snort rules and rule structure  
- Identify system requirements and deployment strategies  

---

## 📚 Key Concepts Learned

### 🔍 What is Snort?
Snort is a **Network Intrusion Detection System (NIDS)** that:
- Monitors network traffic in real time  
- Detects malicious activity using rules  
- Alerts or blocks suspicious traffic  

---

## 🛠️ Snort Operational Modes

- **Sniffer Mode**  
  Captures and displays packets in real time  

- **Packet Logger Mode**  
  Logs packets for later analysis  

- **NIDS Mode**  
  Analyzes traffic and applies rules to detect threats  

---

## 📌 Snort Versions & Implementations

- **Snort 3**  
  - Improved performance  
  - Modular architecture  

- **Snort 2**  
  - Widely used  
  - Requires more manual configuration  

- **Supported Systems**  
  - Linux (Preferred)  
  - Windows  
  - BSD  

---

## 📜 Snort Rules & Rule-Sets

Snort uses rules to detect or block malicious traffic:

- **Community Rules** – Free and open-source  
- **Registered Rules** – Free with account registration  
- **Subscription Rules** – Paid, frequently updated  

---

## 🖋️ Snort Rule Structure

A Snort rule consists of:

- **Rule Header**
  - Action (alert, drop, pass)  
  - Protocol  
  - Source & destination IPs  
  - Ports  

- **Rule Options**
  - Content matching  
  - Metadata  
  - Traffic flow direction  

---

## ⚙️ How Snort Works
- Captures network packets  
- Inspects traffic in real time  
- Compares packets against defined rules  
- Generates alerts or blocks traffic when threats are detected  

---

## 💻 System Requirements (Virtual Lab)

For running Snort on VMware or VirtualBox:

- **CPU:** Minimum 2 cores (4+ recommended)  
- **RAM:** Minimum 4GB (8GB recommended)  
- **Storage:** 20GB+  
- **OS:** Ubuntu, CentOS, or Debian  
- **Network:** Bridged or Promiscuous mode  

---

## 🌐 Network Placement Considerations

Proper placement improves detection capability:

- **Perimeter (Edge Network)**  
  Detects incoming external threats  

- **Internal Network (Core Switch)**  
  Monitors lateral movement and insider threats  

- **Dedicated IDS/IPS Segment**  
  Centralized monitoring and analysis  

---

## 🔎 Security Insight
- Snort provides **real-time visibility** into network traffic  
- Rule-based detection helps identify known attack patterns  
- Proper placement enhances threat detection effectiveness  

---

## 🚀 Key Takeaways
- Snort is a powerful tool for **network-based threat detection**  
- Understanding rules is key to effective monitoring  
- Deployment strategy affects visibility and performance  
- IDS/IPS tools are essential in SOC environments  

---

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

