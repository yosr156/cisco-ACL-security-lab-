# Cisco ACL Security Lab

## Overview
A network security project developed in Cisco Packet Tracer to practice Access Control Lists (ACLs).

## Objectives
- Block ICMP traffic between HR and Students.
- Prevent Students from accessing the server network.
- Allow HR to access the server.
- Practice standard and extended ACL configuration.

## Network Topology
- 1 Cisco 2911 router
- 3 Cisco 2960 switches
- 8 PCs
- 1 server

## IP Addressing

| Network | Address |
|---|---|
| HR | 192.168.10.0/24 |
| Students | 192.168.20.0/24 |
| Servers | 192.168.30.0/24 |

## Technologies
- Cisco Packet Tracer
- Cisco IOS
- IPv4 addressing
- Standard and extended ACLs
- ICMP and HTTP testing

## Security Policy
- HR is allowed to access the server.
- Students are denied access to the server network.
- ICMP traffic between HR and Students is blocked.

## Testing
Connectivity and ACL rules are verified using ping, HTTP testing, and Cisco IOS commands such as `show access-lists`.

## Author
Networking student interested in network administration and systems.
