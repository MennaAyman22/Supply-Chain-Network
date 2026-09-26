# Supply Chain Network — Cisco Packet Tracer / CCNA Project

Multi-site Supply Chain Network design, addressing, configuration, and verification,
built and simulated in Cisco Packet Tracer.

## Overview
The network connects two headquarters (HQ1, HQ2), a DHCP-served Users Network, and an
ISP Office / Server Farm site, all interconnected through a central core router over a
simulated public WAN running OSPF (Area 0).

## Key Features
- VLAN segmentation at both HQ sites
- Inter-VLAN routing: Multilayer Switch (HQ1) and Router-on-a-Stick (HQ2)
- Single-area OSPF across the entire network
- NAT/PAT (Overload) and Static NAT for published servers
- DHCP server for the Users Network
- EtherChannel (Port-Channel) link bundling at HQ2
- SSH-secured administrative access

## Files
- Supply Chain Network.pkt — Cisco Packet Tracer project file
- Supply_Chain_Network_Documentation.pdf — full design & configuration report
- Screenshot (228).png — network topology diagram

## Author
Prepared by Menna Ayman
Supervised by Eng. Saher Waleed
