# GRE Tunnel

This repository contains a **Cisco Packet Tracer lab** demonstrating the configuration of a **Generic Routing Encapsulation (GRE) Tunnel**.  
It shows how two remote networks can be connected over an IP backbone using a virtual point-to-point tunnel.

---

## 📂 Files
- `GRE_Tunnel.pkt` – Packet Tracer lab file  
- Any supporting notes or topology diagrams  

---

## 🚀 Features
- GRE tunnel configuration between two routers  
- Encapsulation of packets for secure delivery  
- Routing over tunnel interfaces  
- Connectivity test between remote LANs  

---

## 🛠️ Requirements
- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) installed  

---

## ⚙️ How to Use
1. Download the `GRE_Tunnel.pkt` file from the repo or **Releases** section.  
2. Open it with **Cisco Packet Tracer**.  
3. Check tunnel configurations with:  
   ```bash
   show running-config
   show ip interface brief
   ping <remote LAN IP>
