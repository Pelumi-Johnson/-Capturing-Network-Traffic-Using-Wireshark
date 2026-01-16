# 🌐 Capturing Network Traffic Using Wireshark

📄 **Full Lab Report:**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/-Capturing-Network-Traffic-Using-Wireshark/blob/main/Capturing%20Network%20Traffic%20Using%20Wireshark.pdf)

---

📘 **Course:** CMIT 436 – Cloud Security  
🏫 **Institution:** University of Maryland Global Campus (UMGC)  
🧪 **Lab Type:** Hands-On Network Analysis  
🛠️ **Tool Used:** Wireshark  

---

## 🎯 Objective
This lab demonstrates how to use **Wireshark**, a network protocol analyzer, to capture live network traffic and save packet data for further analysis. The exercise focuses on understanding how everyday network activity is reflected at the packet level.

---

## 🖥️ Lab Environment
- 💻 **Operating System:** Windows (Virtual Lab Environment)  
- 🔍 **Network Analyzer:** Wireshark  
- 🌐 **Network Interface:** Ethernet0  
- 🌍 **Traffic Generation:** Google Chrome  

---

## 🧭 Lab Procedure Overview

### ▶️ Starting the Environment
- Powered on the virtual machine using the uCertify lab interface.
- Launched Wireshark from the desktop.

### 🔌 Capturing Traffic
- Selected the **Ethernet0** interface.
- Started live packet capture from the Wireshark toolbar.
- Generated traffic by accessing **www.ucertify.com** in Google Chrome.

### ⏹️ Stopping & Reviewing
- Stopped the capture after sufficient traffic was recorded.
- Observed captured packets within Wireshark, including:
  - ARP
  - SSDP
  - LLMNR
  - IPv6 traffic

### 💾 Saving the Capture
- Saved the packet capture file (`capturedata`) to the desktop for later review.

---

## 📊 Results
- Successfully captured live network traffic using Wireshark.
- Verified visibility of multiple network protocols.
- Saved the capture file correctly for future analysis.
- Lab completion was marked **successful** in the uCertify platform.

---

## 🧠 Key Takeaways
- Even routine browsing generates diverse network traffic.
- Packet capture is essential for troubleshooting, monitoring, and incident response.
- Wireshark provides valuable insight into real-time network behavior.
