# Enterprise Network Topology

## Overview

The proposed enterprise network for GreenFields Logistics Ltd. adopts a hierarchical three-tier architecture to provide high availability, scalability, performance, and simplified management.

The design separates the Core, Distribution, and Access layers, ensuring efficient traffic flow and supporting future expansion.

---

# Network Architecture

The enterprise network consists of the following components:

- Dual Internet Service Providers (Primary and Backup)
- Cisco ISR Edge Router
- Cisco Firepower Next-Generation Firewall
- Cisco Catalyst 9500 Layer 3 Core Switch
- Cisco Catalyst 9200 Access Switches
- Enterprise Servers
- Wireless Access Points
- CCTV Infrastructure
- End User Devices

---

# Topology Layers

## Core Layer

The Core Layer provides high-speed routing between VLANs and connects the enterprise network to the Internet.

Devices:

- Cisco Catalyst 9500 Layer 3 Switch

Responsibilities:

- Inter-VLAN Routing
- High-speed Backbone Connectivity
- Redundancy
- Network Availability

---

## Distribution Layer

The Distribution Layer aggregates traffic from each floor and enforces network policies.

Responsibilities:

- Traffic Filtering
- ACL Enforcement
- VLAN Routing
- QoS Policies

---

## Access Layer

The Access Layer connects end-user devices.

Connected Devices:

- Desktop Computers
- Printers
- IP Phones
- Wireless Access Points
- CCTV Cameras

---

# Internet Connectivity

The enterprise uses two Internet Service Providers.

- Primary ISP
- Backup ISP

Automatic failover ensures continuous connectivity.

---

# Security Components

Security is implemented using:

- Cisco Firepower Firewall
- Access Control Lists
- Network Address Translation
- VLAN Segmentation

---

# Design Benefits

- High Availability
- Improved Security
- Better Performance
- Simplified Management
- Future Scalability
