# cisco-branch-network-design
A Cisco Packet Tracer network simulation featuring VLANs, Wireless integration, DHCP, and Inter-VLAN routing for XYZ Company branch

# 🌐 XYZ Company Branch Network Design - Bonalbo

## 📌 Project Overview
**XYZ Company** is a fast-growing food trading enterprise based in Eastern Australia, serving over 2 million global customers. This project covers the design and implementation of a dedicated, standalone branch network near **Bonalbo**, operating independently from the company's Headquarters (HQ).

---

## 🎯 Network Requirements & Specifications

* **Hardware Used:** 1 Cisco Router and 1 Cisco Switch.
* **Department Segmentation:** Divided into **3 distinct VLANs**:
  1. `Admin / IT`
  2. `Finance / HR`
  3. `Customer Service / Reception`
* **Wireless Access:** Integrated wireless network for end users in each department.
* **Automated IP Assignment:** Dynamic IP distribution via **DHCP** for all host devices.
* **Inter-VLAN Communication:** Inter-VLAN routing configured to ensure seamless communication across all departments.
* **Base Network Address:** Assigned ISP IP range `192.168.1.0/24` (Subnetted for each department).

---

## 📸 Network Topology Diagram
![Network Topology](topology.png)

---

## 🛠 Device Breakdown

| Device Type | Description / Model | Role |
| :--- | :--- | :--- |
| **Router** | Cisco Router | Inter-VLAN Routing & DHCP Gateway |
| **Switch** | Cisco Switch | VLAN Trunking & Access Port Allocation |
| **Access Points** | Wireless Access Points (WAPs) | Wireless Connectivity for Hosts |
| **End Devices** | PCs, Laptops, Wireless Hosts | End-user devices receiving IPv4 automatically |

---

## 🧪 Verification & Testing
* **DHCP Verification:** Host devices in all 3 departments successfully acquire automatic IPv4 addresses within the `192.168.1.0` network range.
* **Connectivity Testing:** Full end-to-end communication verified via successful ICMP (`ping`) tests across all VLANs and departments.



