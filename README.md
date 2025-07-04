# Network Fundamentals Project – Packet Tracer Simulation

This project simulates a medium-scale institutional network infrastructure using Cisco Packet Tracer. It includes core services such as DHCP, DNS, web servers, and advanced security and routing protocols

## 👨‍💻 Contributor
- Tolga Ünlü – 200444409  

## 📦 Project Overview

The network topology includes:

- 8 Routers  
- 11 Switches  
- 1 Access Point  
- 1 DHCP Server  
- 1 DNS Server  
- 3 Web Servers (main.com, tolga.com, nazlican.com)

The project simulates an internal corporate network structure with rented cloud web servers and provides internal domain resolution and automatic IP distribution.

## ⚙️ Configurations & Features

- **IP Addressing Scheme:**
  - Inter-router IPs: `10.0.0.0/24`
  - Endpoint IPs: `192.168.0.0/24`
  - Web servers: `8.8.8.0/24`
  - Internet Gateway: `78.1.1.0/28`

- **Services:**
  - DHCP pools for each endpoint group
  - Internal DNS registration for 3 custom domains
  - HTTP web pages with custom HTML/CSS on web servers

- **Security:**
  - SSH and Telnet enabled on most devices (username/password: `admin`)
  - Access Point: `NazTolAp` / Password: `E4F4C3BD2E`
  - Port Security on Switch8 (limit to 5 MAC addresses)
  - AAA & TACACS+ authentication on Switch3 (username: `nazli`, password: `tolga`)
  - VLAN Guest blocked from internet access (ACL applied)

- **Routing & Monitoring:**
  - Dynamic Routing: OSPF
  - Dynamic NAT
  - SNMP enabled on R31 (modification tested via PC8)

## 📁 File Info

- `.pkt` file contains the entire simulation.

---

Feel free to fork, test, or enhance the project for academic or learning purposes.
