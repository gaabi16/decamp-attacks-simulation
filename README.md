# Secure Network & Cyber-Attacks Simulation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-000000?style=for-the-badge&logo=pfsense&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)

A cybersecurity project focused on designing a secure network infrastructure, executing custom cyber-attacks (**Red Team**), and implementing robust detection and prevention mechanisms (**Blue Team**). 

This was developed collaboratively as the final project for the *Secure Network Management* course at **Hochschule München**.

## Infrastructure & Simulation

The entire enterprise environment was simulated using **multiple Virtual Machines** (VirtualBox) to realistically represent each network component without affecting real hardware:
* **Routing & Security:** pfSense firewalls (separating the External network, DMZ and Internal LAN) and VyOS routers.
* **Monitoring:** Snort IDS/IPS and Splunk SIEM for log ingestion and real-time alerting.
* **Endpoints:** Dedicated VMs for Internal Clients, Internal Attackers and External Attackers.

## Key Features

* **Offensive Security (Python/Scapy):** Developed custom scripts to launch targeted attacks, including ARP Sweeps, TCP SYN Scans, TCP/ICMP Floods (DoS) and RIP Route Injections.
* **Defensive Security:** Configured strict firewall ACLs, wrote custom Snort rules to detect the Scapy attack signatures and analyzed logs using Splunk.
* **Traffic Analysis:** Deep packet inspection using Wireshark to validate attack success and verify detection accuracy.

## Network Topology

<p align="center">
  <img src="Important%20documents/Network%20topology.png" width="800">
</p>

## Authors / Team

**Crisan Gabriel & Cinteza Tudor**
* LinkedIn: https://linkedin.com/in/gabriel-crisan16/
