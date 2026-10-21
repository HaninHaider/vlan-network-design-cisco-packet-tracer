# vlan-network-design-cisco-packet-tracer
project designing and testing a VLAN-based network in Cisco Packet Tracer, including DHCP, web services and inter-VLAN routing.

# VLAN Network Design – Cisco Packet Tracer

This project was completed as part of my Computer Systems Architecture (4301COMP) coursework at Liverpool John Moores University.

The aim was to design, configure and test a small network using VLANs, DHCP and web services in Cisco Packet Tracer.

## Project Overview

I designed a network consisting of two VLANs, using one router, one switch, two servers and four PCs.

The network was divided into:

- **VLAN 10:** DHCP server, PC1 and PC2, using automatic IP address allocation.
- **VLAN 20:** Web server, PC3 and PC4, using static IP addresses.

The router was configured to allow communication between the VLANs, enabling devices on both networks to access the web server.

## Implementation

The project involved:

- Configuring two separate VLANs on a Cisco switch.
- Setting up a DHCP server to automatically assign IP addresses.
- Configuring static IP addresses and default gateways.
- Implementing inter-VLAN routing.
- Setting up a web server with HTTP services.
- Testing connectivity between devices.

## Testing

I tested the network in Cisco Packet Tracer to check that:

- PCs in VLAN 10 received IP addresses from the DHCP server.
- Devices could communicate with the web server using ping commands.
- All four PCs could access the web server's homepage.

The coursework report includes screenshots documenting the configuration and testing.

## Tools and Technologies

- Cisco Packet Tracer
- VLAN Configuration
- DHCP
- TCP/IP Networking
- Inter-VLAN Routing
- HTTP Web Services

## What I Learned

This project gave me practical experience in configuring and troubleshooting a small network.

It helped me develop a better understanding of IP addressing, network segmentation, routing and how different network services communicate. I also gained experience testing network connectivity and identifying limitations in a design.

## Coursework

**Module:** 4301COMP – Computer Systems Architecture


**Academic Year:** 2025–2026
