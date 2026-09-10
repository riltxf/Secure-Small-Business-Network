Secure Small Business Network
Overview
This project demonstrates the design and configuration of a secure small business network using Cisco Packet Tracer.
Network Components
Cisco 2911 Router
Cisco 2960 Switch
3 PCs
1 Server
Network Segmentation
VLAN Name Purpose
10 EMPLOYEES PC1 and PC2
20 SERVERS SRV1
30 GUEST PC3
Technologies Used
VLANs
802.1Q Trunking
Router-on-a-Stick
Extended ACL
IP Addressing
Network Connectivity Testing
Security Configuration
An Extended ACL named GUEST_RESTRICTION was configured to prevent the Guest network from accessing the Server network.
Guest Network: 192.168.30.0/24
Server Network: 192.168.20.0/24
The ACL blocks traffic from the Guest network to the Server network while allowing other permitted network traffic.
Testing
The network was tested using ICMP Ping:
Guest PC → Server: Blocked
Guest PC → Employee PC: Allowed
These tests verified that the configured ACL security policy was working as intended.
Project Files
The Cisco Packet Tracer .pkt file and project screenshots are included in this repository.
