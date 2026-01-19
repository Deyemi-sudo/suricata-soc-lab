# Incident Report: ICMP Block Test

## 📅 Date/Time
January 11, 2026

## 🧾 Summary
ICMP traffic (ping requests) from Windows client `192.168.10.254` to Ubuntu server `192.168.10.20` was blocked by pfSense firewall rules.  
This test confirms that ICMP traffic was denied and not forwarded.

## 🛠 Tools Used
- pfSense Firewall
- Suricata IDS
- Wireshark

## 🚨 Evidence

### Firewall Rules
![Firewall Rules](../firewall-rules/firewall-rules.png)

### Wireshark Capture
![Wireshark Capture](../wireshark-captures/icmp-block.png)

## 🛡️ Response
- Firewall successfully blocked ICMP traffic
- Suricata monitored attempted communication
- No ICMP replies observed
- No forward/allowed traffic confirmed
