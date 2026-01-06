# Enterprise Network POC on EVE-NG

## Overview
This project demonstrates how to design and deploy a **proof-of-concept enterprise network architecture** using **EVE-NG**. The goal is to build a realistic environment that includes network infrastructure, directory services, security monitoring, and attack simulation.

---

## Objectives
- Model and deploy an enterprise network on **EVE-NG**
- Configure **Cisco switches and routers** (VLANs, routing, redundancy)
- Deploy **Active Directory** for authentication, DNS, and DHCP
- Integrate **Wazuh HIDS** for endpoint security
- Set up **Zabbix** for monitoring
- Simulate attacks using **Atomic Red Team**
- Implement **pfSense firewall cluster in High Availability (HA)**
- Provide DNS/DHCP services via Active Directory

---

## Network Architecture

### Key Components
- **External Network**: Cisco routers (HSRP), external switches
- **Firewall Cluster**: pfSense HA setup for redundancy
- **Internal Network**: Core switches (LACP), Active Directory server, SIEM, Zabbix, and Kali Linux for testing
- VLAN segmentation for DMZ, internal, and management zones

---

## Tools & Technologies
- **EVE-NG** for network emulation
- **Cisco IOS** for routing and switching
- **pfSense** for firewall HA cluster
- **Active Directory** for centralized authentication and DNS/DHCP
- **Wazuh** for intrusion detection
- **Zabbix** for monitoring
- **Atomic Red Team** for attack simulation
- **Kali Linux** for penetration testing

---

## Deployment Steps
1. Build the topology in **EVE-NG**
2. Configure Cisco devices (VLANs, routing, HSRP)
3. Deploy Active Directory and configure DNS/DHCP
4. Install Wazuh agents on endpoints
5. Set up Zabbix monitoring
6. Configure pfSense HA cluster
7. Run Atomic Red Team tests
8. Validate monitoring and security alerts

---



---
