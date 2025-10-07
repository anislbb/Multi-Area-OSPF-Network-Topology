# 🛰️ Enterprise Network Topology — Multi-Area OSPF, VLANs, and Security Configuration

## 📘 Overview
This project demonstrates a complete **enterprise-level Cisco network** designed and configured using **Cisco Packet Tracer**.  
The network implements **multi-area OSPF routing**, **VLAN segmentation**, **VTP management**, **EtherChannel**, **DHCP**, and **STP per VLAN**, simulating a realistic and secure network infrastructure.

---

## 🧩 Network Architecture
- **3 Routers** connected via **OSPF Area 0** (backbone)
- **2 Core Switches**:
  - Core 1 → OSPF **Area 2**
  - Core 2 → OSPF **Area 1**
- **VTP** domain configured for VLAN management
- **EtherChannel** between core and distribution switches
- **STP** per VLAN to prevent loops
- **DHCP Server** for automatic IP assignment to all VLANs
- **Trunk links** between switches for VLAN propagation

---

## 🌐 VLAN Configuration
| Area | VLANs | Subnets |
|------|--------|----------|
| Area 1 | VLAN 11, 12, 13 | 1010.11.0/28 – 1010.13.0/28 |
| Area 2 | VLAN 21, 22, 23 | 1010.21.0/27 – 1010.23.0/27 |

---

## ⚙️ Technologies Used
- **OSPFv2 (Multi-Area)**
- **VLANs / VTP / Trunking**
- **Spanning Tree Protocol (PVST+)**
- **EtherChannel (LACP)**
- **DHCP Server Configuration**
- **Static IP Management for Routers and Core Switches**

---

## 🧠 Learning Objectives
- Design and implement hierarchical Cisco network architectures
- Configure routing between multiple OSPF areas
- Ensure redundancy and loop prevention using STP
- Manage VLANs and trunking with VTP
- Automate IP addressing with DHCP

---

## 🧑‍💻 Author
**Mohamed Anis LEBBAH**  
Cybersecurity & Network Engineering Student  
Université Oran 1 Ahmed Ben Bella  
🔗 [LinkedIn](https://www.linkedin.com/in/anis-lebbah-4039a6377) | 💻 [GitHub](https://github.com/anislbb)
