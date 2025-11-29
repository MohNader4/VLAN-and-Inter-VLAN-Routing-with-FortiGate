VLAN-and-Inter-VLAN-Routing-with-FortiGate

Project Overview
This project focuses on designing and implementing a segmented Layer 2 and Layer 3 network using VLANs, inter-VLAN routing, and FortiGate firewall integration.

The network was built and tested across three consecutive phases, each contributing to the final architecture.
The project was divided into four weeks:

Week 1: VLAN Configuration Basics

Tasks included creating and configuring two VLANs, assigning them to ports and IPs, configuring inter-VLAN routing, and drawing a complete logical network diagram.

Two VLANs were created:

VLAN_Accounting

VLAN_HR

Their respective IP addresses and administrative access were configured as shown in the Week 1 document PDF uploaded within the repository.

Week 2: FortiGate Integration for VLANs

In this phase, VLAN interfaces were created on the FortiGate firewall, and firewall policies were implemented to validate inter-VLAN communication.

Full details on firewall policies and inter-VLAN communication testing are provided in the Week 2 document included in the repository.

Week 3: Advanced VLAN Features & Testing

This phase involved implementing VLAN trunking and testing full connectivity across the VLANs through the FortiGate.

Test:
Ping communication between the two VLANs located on completely separate networks, but connected via a trunk to the same FortiGate port.

Result:
Successful ping in both directions.
This verified that the firewall policies allow bidirectional communication and that trunking was successfully implemented.

Final Deliverables

Full VLAN diagram

All switch configurations

FortiGate VLAN and policy configuration

Trunk setup and testing results

Final PDF report

Presentation slides

Conclusion

The final setup is scalable and ready for future enhancements such as VLAN-based security zones, DHCP relaying, and advanced FortiGate UTM features.

Made By
Mohamed Ayman
Mohammed Nader
Moaz Mahmoud
Osama Ahmed



