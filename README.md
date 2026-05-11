# Secure Enterprise Network Design (CTC 492)

## Overview
This project demonstrates the design and simulation of a secure and scalable enterprise network using VLAN segmentation, inter-VLAN routing, access control lists (ACLs), and Network Address Translation (NAT).

The network was developed and tested using Cisco Packet Tracer.

## Features
- VLAN segmentation across multiple departments
- Inter-VLAN routing using router-on-a-stick
- Role-based access control using ACLs
- Guest network isolation
- NAT for internet connectivity

## How to Run the Project
1. Install Cisco Packet Tracer
2. Download the file: Final_Project.pkt
3. Open the file in Packet Tracer
4. View and test the network using device CLI

## Testing
The following test cases were validated:
- HR → Server (Allowed)
- Sales → HR (Blocked)
- Management → HR (Allowed)
- Guest → Internal Network (Blocked)
- Internet connectivity via NAT (Successful)

## Files Included
- Final_Project.pkt
- Project Report PDF
- Screenshots

## Author
Raul Lozoya
