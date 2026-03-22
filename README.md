# Enterprise Network Infrastructure Design

## Overview
Designed and simulated a scalable enterprise network using OSPF, VLANs, and NAT.

## Project Context
This project simulates a real-world enterprise network environment similar to telecommunications and infrastructure systems.

## Key Features
- Multi-router enterprise network topology
- Dynamic routing using OSPF for automatic path selection
- VLAN segmentation to reduce broadcast domains
- Inter-network communication enabled through routing protocols
- External connectivity using NAT for internet access

## Tools Used
- Cisco Packet Tracer

## Outcome
Improved network scalability by eliminating static routing and enabling efficient communication between segmented networks.

## OSPF Routing Implementation

### Objective
Configured OSPF dynamic routing to enable automatic route exchange between multiple network segments.

### Implementation
- Enabled OSPF routing protocol on routers
- Advertised network ranges using OSPF
- Established neighbour relationships between routers

### Outcome
- Achieved automatic route updates
- Reduced need for manual routing configuration
- Improved network scalability and efficiency

  ## VLAN and Inter-VLAN Routing

### Objective
Implemented VLAN segmentation to separate network traffic and configured inter-VLAN routing to enable communication between different network segments.

### Implementation
- Created VLANs to segment network traffic
- Assigned switch ports to specific VLANs
- Configured trunk links between switches and routers
- Implemented router-on-a-stick for inter-VLAN communication

### Outcome
- Reduced broadcast domains
- Improved network security and traffic management
- Enabled efficient communication between VLANs

## Static Routing Configuration

### Objective
Configured static routing to enable communication between different network segments in a controlled and predictable manner.

### Implementation
- Defined static routes on routers for specific destination networks
- Configured next-hop IP addresses for routing paths
- Verified connectivity using ping and routing tables

### Outcome
- Established reliable communication between networks
- Enabled controlled routing behaviour
- Provided foundation for understanding dynamic routing protocols

## NAT and PAT Configuration

### Objective
Implemented Network Address Translation (NAT) and Port Address Translation (PAT) to enable internal network devices to access external networks.

### Implementation
- Configured NAT to translate private IP addresses to public IP addresses
- Implemented PAT for multiple devices to share a single public IP
- Defined inside and outside interfaces
- Verified connectivity to external networks

### Outcome
- Enabled internet access for internal devices
- Improved IP address utilisation
- Simulated real-world enterprise network behaviour
  
## Author
Swati Clarice Xalxo
