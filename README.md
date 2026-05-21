# ENTERPRISE-MULTI-SITE-NETWORK-INFRASTRUCTURE-PROJECT

## Project Overview
Designed and implemented an enterprise-grade multi-site network infrastructure using Cisco Packet Tracer simulating real-world enterprise networking between Head Office and Branch Office environments. The project includes VLAN segmentation, Inter-VLAN Routing, OSPF dynamic routing, NAT/PAT, ACL security policies, DHCP Relay, DNS services, HTTP web hosting, SSH remote administration, and WAN connectivity.

---

# Network Topology
<img width="1366" height="717" alt="Network Topology" src="https://github.com/user-attachments/assets/1c43b579-65f7-440a-8651-d4030903dc36" />


---
#  Key Features

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
## Trunking
<img width="1366" height="768" alt="Trunking" src="https://github.com/user-attachments/assets/711a0c11-6c8e-475d-bd90-ee92fdc3abf4" />

## VLAN and Trunk
<img width="1366" height="719" alt="VLAN and Trunk" src="https://github.com/user-attachments/assets/a37b2d5f-9158-4756-bf91-2baa78c80db4" />

## VLAN
<img width="1366" height="728" alt="VLAN" src="https://github.com/user-attachments/assets/708362d0-ff2f-48e8-bf34-89e68b1d3f35" />

## Routing
- Implemented Inter-VLAN Routing using Router-on-a-Stick
- Configured OSPF dynamic routing between routers
- Validated WAN communication between sites
## Router-on-a-stick
<img width="1366" height="768" alt="Router-on-a-stick" src="https://github.com/user-attachments/assets/38b14586-78ba-4f4c-99d3-2d4810cb1e5d" />

## OSPF Routing
<img width="1366" height="704" alt="OSPF" src="https://github.com/user-attachments/assets/a2fe12c2-44b5-4c34-845b-5d92fd1d18b3" />
<img width="1366" height="719" alt="OSPF routes" src="https://github.com/user-attachments/assets/4642ccaf-52c6-4da8-9619-02253f253082" />
<img width="1366" height="711" alt="OSPF configuration" src="https://github.com/user-attachments/assets/81dd64e3-cf31-4d7a-aa13-7909486b5680" />
<img width="1366" height="700" alt="interfaces and sub interfaces" src="https://github.com/user-attachments/assets/fee0e471-aa34-4d3b-be6a-84e85c17e77e" />

## Inter-VLAN Routing
<img width="1366" height="768" alt="inter-VLAN routing" src="https://github.com/user-attachments/assets/5c505b6f-04a4-4f25-9240-325892bb1a20" />

## Network Services
- Configured centralized DHCP Server
- Implemented DHCP Relay using `ip helper-address`
- Configured DNS Server for hostname resolution
- Hosted internal enterprise webpage using HTTP Server
## Web Server
<img width="1366" height="706" alt="Web server" src="https://github.com/user-attachments/assets/95308e3b-8a4c-4a0b-8067-b170b8f42e7e" />
<img width="1366" height="713" alt="company local dns" src="https://github.com/user-attachments/assets/835462a8-2eea-4110-87f6-a9e79fd1b45f" />

## DNS
<img width="1366" height="715" alt="DNS Domain" src="https://github.com/user-attachments/assets/626adb75-6686-4883-adef-bf23eca23509" />
<img width="1366" height="717" alt="DNS" src="https://github.com/user-attachments/assets/0446ac1b-5cda-461d-a8ba-89e6b3f40f65" />

## DHCP
<img width="1366" height="734" alt="DHCP Success HR pc" src="https://github.com/user-attachments/assets/fedc7f91-9fb7-4b2f-8800-03220c07b578" />
<img width="1366" height="719" alt="DHCP Pool" src="https://github.com/user-attachments/assets/3e76659e-b015-4a0b-8fc2-f804118d2032" />
<img width="1366" height="723" alt="DHCP Configuration" src="https://github.com/user-attachments/assets/14e9b810-8e7e-4446-848d-18a9b2269ab6" />

## Security & Remote Access
- Configured ACLs to restrict unauthorized VLAN communication
- Implemented NAT/PAT for private IP translation
- Configured SSH secure remote administration
## ACL
<img width="1366" height="702" alt="ACL test" src="https://github.com/user-attachments/assets/b7e7b7c0-c30f-4817-870c-1355b3d73d13" />
<img width="1364" height="698" alt="ACL configuration (2)" src="https://github.com/user-attachments/assets/8a083e33-1ad0-494a-9614-be0dc9c35b81" />

## NAT
<img width="1366" height="719" alt="NAT Translation" src="https://github.com/user-attachments/assets/12258684-2ecf-4ea7-b7ec-5cb353a36c66" />
<img width="1366" height="768" alt="NAT configuration" src="https://github.com/user-attachments/assets/ac081f53-7e68-4355-8573-20e5d7ffcd88" />

## SSH
<img width="1366" height="715" alt="SSH into HQ Router" src="https://github.com/user-attachments/assets/5a0a7d16-34ca-4070-a1c8-6036a4a38edc" />
<img width="1366" height="728" alt="SSH  configuration" src="https://github.com/user-attachments/assets/eec6ba1a-db82-4fa7-a92c-c7a06eb86260" />

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
