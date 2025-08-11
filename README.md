# wireshark-network-capture-analysis
A collection of Wireshark network capture files (.pcap) and analysis reports for different protocols, attack patterns, and troubleshooting scenarios.


## 📌 Overview
This project is part of a cybersecurity practical exercise to **capture live network packets**, analyze them using **Wireshark**, and identify at least three different protocols from the captured data.  
The main protocols analyzed in this task are **HTTP**, **DNS**, and **TCP**.

---

## 🎯 Objective
- To capture live network packets using Wireshark.
- To filter packets based on specific protocols.
- To understand and document the characteristics of the identified protocols.
- To provide a `.pcap` file and a detailed report with screenshots.

---

## 🛠 Tools & Environment
- **Wireshark v4.x** (Free & Open Source)
- **Npcap** (Windows Packet Capture Library)
- **Operating System:** Windows 10/11 (also compatible with Linux/Mac)
- **Network Type:** Wi-Fi connection

---


---

## 🧪 Steps Performed

### 1️⃣ Install Wireshark
1. Download from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html).
2. Install with default options and ensure **Npcap** is installed for packet capture.

### 2️⃣ Start Packet Capture
1. Open Wireshark.
2. Select the **active network interface** (Wi-Fi).
3. Click the **blue shark fin icon** to start capturing.

### 3️⃣ Generate Network Traffic
- Visited a website in the browser to trigger **HTTP** and **DNS** traffic.
- Used the command:
  ```bash
  ping google.com


## 📂 Project Structure

