# Incident Report: EICAR Malware Test

## 📅 Date/Time
January 17, 2026

## 🧾 Summary
Windows Defender detected the EICAR test file on the Windows client.  
This file is a harmless test used to verify antivirus and IDS functionality. Suricata was monitoring traffic during the download.

## 🛠 Tools Used
- Windows Defender
- Suricata IDS
- Wireshark

## 🚨 Evidence

### Windows Defender Alert
![Windows Defender](../windows-alerts/eicar-detected.png)

### Suricata Alerts
![Suricata Alert](../suricata-alerts/suricata-alerts.png)

### Wireshark Capture
![Wireshark Capture](../wireshark-captures/eicar-test.png)

## 🛡️ Response
- Defender quarantined the file automatically
- Suricata confirmed traffic inspection
- No forward/allowed traffic beyond the test file
