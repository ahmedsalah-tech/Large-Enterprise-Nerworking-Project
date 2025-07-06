## Network Design and Implementation for a New Office Building

This document provides a high-level overview of a network design and implementation project for a new office building, serving as the final project for a networking class. The goal was to create a robust, scalable, and redundant network infrastructure for 600 staff members.

### **Project Overview**

The project focused on designing and implementing a logical network for a new office building, ensuring it meets current business needs and is future-proofed. Key aspects included a hierarchical design with redundancy, comprehensive IP addressing, and various network services.

### **Key Features Implemented**

*   **Redundant Hierarchical Design:** Utilized two routers and two multilayer switches for high availability.
*   **Dual ISP Connectivity:** Ensured internet redundancy through connections to two Internet Service Providers.
*   **VLAN Segmentation & Inter-VLAN Routing:** Departments are isolated into different VLANs with communication enabled via multilayer switches.
*   **Dynamic & Static IP Allocation:** DHCP for most devices, static IPs for server room equipment.
*   **OSPF Routing:** Implemented OSPF for efficient route advertisement across the network.
*   **Security Measures:** Configured SSH for secure remote access and port security for specific departments.
*   **NAT (PAT):** Enabled network address translation for outbound internet access.
*   **Wireless Network:** Provided wireless connectivity for all departments.

### **IP Addressing**

The network uses a base of `172.16.1.0` with detailed subnetting for departments and inter-device links. Public IP addresses (`195.136.17.0/30` range) are used for ISP connections.

### **Technologies Used**

Cisco Packet Tracer(v8.2.2) was used for design and simulation. Core technologies include VLANs, DHCP, OSPF, SSH, PAT, ACLs, and Port Security.

**For more detailed information, including specific IP addressing schemes, configuration steps, and network topology, please refer to the full documentation file.**
