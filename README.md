# Three-Site-Enterprise-Network-WAN-Routing-Lab
Designed and configured a multi-site enterprise network in Cisco Packet Tracer connecting NJ, NY, and a branch site using routers, multilayer switches, VLANs, inter-VLAN routing, trunking, EtherChannel, static routing, DNS, HTTP services, and point-to-point WAN links.

## Overview

This project demonstrates the design and configuration of a multi-site enterprise network using Cisco Packet Tracer.

The network connects three separate locations through routed WAN links. Each location contains local users and switching infrastructure, while the primary sites also provide shared network services such as DNS and HTTP.

The purpose of the project was to practice enterprise network design, VLAN segmentation, Layer 2 and Layer 3 switching, routing between remote networks, and end-to-end connectivity troubleshooting.

## Network Architecture

The topology consists of three locations:

- New Jersey site
- New York site
- Branch/remote site

Routers provide connectivity between the individual sites, while multilayer switches provide Layer 3 routing within the local networks.

The environment includes:

- Cisco routers
- Multilayer switches
- Layer 2 switching
- Multiple client laptops
- DNS server
- Multiple HTTP/web servers
- Point-to-point WAN connections

## Networking Concepts Implemented

- VLAN configuration
- Switched Virtual Interfaces (SVIs)
- Inter-VLAN routing
- Layer 2 and Layer 3 switching
- 802.1Q trunking
- EtherChannel
- Static routing
- IPv4 addressing
- /30 point-to-point subnetting
- DNS services
- HTTP services
- Multi-site WAN connectivity
- Network troubleshooting

## New Jersey Site

The New Jersey site contains multiple client networks, multilayer switches, an HTTP server, and a DNS server.

VLANs and SVIs were configured to separate user networks and provide communication between subnets.

Trunk connections were used between switches, and EtherChannel was implemented to combine multiple physical switch links into a logical connection.

## New York Site

The New York site contains multiple VLANs, client systems, and web servers.

Multilayer switching provides inter-VLAN routing, while the site router provides connectivity to the remote networks.

HTTP services were configured on the servers and tested from client devices.

## Remote Branch Site

A third branch network was added to expand the enterprise topology.

The branch includes a multilayer switch, multiple client devices, and a router connecting the branch to the main enterprise WAN.

This extension demonstrates how an additional remote office can be integrated into an existing enterprise network.

## WAN Routing

Routers connect the individual locations using point-to-point links.

Static routing was configured so that devices located in different networks and sites could communicate.

Point-to-point addressing was subnetted appropriately to conserve IPv4 address space.

## Network Services

The environment includes:

- DNS services
- HTTP/web services
- Internal client-to-server communication

DNS allows clients to resolve configured hostnames, while HTTP servers provide application/web services across the network.

## Testing and Verification

The network was tested to verify:

- Local VLAN connectivity
- Inter-VLAN routing
- Communication between remote sites
- Router-to-router connectivity
- Static route operation
- DNS resolution
- HTTP server accessibility
- Client-to-server communication
- End-to-end network connectivity
