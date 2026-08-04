# 🏫 College Campus Network

<p align="center">
  <img src="./images/flowchart.pngflowchart.png" alt="ColleNetwork Topology">
</p>

## 🧱 Overview

A multi-campus university network design implemented in Cisco Packet Tracer.
It features a hierarchical architecture connecting a main campus and a
branch campus, utilizing VLAN segmentation, router-on-a-stick inter-VLAN
routing, RIPv2 dynamic routing, and centralized DHCP services.

---

## ⚙️ Configuration Summary
- VLANs: Admin (10), HR (20), Finance (30), Business (40) etc..
- RIP version 2 enabled for internal dynamic routing between campus routers
- Inter-VLAN Routing
- Router-based DHCP server configured with multiple pools for each department to handle dynamic IP addressing

---

## 📁 Files
- `campus_network.pkt` — Full Packet Tracer topology
- `campus_topology.png` — Visual diagram
- `configs/` — Router, switch   configuration files

---

## ✅ Verification
- Successful IP acquisition via DHCP on client end devices.
- Successful ping tests across different VLANs (Inter-VLAN routing) and between campus sites.
- Successful verification of end-to-end connectivity to external server resources.

---

## 🧠 Lessons Learned
This project reinforced practical skills in hierarchical network design, implementation of router-on-a-stick for inter-VLAN routing, configuration of RIPv2 for dynamic campus-wide connectivity, and the management of DHCP server pools to streamline IP addressing for diverse departmental end-devices.

---

<p align="center">⬅️ <a href="../README.md">Back to Main Portfolio</a></p>
