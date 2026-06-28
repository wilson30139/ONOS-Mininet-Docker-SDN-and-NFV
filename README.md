## Course
- Name: Software Defined Networks and Network Function Virtualization
- Instructor: Chien-Chao Tseng

## Project 1 and 2
- Project 1 and 2 cover the installation of ONOS and Mininet.
- They include the setup of the experiment environment used in later projects.
- They invovle basic observations of the OpenFlow protocol and Flow Rule installation.
- Since these topics are foundational, they are not included in detail in this repository.

## [Project 3: SDN-enabled Learning Bridge (SDN)](https://github.com/wilson30139/ONOS-Mininet-Docker-SDN-and-NFV/tree/main/Project%203)
- An SDN-enabled Learning Bridge shifts MAC address learning from traditional switches to a centralized SDN controller.
- It shifts packet forwarding decisions from trational switches to the SDN controller.
- The switch is responsible only for forwarding packets based on flow rules installed by the controller.
- The controller manages both learning and forwarding behavior in a centralized manner.

## Project 4: Unicast DHCP Application (SDN)
- A Unicast DHCP Application uses the Dynamic Host Configuration Protocol (DHCP) to dynamically design IP address to hosts.
- It uses unicast transmission during part or all of the DHCP communication process.
- It reduces reliance on broadcast-based DHCP message exchange when possible.
- It is typically used to improve efficiency in DHCP communication.

## Project 5: Proxy ARP (SDN)
- In this project, the SDN controller acts as a Proxy ARP entity.
- The controller responds to ARP requests on behalf of destination hosts.
- It enables communication without requring direct ARP resolution between hosts.
- The controller effectively handles ARP reply behavior to simplify host communication.

## Project 6: Software Router and Containerization (NFV)
- Software Router and Containerization refers to deploying a software-based router inside containers.
- It enables flexible deployment of routing functions.
- It improves resource utilization efficiency.
- It supports scalable network services.
- It is commonly used in modern cloud-native and SDN environments.

## Final Project: SDN Network as Virtual Router (SDN and NFV)
- SDN Network as Virtual Router is an SDN architecture.
- The entire network operates as a single virtual router.
- The SDN controller makes centralized routing decisions.
- Switches forward packets based on installed flow rules.
- It abstracts the physical network into a logically unified routing system.
<p align="center">
  <img width="1886" height="931" alt="Screenshot 2026-06-28 182223" src="https://github.com/user-attachments/assets/bedb530c-33d4-422c-ad0a-cee8b91690d3" />
  <strong>Figure 1: Final Project Network Topology</strong>
</p>
