Incident Report: Nmap SYN Scan

## 📅 Date/Time
January 5, 2026

## 🧾 Summary
Suricata IDS detected a SYN scan from `192.168.10.20` targeting the pfSense firewall (`192.168.10.1`).  
This activity is classified as reconnaissance — the attacker was probing multiple ports to discover open services.

## 🛠 Tools Used
- Suricata IDS
- Wireshark
- pfSense Firewall

## 🚨 Evidence

### Suricata Alert
![Suricata Alert](../suricata-alerts/nmap-scan.png)

### Wireshark Capture
![Wireshark Capture](../wireshark-captures/wireshark-capture.png)

## 🛡️ Response
- Source IP flagged
- Firewall rules reviewed
- Monitoring increased
