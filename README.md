# Computer Networks Project - Cisco Packet Tracer Implementation
# Overview
This repository contains the configuration files and documentation for a comprehensive computer networks project implemented using Cisco Packet Tracer during the 5th semester. 
The project involves the design and configuration of a complex network with multiple blocks, incorporating various routing protocols, VLANs, DHCP, NAT, and security measures.

# Project Structure
The project is organized into four blocks.
![image](https://github.com/LaibaZaffar/Computer-Networks/assets/150477947/28182c8e-0a61-4721-9d49-b54ec6248274)

The following steps were performed to implement the network:

## 1. VLSM Configuration:
Utilized Variable Length Subnet Masking (VLSM) to efficiently allocate IP addresses based on the given number of required hosts per subnet for each group.

## 2. Routing Protocols:
Used OSPF with area 1 in the second block, RIP in the third block, and OSPF with area 0 in the last block.
EIGRP was implemented in the first block for routing.

## 3. Redistribution:
Configured redistribution on Router8 and Router21 to connect OSPF with OSPF and OSPF with RIP.

## 4. DHCP Configuration:
Configured DHCP servers to allocate IP addresses to hosts in OSPF area 1 and RIP.
Hosts in OSPF area 0 obtained IP addresses from "DHCP Server for VLAN's."

## 5. NAT Implementation:
Implemented NAT on a designated router with Network G, using the provided public IP address for translation.

## 6. VLAN Configuration:
Created VLANs as specified in the scenario.
Configured VTP, designating the 3560 switch as the server and others as clients. The 3560 switch acts as a multi-level switch.

## 7. Inter-VLAN Communication:
Established Inter-VLAN communication between VLAN 20 and VLAN 40 using router-on-a-stick technique.

## 8. Security Measures:
Implemented IP security between every router in the network.

## 9. Access Control:
Configured access control to restrict specific hosts' access to TFTP server, Data server, and other designated hosts.

## 10. Routing for VLANs:
Implemented VLAN routing using the router-on-a-stick technique.

# Instructions for Running the Simulation
1. Open the project file in Cisco Packet Tracer.

2. Start the simulation to observe the configured network.

3. Explore the network according to the specified instructions and scenarios.

"Feel free to reach out for any further clarification or assistance."💕

# Happy Networking! ;)
