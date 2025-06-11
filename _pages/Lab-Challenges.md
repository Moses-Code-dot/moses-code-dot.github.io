---
title: "Lab Challenges"
permalink: /lab-challenges/
layout: single
author_profile: true
---

# Lab Challenge 1
 **HTB Academy: Introduction to Network Traffic Analysis**
 
 **Problem statement:** 
 aims to teach beginners how to analyze network traffic to identify suspicious activities, understand protocols, and detect potential security threats. The challenge is to equip learners with foundational skills to capture, interpret, and analyze network packets effectively.

 **Approach:**
 - Learning Fundamentals: Study core concepts of network protocols (e.g., TCP/IP, HTTP, DNS) and packet structures.
 - Packet Capture: Use tools to capture network traffic from simulated environments or provided PCAP files.
 - Analysis: Inspect packets to identify patterns, anomalies, or malicious activities (e.g., unauthorized access, data exfiltration).
 - Practical Exercises: Complete hands-on tasks like filtering traffic, reconstructing sessions, or identifying specific protocol behaviors.
 - Reporting: Summarize findings to understand network behavior or security incidents.

**Tools Used:**
  - HTB Platform: Provides interactive labs and challenges for practical application.
-------

# Lab Challenge 2
 **VLANs and Secure Switch Configuration**

 **Problem Statement:**
 VLANs and Secure Switch Configuration focuses on teaching learners to design, implement, and secure VLANs to segment network traffic and mitigate security risks. The challenge is to configure VLANs and switches to ensure proper traffic isolation, prevent unauthorized access, and protect against attacks like VLAN hopping or spoofing while maintaining network functionality.
  
  **Approach:**
  - VLAN Setup: Define and configure VLANs to segment network traffic (e.g., by department or device type) to enhance security and reduce broadcast domains.
  - Secure Switch Configuration:
     - Assign access ports to specific VLANs and disable unused ports or move them to a "black hole" VLAN.
     - Configure trunk ports with a non-default native VLAN (not VLAN 1) and restrict allowed VLANs to prevent VLAN hopping.
     - Disable Dynamic Trunking Protocol (DTP) to block unauthorized trunking.
     - Implement port security (e.g., 802.1X, MAC address filtering) to control device access.
     - Apply ACLs to restrict inter-VLAN traffic and enable DHCP snooping/ARP inspection to counter spoofing.
  - Documentation: Maintain network diagrams and configuration logs for traceability.

**Tools Used:**
  -Packet Tracer
