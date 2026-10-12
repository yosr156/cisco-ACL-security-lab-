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

### ACL Implementation and Testing

### . Extended ACL
Initially, an Extended Access Control List (ACL) was configured to filter network traffic based on source IP address, destination IP address, and protocol. It was used to block ICMP traffic between the HR and Students departments and restrict Students' access to the server.

### . Removing the Extended ACL
After testing the Extended ACL, it was removed from the router configuration to allow the implementation of a Standard ACL.

### . Standard ACL
A Standard ACL was then configured to filter traffic based only on the source IP address. This allowed me to understand the differences between Standard and Extended ACLs and how ACL placement affects traffic filtering.

### . Learning Outcomes
- Configuring and testing Extended ACLs.
- Removing an ACL from a router interface and configuration.
- Configuring and applying Standard ACLs.
- Understanding the differences between Standard and Extended ACLs.
- Verifying ACL behavior using Cisco IOS commands.
### .Author
Networking student interested in network administration and systems.
