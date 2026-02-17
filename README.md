# Enterprise Office Network Design using Cisco Packet Tracer

## Project Overview

This project demonstrates the design and implementation of a simulated enterprise office network using Cisco Packet Tracer. The objective was to create a scalable and functional network environment integrating dynamic routing, automated IP addressing, centralized services, and remote device management.

The network simulates multiple interconnected enterprise locations where routers communicate through WAN links while supporting individual LAN environments connected via switches and end devices.

---

## Network Architecture

The enterprise network consists of:

- 9 interconnected routers forming a chained WAN topology
- 16 switches providing LAN connectivity
- Multiple PCs and laptops configured as DHCP clients
- One centralized server hosting DNS and HTTP services

Each router manages its own LAN subnet and participates in dynamic routing to ensure full connectivity across the network.

---

## Technologies and Protocols Used

- EIGRP (Enhanced Interior Gateway Routing Protocol) for dynamic routing
- DHCP (Dynamic Host Configuration Protocol) for automatic IP assignment
- DNS (Domain Name System) for domain name resolution
- HTTP for internal web hosting
- Telnet (VTY lines) for remote router management
- Subnetting and IP address planning
- Cisco CLI configuration

---

## IP Addressing Scheme

WAN Network Range (Router-to-Router Communication):

- 192.168.1.0 – 192.168.8.0

LAN Network Range:

- 172.16.1.0 – 172.16.16.0

Different subnet masks were used based on device requirements to optimize IP utilization.

---
## Screenshots

### Network Topology
<img width="1507" height="633" alt="Netwok-Design" src="https://github.com/user-attachments/assets/31a1847c-1df3-4a97-a409-80ccadbad7c5" />

### EIGRP Configuration
<img width="1267" height="1011" alt="IP-Routes" src="https://github.com/user-attachments/assets/11533e49-7e4a-4ea5-9320-926aed319c46" />

### DHCP Working
<img width="948" height="1006" alt="Screenshot 2026-02-17 124130" src="https://github.com/user-attachments/assets/91535002-3b07-4cc1-bddb-efa04698b069" />


### DNS Lookup
<img width="805" height="1002" alt="DNS_Server" src="https://github.com/user-attachments/assets/364acee0-f8a9-4447-a380-1847799eb54e" />


### HTTP Website Test
<img width="1266" height="1000" alt="Lauching_Site_on PCbrowser" src="https://github.com/user-attachments/assets/59239990-cc79-42ae-9a0b-24a194231341" />


### Telnet Remote Access
<img width="1355" height="1018" alt="Telnet_remote-access" src="https://github.com/user-attachments/assets/5cde0b42-88cb-4bdd-bef0-3b1b9c870ec6" />


## Key Features

- Dynamic route exchange using EIGRP
- Automated IP assignment through multiple DHCP pools
- DNS-based access to internal websites:
  - www.aot.com
  - www.jjk.com
- Remote router configuration using Telnet
- Successful end-to-end connectivity across all network segments

---

## Testing and Validation

The following tests were performed:

- Ping tests for connectivity verification
- DNS lookup validation
- HTTP browser testing for hosted websites
- Remote login via Telnet

All devices successfully communicated across networks through dynamic routing.

---

## Network Topology Diagram

**Topology Overview:**

The diagram represents a simulated enterprise network consisting of nine routers connected in a chained WAN architecture. Each router connects to local LAN segments through switches and supports DHCP-based client devices. Dynamic routing using EIGRP ensures connectivity between all subnets, while a centralized server provides DNS and HTTP services accessible through domain names. Telnet remote access is enabled on all routers for administrative management.

(Add your topology screenshot here)

---

## Learning Outcomes

- Enterprise network topology design
- Dynamic routing protocol implementation
- Automated IP management using DHCP
- DNS and HTTP service integration
- Remote network device administration

---

## Future Improvements

- Replace Telnet with SSH for secure remote access
- Implement Access Control Lists (ACLs)
- Add VLAN segmentation for improved network organization
- Introduce hierarchical network design

---

## Author

Gagandeep Kaur
