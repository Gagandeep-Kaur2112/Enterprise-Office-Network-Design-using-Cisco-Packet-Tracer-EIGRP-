Enterprise Office Network Design using Cisco Packet Tracer
Project Overview

This project demonstrates the design and implementation of a simulated enterprise office network using Cisco Packet Tracer. The network is built to represent multiple interconnected enterprise locations with automated configuration, dynamic routing, centralized services, and remote device management.

The primary objective was to create a scalable network infrastructure where multiple routers, switches, and end devices communicate efficiently while supporting internal web services accessible through domain names.

Network Architecture

The enterprise network consists of:

9 interconnected routers forming a chained WAN topology

16 switches providing LAN connectivity

Multiple PCs and laptops configured as DHCP clients

One centralized server providing DNS and HTTP services

Each router supports its own LAN subnet and exchanges routing information using dynamic routing protocols to maintain full connectivity across the network.

Technologies and Protocols Used

EIGRP for dynamic routing between routers

DHCP for automatic IP address assignment

DNS for domain name resolution

HTTP for internal web hosting

Telnet (VTY lines) for remote router management

Subnetting and structured IP addressing

IP Addressing Scheme

WAN Links (Router-to-Router):

192.168.1.0 – 192.168.8.0

LAN Networks:

172.16.1.0 – 172.16.16.0

Subnet masks were adjusted based on the number of devices in each LAN to optimize address usage.

Key Features

Dynamic routing using EIGRP

Multiple DHCP pools configured per subnet

DNS-based website access:

www.aot.com

www.jjk.com

Remote access to routers via Telnet

Successful end-to-end connectivity across all networks

Testing and Validation

The following validation steps were performed:

Ping tests for connectivity verification

DNS lookup testing

HTTP web access through browser

Remote login using Telnet

Learning Outcomes

Enterprise network topology design

Dynamic routing configuration

Automated IP management

Network service deployment

Remote administration techniques

Future Improvements

Implement SSH instead of Telnet

Add Access Control Lists (ACL)

Introduce VLAN segmentation

Improve hierarchical network design

Author

Gagandeep Kaur
