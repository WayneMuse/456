# Networking Security Project - CPSC 456

## Project Overview

This project focuses on implementing and securing a network topology using routers, firewalls, and security configurations. It includes detailed testing of network connectivity, security policies, and firewall rules. The project was completed following industry best practices and security frameworks.

## Contents

### 1. Network Topology & Connectivity
- **Topology Diagram**: A visual representation of the network architecture.
- **Connectivity Testing**: Verifying communication between hosts using `ping` tests.
  - UbuntuDockerGuest-1 ↔ UbuntuDockerGuest-2
  - UbuntuDockerGuest-2 ↔ UbuntuDockerGuest-3
  - UbuntuDockerGuest-3 ↔ UbuntuDockerGuest-1
- **Configuration Files**: Router configurations for different network setups.

### 2. Firewall Configuration & Security Policies
- **Firewall Setup**: Implemented using pfSense.
- **Security Features:**
  - **IP Address Assignment**: DHCP server setup.
  - **Anti-Spoofing Protection**: Using `hping3` to simulate spoofing attacks.
  - **Traffic Filtering Rules**:
    - Block all outgoing ICMP packets.
    - Block traffic from specific IP ranges (Russia & China).
    - Allow HTTPS traffic only to `www.fullerton.edu` while blocking all other HTTPS sessions.
- **Logging & Monitoring**:
  - Capturing logs for security rule enforcement.
  - Analyzing network behavior using `traceroute` and `ping` scripts.

## Configuration Files & Resources
- **Router Configurations**: Available for multiple network setups.
- **Firewall Rules**: Implemented and tested through multiple security scenarios.

### 🔗 **Access Configuration Files**
Configuration files for different parts of the project can be accessed [here](https://drive.google.com/drive/folders/1oRhSBPHWUaLXZ-YvQA6DZuQnUiygRzKU?usp=sharing).

## Testing & Results
- Connectivity tests confirmed full network reachability.
- Firewall successfully blocked unauthorized traffic while allowing essential communications.
- Security measures effectively prevented spoofing attacks and restricted unwanted access.
