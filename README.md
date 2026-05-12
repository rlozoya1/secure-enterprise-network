# Secure Enterprise Network Design (CTC 492)

## Overview
This project demonstrates the design and simulation of a secure and scalable enterprise network using VLAN segmentation, inter-VLAN routing, access control lists (ACLs), and Network Address Translation (NAT).

The network was built and tested using Cisco Packet Tracer.

---

## How to Run the Project
1. Install Cisco Packet Tracer
2. Download the file: Final_Project.pkt
3. Open the file in Packet Tracer
4. Click on devices (Router, Switches, PCs)
5. Use CLI to verify configurations:
   - show vlan brief
   - show ip interface brief
   - show access-lists
   - show ip nat translations

---

## Features
- VLAN segmentation across departments
- Inter-VLAN routing using router-on-a-stick
- Role-based access control using ACLs
- Guest network isolation
- NAT for internet connectivity

---

## Testing and Results

### Test Case 1: HR to Server
Result: Successful communication  
Explanation: Inter-VLAN routing is working correctly.

### Test Case 2: Sales to HR
Result: Blocked  
Explanation: ACL correctly restricts unauthorized access.

### Test Case 3: Management to HR
Result: Successful  
Explanation: Authorized access is allowed.

### Test Case 4: Guest to Internal Network
Result: Blocked  
Explanation: Guest VLAN is isolated from internal networks.

### Test Case 5: Internet Access via NAT
Result: Successful  
Explanation: NAT overload allows private IP addresses to access external networks.

---

## Files Included
- Final_Project.pkt (Packet Tracer network)
- Project_Report.pdf
- Screenshots folder

---

## Author
Raul Lozoya
