# Network Infrastructure Design

## Project Overview
Design and implementation of an enterprise-style network infrastructure following a **core–distribution–access** architecture.  
This project simulates a real corporate environment, focusing on routing, switching, security, and network services, using Cisco technologies and best practices.

The goal of this lab is to demonstrate practical skills in **network design, configuration, troubleshooting, and documentation**, similar to scenarios found in production environments.

---

## Project Objectives
- Design a scalable and structured enterprise network.
- Implement Layer 2 and Layer 3 switching.
- Configure dynamic routing and redundancy.
- Integrate security and perimeter control.
- Document the network topology and configurations clearly.

---

## Network Architecture
The network follows a **hierarchical model**:

- **Core / Distribution Layer**
  - Cisco 3750-X (Layer 3)
  - Inter-VLAN routing
  - OSPF and BGP routing
- **Access Layer**
  - Cisco 2960-X and 2960-S (Layer 2)
  - VLAN segmentation
  - Access port configuration
- **Edge & Security**
  - Cisco ASA 5508-X (Firewall)
  - Cisco ISR Routers (WAN / Edge connectivity)

---

## Technologies & Protocols Used
- **Switching & Routing**
  - VLANs, Trunking (802.1Q)
  - Inter-VLAN Routing
  - OSPF (Internal routing)
  - BGP (External routing simulation)
- **Security**
  - Cisco ASA Firewall
  - Zone-based traffic control
- **Services**
  - DHCP
  - DNS (logical integration)
- **Management**
  - SSH
  - Network documentation
  - Configuration backups

---

## Lab Components
| Device | Model | Role |
|------|------|------|
| Access Switches | Cisco 2960-X / 2960-S | Layer 2 Access |
| Distribution/Core Switches | Cisco 3750-X | Layer 3 Routing |
| Routers | Cisco 1900 / 1800 Series | Edge / WAN |
| Firewall | ASA 5508-X | Perimeter Security |

---

## Repository Structure
├── configs/
│ ├── access-switches/
│ ├── distribution-core/
│ ├── routers/
│ └── firewall/
├── diagrams/
│ └── network-topology.png
└── README.md
