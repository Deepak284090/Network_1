# Dplink Network Solutions - 5 Floor Network

## Overview
This project presents a network design for Dplink Network Solutions, a mid-sized enterprise with a 5-floor office building. The network is structured to ensure efficient communication, scalability, and performance.

## Network Design Requirements

### 1. Topology Selection
- **Floor 1 & Floor 2:** Ring Topology (Ensures redundancy and fault tolerance)
- **Floor 3 & Floor 4:** Mesh Topology (Provides high reliability and multiple communication paths)
- **Floor 5:** Star Topology (Simple and cost-effective with a central switch)

### 2. IP Addressing Scheme
- **Floor 1:** Class B Private IP (172.168.0.0/16)
- **Floor 2:** Class B Private IP (172.170.0.0/16)
- **Floor 3:** Class C Private IP (192.168.0.0/24)
- **Floor 4:** Class C Private IP (192.168.1.0/24)
- **Floor 5:** Class A Public IP (150.0.0.0/8)

### 3. Routing Strategy
- Static routing is implemented for inter-floor communication.
- Each floor has a designated network address to ensure proper routing and connectivity.
- Routers are used to interconnect floors and manage network traffic efficiently.

## Implementation Details
- Devices include hubs, switches, and routers to accommodate different topology needs.
- Each floor consists of 10 computers connected according to the assigned topology.
- Network segmentation is maintained through proper subnetting.

## Network Diagram
A visual representation of the network topology has been provided.

![Network Diagram](
![Screenshot 2025-03-02 093533](https://github.com/user-attachments/assets/f4f2aaaf-cdf2-400b-a968-6297ff47a4a5))

## How to Use
1. Clone the repository using:
   ```sh
   git clone https://github.com/your-username/dplink-network.git
   ```
2. Review the network diagram and configuration files.
3. Deploy and test the network using simulation software (e.g., Cisco Packet Tracer, GNS3).


## Author
Deepak Kumar Sirsaha


