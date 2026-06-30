# Network Emulation

## [Course](https://timetable.nycu.edu.tw/?r=main/crsoutline&Acy=112&Sem=1&CrsNo=535607&lang=en-us)
- Name: Software Defined Networks and Network Function Virtualization
- Instructor: Professor Chien-Chao Tseng Professor

## Introduction
This repository contains a collection of network emulation projects developed using ONOS, Mininet, and Docker. It provides a programmable networking environment for exploring Software-Defined Networking (SDN) and Network Functions Virtualization (NFV) through virtual network topologies and software-based network functions.

The projects demonstrates the implementation of SDN applications, OpenFlow-based packet forwarding, software routers, virtual routers, and containerized network functions, highlighting how SDN controllers and virtualized technologies can be integrated in modern network architectures.

## Technologies
- ONOS
- Mininet
- Docker
- OpenFlow
- SDN
- NFV

## Overview
| Project | Topic | Category |
|----------|-------|----------|
| [Project 1](#project-1-and-2) | ONOS and Mininet Installation | SDN |
| [Project 2](#project-1-and-2) | OpenFlow Protocol Observation and Flow Rule Installation | SDN |
| [Project 3](#project-3-sdn-enabled-learning-bridge-sdn) | SDN-enabled Learning Bridge | SDN |
| [Project 4](#project-4-unicast-dhcp-application-sdn) | Unicast DHCP Application | SDN |
| [Project 5](#project-5-proxy-arp-sdn) | Proxy ARP | SDN |
| [Project 6](#project-6-software-router-and-containerization-nfv) | Software Router and Containerization | NFV |
| [Final Project](#final-project-sdn-network-as-virtual-router-sdn-and-nfv) | SDN Network as Virtual Router | SDN and NFV |

## Project 1 and 2
- Installed and configured the ONOS controller and Mininet.
- Built the experimental environment used throughout subsequent projects.
- Explored the OpenFlow protocol and observed Flow Rule installation.
- Since these projects focus on foundational setup, they are not included in detail in this repository.

## [Project 3: SDN-enabled Learning Bridge (SDN)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Project%203)
- Implemented an SDN-enabled learning bridge using ONOS.
- Centralized MAC address learning in the SDN controller.
- Installed OpenFlow flow rules dynamically for packet forwarding.
- Replaced traditional switch-based learning with controller-managed forwarding.

## [Project 4: Unicast DHCP Application (SDN)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Project%204)
- Developed a unicast DHCP application on the ONOS controller.
- Dynamically assigned IP addresses to hosts using DHCP.
- Utilized unicast communication to reduce broadcast traffic during DHCP message exchange.
- Improved the efficiency of DHCP communication within the SDN environment.

## [Project 5: Proxy ARP (SDN)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Project%205)
- Implemented a Proxy ARP application on the SDN controller.
- Responded to ARP requests on behalf of destination hosts.
- Eliminated the need for direct ARP resolution between hosts.
- Simplified host communication through centralized ARP management.

## [Project 6: Software Router and Containerization (NFV)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Project%206)
- Deployed a software router using Docker containers.
- Implemented virtualized routing functions in a containerized environment.
- Improved deployment flexibility and resource utilization.
- Demonstrated container-based network function virtualization (NFV).
<p align="center">
  <img width="1390" height="633" alt="Project 6 Network Topology" src="https://github.com/user-attachments/assets/4290fa2f-304c-412e-a601-9d9edf51101f" />
  <strong>Figure 1: Project 6 Network Topology</strong>
</p>

## [Final Project: SDN Network as Virtual Router (SDN and NFV)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Final%20Project)
- Designed an SDN architecture in which the network operates as a single virtual router.
- Centralized routing decisions in the ONOS controller.
- Forwarded packets through OpenFlow flow rules installed on switches.
- Abstracted the physical network into a logically unified routing system.
- Integrated SDN control with virtualized network functions.
<p align="center">
  <img width="1886" height="931" alt="Screenshot 2026-06-28 182223" src="https://github.com/user-attachments/assets/bedb530c-33d4-422c-ad0a-cee8b91690d3" />
  <strong>Figure 2: Final Project Network Topology</strong>
</p>

## Learning Outcomes
Through these projects, I gained hands-on experience in:
- Software-Defined Networking (SDN)
- Network Functions Virtualization (NFV)
- ONOS controller application development
- OpenFlow protocol and Flow Rule management
- Network emulation with Mininet
- Containerized network functions using Docker
- Software router deployment
- Virtual network architecture design
