# 🖧 Network System Design for the Practical Workshop  
**Quang Ninh University of Industry**

## 📌 Overview
This project focuses on designing and simulating a network system for the university's practical workshop.  
The goal is to build a stable, secure, and scalable network infrastructure that meets the requirements of teaching and hands-on practice.

---

## 🎯 Role
**Network Designer & Simulator** – Designed the network diagram and simulated the entire system using **Cisco Packet Tracer**.

---

## 🔧 Key Tasks
- 📊 **Requirements Analysis**: Analyzed usage requirements and surveyed the current network infrastructure.  
- 🗺 **Network Topology Design**: Created optimized **physical** and **logical** topologies for the practical workshop.  
- 🌐 **Network Configuration**: Configured **VLANs** and **inter-VLAN routing**.  
- 🖥 **Server Deployment**: Set up servers providing  
  - DHCP  
  - DNS  
  - HTTP/HTTPS  
  - FTP  
  - Email  
  - IoT services  
- 🚀 **Performance & Scalability**: Ensured stable operation, high bandwidth, and easy scalability.

---

## 🛠 Technologies & Tools
- **Cisco Packet Tracer**
- **Switches, Routers, and Servers**
- **Network Protocols:** DHCP, DNS, HTTP/HTTPS, FTP, SMTP, IoT

---

## 💰 Equipment Price List (VNĐ)

| No. | Device                                                     | Quantity | Unit Price (VNĐ) | Total Price (VNĐ) |
|-----|------------------------------------------------------------|----------|------------------|-------------------|
| 1   | Cisco CISCO1921/K9 C1921 Modular Router                     | 1        | 2,820,256        | 2,820,256         |
| 2   | Switch Cisco Layer3 8 Port CBS250-8PP-E-2G                  | 1        | 8,484,615        | 8,484,615         |
| 3   | Switch Cisco 16 Port CBS110-16T-EU                          | 3        | 2,750,000        | 8,250,000         |
| 4   | Switch Cisco 8 Port SG95D-08                                | 4        | 1,250,000        | 5,000,000         |
| 5   | Switch Cisco 48 Ports SLM2048T-EU                           | 2        | 9,796,000        | 19,592,000        |
| 6   | Wifi Router TP-Link TL-WR940N                               | 6        | 430,000          | 2,580,000         |
| 7   |    8 Camera Hikvision                                       | 1        | 7,930,000        | 7,930,000         |
| 8   | CAT5E J45 AMP                                               | 350      | 9,000            | 3,150,000         |
| 9   | Cable AMP CAT5E 6-219590 (305m/roll)                        | 2        | 2,600,000        | 7,800,000         |
| **Total** |                                                        |          |                  | **65,606,871**    |

---

## 📍 IP Addressing & Subnet Mask

| VLAN ID | VLAN Name   | Devices | Allocated Hosts | Network Address | Subnet Mask     | Usable IP Range               | Broadcast Address |
|---------|-------------|---------|-----------------|-----------------|-----------------|--------------------------------|-------------------|
| 10      | Admin       | 9       | 14              | 192.168.1.160   | 255.255.255.240 | 192.168.1.161 - 192.168.1.174 | 192.168.1.175     |
| 20      | Student     | 25      | 30              | 192.168.1.128   | 255.255.255.224 | 192.168.1.129 - 192.168.1.158 | 192.168.1.159     |
| 30      | Server      | 5       | 6               | 192.168.1.176   | 255.255.255.248 | 192.168.1.177 - 192.168.1.182 | 192.168.1.183     |
| 40      | IoT Devices | 4       | 6               | 192.168.1.184   | 255.255.255.248 | 192.168.1.185 - 192.168.1.190 | 192.168.1.191     |
| 50      | CCTV        | 2       | 2               | 192.168.1.192   | 255.255.255.252 | 192.168.1.193 - 192.168.1.194 | 192.168.1.195     |
| 60      | Lab PCs     | 110     | 126             | 192.168.1.0     | 255.255.255.128 | 192.168.1.1 - 192.168.1.126   | 192.168.1.127     |
| -       | Router Link | 1       | 2               | 192.168.1.196   | 255.255.255.252 | 192.168.1.197 - 192.168.1.198 | 192.168.1.199     |

---

## 📷 Network Diagram
![Physical Network Diagram](https://github.com/vunguyen1203/network_system_design_practice_workshop/raw/main/physical_diagram.png)

## 📷 Logic Network Diagram
![Logic Network Diagram](https://github.com/vunguyen1203/network_system_design_practice_workshop/blob/main/logic_diagram.png?raw=true)

## 📷 Simulator
![Simulator](https://github.com/vunguyen1203/network_system_design_practice_workshop/blob/main/simulator.png?raw=true)



