# Day 22 – Mastering Wireshark for Network Analysis 🦈🔍

## 🧠 Overview
Today’s lab focused on **Wireshark**, one of the most powerful tools for network traffic analysis and packet inspection. I explored the installation process, navigated the GUI, captured live traffic, and practiced analyzing PCAP files using different filtering techniques.

---

## 🎯 Objectives
- Install and set up Wireshark  
- Understand the Wireshark interface and GUI components  
- Capture and analyze live network traffic  
- Learn how to save and review PCAP files  
- Use filters to investigate network activity  

---

## 📚 Key Concepts Learned

### 🔧 Setting Up Wireshark & GUI Walkthrough
After installing Wireshark, I explored the interface and key components:

- **Start Capture Button** – Begins live network traffic capture  
- **Filter Bar** – Helps refine and focus on specific packets  
- **Packet List Pane** – Displays captured packets  
- **Packet Details Pane** – Provides deeper protocol information  
- **Packet Bytes Pane** – Shows raw packet data  

---

## 📡 Capturing Live Traffic
Using **Windows on my host system**, I captured real-time network traffic and learned how to:

- Start and stop packet captures  
- Monitor network activity in real time  
- Save captured traffic as **PCAP files**  
- Export files for further analysis  

---

## 📊 Viewing Network Statistics
Wireshark provides useful statistics that help understand traffic patterns:

- **Protocol Hierarchy** – Shows which protocols are most active  
- **Conversations** – Displays communication between devices  
- **Endpoints** – Lists all unique network devices involved in traffic  

---

## 🔍 Filtering and Analyzing PCAP Files
Wireshark filters make analysis faster and more efficient. Some filters I practiced include:

- `ip.addr == 192.168.1.1` – Traffic from a specific IP address  
- `tcp.port == 80` – Filter HTTP traffic  
- `dns` – Analyze DNS queries and responses  
- `http.request.method == "GET"` – Identify HTTP GET requests  

---

## 🧪 Hands-on Lab Experience
- Analyzed a provided **PCAP file** using **Kali Linux on my virtual machine**  
- Applied different filters to investigate captured traffic  
- Practiced identifying useful information within network packets  

This hands-on practice improved my confidence in using Wireshark for **real-world cybersecurity investigations**.

---

## 🚀 Key Takeaways
- Wireshark is a **powerful and essential tool** for network security analysis  
- Packet filtering helps isolate important network activity quickly  
- PCAP files provide valuable evidence during investigations  
- Packet analysis is a key skill in **SOC operations and incident response**

---

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

---

## 📌 Status
✅ Completed

