# Network Traffic Analyzer

## Project Report

### 1. Introduction
Network security and traffic monitoring are critical components of modern cybersecurity frameworks. This project, **Network Traffic Analyzer**, aims to analyze network traffic from **PCAP (Packet Capture) files**, providing insights into protocol usage, bandwidth consumption, and potential security threats such as **port scanning attacks**.

- **Phase 1: Rule-Based Network Traffic Analyzer** (Current Implementation)

### 2. Phase 1: Rule-Based Network Traffic Analyzer
#### 2.1 Objective
The first phase focuses on **extracting, analyzing, and visualizing network traffic data** using predefined rules and statistical methods.

#### 2.2 Implementation
The system processes a **PCAP file** to extract and analyze key network features such as:
- **Source and destination IP addresses**
- **Protocols used (TCP, UDP, ICMP, etc.)**
- **Packet sizes and bandwidth consumption**
- **Port scanning detection** (by identifying IPs accessing multiple ports excessively)

#### 2.3 Key Functionalities
- **Protocol Distribution Analysis:** Determines the percentage of traffic by protocol.
- **IP Communication Patterns:** Identifies communication trends between different IPs.
- **Bandwidth Utilization:** Calculates total bandwidth consumption.
- **Port Scanning Detection:** Flags potential attackers based on unusual port access patterns.

#### 2.4 Tools & Technologies Used
- **Python**
- **Scapy (for PCAP processing)**
- **Pandas (for data analysis)**
- **Matplotlib (for visualization)**
- **Logging & TQDM (for debugging and progress tracking)**


### 4. Conclusion & Future Scope
The **Phase 1: Rule-Based Network Traffic Analyzer** successfully processes PCAP files to analyze traffic patterns and detect anomalies based on predefined rules. However, manual rule-based methods have **limitations in adaptability**.
**ML-Powered Analyzer** can be furter implemented which will leverage machine learning to enhance threat detection accuracy and automate network security monitoring.

The final goal is to develop a **fully automated, intelligent network monitoring system** capable of detecting **zero-day attacks, advanced persistent threats (APTs), and sophisticated cyber intrusions**.

---

**Current Status:** Phase 1 is implemented and demonstrated successfully.

**Next Steps:** Phase 2 will be integrated by incorporating machine learning-based anomaly detection techniques.

