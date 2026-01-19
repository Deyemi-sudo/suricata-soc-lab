# SOC Analyst Lab: pfSense + Suricata

# Objective
This project is a home lab I built to practice SOC workflows. The goal was to detect, analyze, and document different types of network threats using open‑source tools and a firewall setup.

# Tools Used
- pfSense Firewall
- Suricata IDS/IPS
- Wireshark
- Windows Defender
- VMware Workstation

# Folder Structure
- incident-reports/ – Written reports for each incident
- suricata-alerts/ – Screenshots of Suricata alerts
- wireshark-captures/ – Screenshots of packet captures
- windows-alerts/ – Windows Defender detections
- firewall-rules/ – Screenshot of firewall configuration

# Completed Incidents
- Detection of an Nmap SYN scan
- EICAR malware test file detection
- ICMP block verification through firewall rules

# Firewall Policy
I configured the firewall with a **deny‑by‑default** stance.  
- Blocked: ICMP, Telnet, FTP  
- Allowed: HTTP (80), HTTPS (443), DNS (53)  

This setup enforces strict control while still permitting essential traffic.

# Next Steps
- Write and test custom Suricata rules
- Add a network diagram for clarity
- Expand the lab with DNS tunneling or brute‑force detection scenarios
