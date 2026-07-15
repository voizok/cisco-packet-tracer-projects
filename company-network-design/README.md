# 🏢 Company Network Design# 

## 🧱 Overview
A professional business network design for a trading floor support center, implemented in Cisco Packet Tracer. The project features a redundant, hierarchical architecture (Core, Distribution, and Access layers) supporting 600 staff across three floors. It incorporates advanced enterprise technologies, including VLAN segmentation, Inter-VLAN routing via multi-layer switches, OSPF dynamic routing, redundant ISP connectivity with NAT (PAT), port security, and comprehensive wireless network integration for mobile devices

---

## ⚙️ Configuration Summary
- VLANs: Admin (10), HR (20), Finance (30), Business (40) etc..
- OSPF configured across Core routers and Layer 3 switches for dynamic network advertisement.
- Inter-VLAN Routing
- Router-based DHCP server configured with multiple pools
- Port security (sticky MAC learning) for Finance/Accounts, SSH for remote device management, and NAT Overload (PAT) for external connectivity to redundant ISPs

---

## 📁 Files
- `company_network.pkt` — Full Packet Tracer topology
- `company_topology.png` — Visual diagram
- `configs/` — Router, switch, and firewall configuration files

---

## ✅ Verification
- Successful IP acquisition via DHCP on client end devices.
- Successful ping tests across different VLANs (Inter-VLAN routing) and between campus sites.
- Confirmed PAT/NAT translations allow internal hosts to reach external ISP resources
- Verified port security on the Finance/Accounts switch, ensuring only authorized devices connect

---

## 🧠 Lessons Learned
This project provided hands-on experience in building a redundant, hierarchical network design (Core, Distribution, and Access layers). It reinforced skills in configuring Inter-VLAN routing,implementing OSPF dynamic routing for enterprise-scale path selection, and establishing secure, scalable DHCP services with helper addresses. Additionally, it highlighted the practical application of NAT/PAT for edge connectivity and port security protocols to maintain network integrity.

---

<p align="center">⬅️ <a href="../README.md">Back to Main Portfolio</a></p>