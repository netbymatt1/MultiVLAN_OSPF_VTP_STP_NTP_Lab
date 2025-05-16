# MultiVLAN_OSPF_VTP_STP_NTP_Lab
Cisco Packet Tracer lab with VLAN, VTP, OSPF, NTP and ROAS
- **Multi-VLAN Setup**: VLAN 10, 20, 30 on one network; VLAN 50, 100, 150, 200 on the other.
- **VTP Configuration**: SW1 as the VTP Server, others as Clients.
- **STP Optimization**: SW1 manually set as Root Bridge.
- **ROAS (Router-on-a-Stick)**: R1 and R3 configured with subinterfaces for inter-VLAN routing.
- **OSPF Routing**: All routers are connected and communicating via OSPF (Area 0).
- **NTP Server**: R2 serves as the NTP server.
- **NTP Client Devices**: All routers and switches are synchronized with R2.
- **DTP Disabled**: All DTP settings are turned off for security.
- **Trunk and Access Ports**: Manually assigned as needed.
- **PCs Assigned IPs and Default Gateways**: All PCs are reachable across VLANs.

## Topology Summary

- 3 Routers (R1, R2, R3)
- 8 Switches (SW1 is root bridge and VTP server)
- 14 PCs across 7 VLANs
- NTP synchronization from R2
- End-to-end ping tested
