# ENTERPRISE-MULTI-SITE-NETWORK-INFRASTRUCTURE-PROJECT

## Project Overview
Designed and implemented an enterprise-grade multi-site network infrastructure using Cisco Packet Tracer simulating real-world enterprise networking between Head Office and Branch Office environments. The project includes VLAN segmentation, Inter-VLAN Routing, OSPF dynamic routing, NAT/PAT, ACL security policies, DHCP Relay, DNS services, HTTP web hosting, SSH remote administration, and WAN connectivity.

---

# Architecture Diagram

```text
                                        INTERNET / WAN
                                              |
                                      +----------------+
                                      |   ISP ROUTER   |
                                      | 10.0.0.1 / .5 |
                                      +----------------+
                                        /            \
                                       /              \
                         10.0.0.0/30  /                \ 10.0.0.4/30
                                     /                  \
                    +--------------------+      +--------------------+
                    |     HQ ROUTER      |      |   BRANCH ROUTER    |
                    |  Router-on-a-Stick |      |  Server Gateway    |
                    +--------------------+      +--------------------+
                              |                           |
                           TRUNK                        TRUNK
                              |                           |
                    +----------------+         +-------------------+
                    |   CORE SWITCH  |         |   BRANCH SWITCH   |
                    +----------------+         +-------------------+
                      /            \                     |
                     /              \                 TRUNK
                    /                \                   |
          VLAN 10 HR            VLAN 20 FINANCE   +-------------------+
           192.168.10.0          192.168.20.0     |    SERVER SWITCH  |
                                                   +-------------------+
             +-----------+         +-----------+      /       |       \
             | HR PC1    |         | FIN PC1   |     /        |        \
             | .10       |         | .100      |    /         |         \
             +-----------+         +-----------+  DHCP      DNS       WEB
                                                    SERVER    SERVER    SERVER
                                                 192.168.30.10
                                                 192.168.30.11
                                                 192.168.30.20
```

---

# Key Features

- Multi-site enterprise network topology
- VLAN segmentation for departmental isolation
- Inter-VLAN Routing using Router-on-a-Stick
- OSPF dynamic routing between routers
- WAN connectivity between Head Office and Branch Office
- Centralized DHCP Server with DHCP Relay
- Internal DNS Server for hostname resolution
- Internal HTTP Web Server hosting enterprise webpage
- NAT/PAT configuration for private-to-public IP translation
- ACL-based network traffic filtering and security
- SSH secure remote administration for routers and switches
- 802.1Q trunking between switches
- Enterprise network troubleshooting and connectivity validation

---

# Technologies Used

- Cisco Packet Tracer
- VLANs
- Inter-VLAN Routing
- Router-on-a-Stick
- OSPF
- NAT/PAT
- ACL
- DHCP
- DHCP Relay
- DNS
- HTTP
- SSH
- TCP/IP
- 802.1Q Trunking
- WAN Routing
- Enterprise Networking

---

# Network Design

## Head Office
- HR VLAN
- Finance VLAN
- Core Switch
- Router-on-a-Stick configuration
- SSH-enabled router and switch management

## Branch Office
- Server VLAN
- DHCP Server
- DNS Server
- Internal Web Server

## WAN Infrastructure
- ISP Router connectivity
- OSPF routing between sites
- NAT/PAT implementation
- End-to-end communication between branches

---

# Implemented Configurations

## VLAN & Switching
- Configured VLANs for HR, Finance, and Server departments
- Implemented trunk links using 802.1Q encapsulation
- Configured multi-switch enterprise architecture

## Routing
- Implemented Inter-VLAN Routing using Router-on-a-Stick
- Configured OSPF dynamic routing between routers
- Validated WAN communication between sites

## Network Services
- Configured centralized DHCP Server
- Implemented DHCP Relay using `ip helper-address`
- Configured DNS Server for hostname resolution
- Hosted internal enterprise webpage using HTTP Server

## Security & Remote Access
- Configured ACLs to restrict unauthorized VLAN communication
- Implemented NAT/PAT for private IP translation
- Configured SSH secure remote administration

## Troubleshooting
- Resolved VLAN trunking issues
- Debugged DHCP relay communication
- Validated DNS resolution and web accessibility
- Performed routing and connectivity troubleshooting

---

# Validation & Testing

Successfully validated:

- DHCP IP allocation across VLANs
- DNS hostname resolution using `company.local`
- Inter-VLAN communication
- OSPF route propagation
- NAT/PAT translations
- SSH remote login
- ACL traffic filtering
- Internal web server accessibility
- End-to-end WAN connectivity

---

# Suggested Screenshots

- Full enterprise topology
- OSPF routing table
- NAT translation table
- Successful SSH login
- DHCP successful allocation
- ACL testing
- Web server access using DNS name

---

# Skills Demonstrated

- Enterprise Network Design
- Routing & Switching
- WAN Technologies
- Network Security
- Infrastructure Administration
- Cisco CLI Configuration
- Network Troubleshooting
- TCP/IP Networking
- Secure Remote Administration

---
