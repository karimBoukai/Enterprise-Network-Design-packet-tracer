# Next Generation University Network

## Overview

This project presents the design and implementation of a multi-campus university network using Cisco Packet Tracer. The network connects the Besiktas Main Campus and the Galata Branch Campus through a WAN infrastructure while providing secure communication, VLAN segmentation, inter-VLAN routing, server services, and security-focused network architecture.

The project was developed as part of the Network Systems Engineering course and demonstrates practical networking concepts including routing, switching, subnetting, VLAN implementation, WAN connectivity, security controls, and network validation.

---

## Project Objectives

* Design a scalable university network architecture.
* Connect multiple campuses through a WAN topology.
* Implement VLAN segmentation for different departments.
* Configure inter-VLAN routing using a Layer 3 switch.
* Deploy core services including Web, FTP, and Email.
* Implement static routing between campuses.
* Apply security concepts such as VPNs, ACLs, IAM, and Zero Trust.
* Validate end-to-end connectivity across the entire network.

---

## Network Architecture

### Main Campus (Besiktas)

The headquarters campus contains:

* Espresso Lab
* Staff Network
* Digital Lab
* PC Lab
* PC Lab – A Block
* Staff – A Block
* Dental Lab
* Server Network

### Branch Campus (Galata)

The branch campus contains:

* Staff Network
* Architecture Studio

### WAN Connectivity

The two campuses are interconnected using a point-to-point WAN link with static routing between routers.

---

## Technologies Used

* Cisco Packet Tracer
* Cisco Routers
* Cisco Layer 3 Switches
* Cisco Access Switches
* VLANs
* Static Routing
* Inter-VLAN Routing
* WAN Design
* ACL Concepts
* VPN Concepts
* Cloud Connectivity Concepts

---

## VLAN Structure

| VLAN | Department          |
| ---- | ------------------- |
| 10   | Espresso Lab        |
| 20   | Staff               |
| 30   | Digital Lab         |
| 40   | PC Lab              |
| 50   | PC Lab – A Block    |
| 60   | Staff – A Block     |
| 70   | Dental Lab          |
| 80   | Servers             |
| 90   | Branch Staff        |
| 100  | Architecture Studio |

---

## Services Implemented

### Web Server

Provides university web-based services.

### FTP Server

Provides file transfer services for academic and administrative operations.

### Email Server

Connected through the Cloud/ISP segment to simulate external email services.

---

## Routing Design

The network uses:

* Layer 3 Switching for inter-VLAN routing at the Main Campus.
* Static Routing between Main Campus and Branch Campus.
* Point-to-point WAN connectivity using /30 subnets.

This design provides simple, reliable, and easily verifiable routing suitable for a university environment.

---

## Security Features

The project incorporates several security concepts:

* VLAN Segmentation
* Access Control Lists (ACLs)
* Identity and Access Management (IAM)
* Zero Trust Principles
* VPN Architecture
* Secure Administrative Access
* Log Management Concepts
* Least Privilege Access

---

## VPN Design

### Site-to-Site VPN

Designed conceptually to secure communication between campuses.

### Remote Access VPN

Allows faculty and staff to securely access university resources from external locations.

---

## Hybrid Cloud Architecture

The network follows a hybrid model:

### On-Premises

* Core routing and switching
* Internal university services
* Local authentication systems

### Cloud

* Email services
* Backup storage
* Disaster recovery services
* Learning Management System scalability

---

## Disaster Recovery and Business Continuity

The project includes:

* Backup strategies
* Disaster Recovery planning
* Business Continuity considerations
* Risk assessment
* Service prioritization (RTO/RPO targets)

---

## Testing and Validation

The network was validated using:

* End-to-end ping tests
* VLAN communication tests
* Inter-VLAN routing tests
* WAN connectivity verification
* Service reachability testing
* Routing table verification
* Trunk validation

Successful tests confirmed communication between:

* Main Campus VLANs
* Branch Campus VLANs
* FTP Server
* Web Server
* Email Services
* WAN-connected campuses

---

## Learning Outcomes

Through this project, the following concepts were applied:

* Network Design
* Subnetting
* VLAN Configuration
* Layer 2 Switching
* Layer 3 Routing
* Static Routing
* WAN Technologies
* Security Architecture
* VPN Design
* Cloud Networking
* Disaster Recovery Planning
* Network Troubleshooting

---

## Team Members

* Ahmed Saeedy
* Kerim Elmali (Karim Boukai)
* Naki Erim Ozer
* Abdulsalam Alhashmi
* Yusuf Suha Yilmazer

---

## Author

Karim Boukai

Software Engineering Student
Bahçeşehir University

---

## Course

Network Systems Engineering

---

## Academic Notice

This project was developed for educational and academic purposes as part of a university networking course. The design demonstrates practical implementation of networking concepts using Cisco Packet Tracer and industry-standard network engineering principles.
