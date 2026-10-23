# Cisco Packet Tracer 6.1.2.1 — Add Computers to an Existing Network

## Project Overview
Configured two workstations using DHCP and a server using static IPv4 addressing in Cisco Packet Tracer. Verified local network connectivity and troubleshot an incorrect default gateway.

**Platform:** Cisco Packet Tracer  
**Assessment:** 100% (30/30 points)  
**Network:** 172.16.1.0/24

## Network Topology
- BranchOffice router
- BranchSwitch
- PC0 and PC1
- Server0
- Corporate cloud connection

## IP Address Configuration

| Device | IP Address | Subnet Mask | Default Gateway | Addressing |
|---|---|---|---|---|
| PC0 | 172.16.1.1 | 255.255.255.0 | 172.16.1.254 | DHCP |
| PC1 | 172.16.1.2 | 255.255.255.0 | 172.16.1.254 | DHCP |
| Server0 | 172.16.1.100 | 255.255.255.0 | 172.16.1.254 | Static |

DNS server: 209.165.200.226

## Configuration and Verification
1. Enabled DHCP on PC0 and PC1 and verified successful IPv4 assignments.
2. Configured Server0 with a static IPv4 address, subnet mask, default gateway, and DNS server.
3. Tested PC0-to-PC1 connectivity using `ping 172.16.1.2` — four replies, 0% packet loss.
4. Tested PC0-to-Server0 connectivity using `ping 172.16.1.100` — four replies, 0% packet loss.
5. Used Packet Tracer assessment feedback to identify and correct an incorrect server default gateway.
6. Verified final assessment score of 30/30 (100%).

## Skills Demonstrated
- DHCP client configuration
- Static IPv4 addressing
- Subnet masks and default gateways
- Network connectivity validation
- Ping-based troubleshooting
- Cisco Packet Tracer network simulation

## Lessons Learned
Devices on the same local subnet can communicate even when a default gateway is misconfigured. Testing connectivity and reviewing configuration requirements are both important for confirming a correct network setup.

## Evidence
Screenshots of the topology, successful connectivity tests, and final activity assessment can be added to this folder.

## Author
SDais4g63 — Cybersecurity AAS student and aspiring IT/network support professional.
