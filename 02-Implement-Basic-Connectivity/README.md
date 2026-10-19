# Lab 02: Implement Basic Connectivity

## Overview
This lab focuses on configuring basic network connectivity between PCs and Cisco switches.

## Objectives
- Configure switches S1 and S2.
- Configure console and privileged EXEC passwords.
- Assign IPv4 addresses to PCs.
- Configure VLAN 1 management interfaces.
- Verify connectivity using ping.
- Save configurations to NVRAM.

## IP Addressing

| Device | Interface | IP Address | Subnet Mask |
|--------|-----------|------------|-------------|
| S1 | VLAN 1 | 192.168.1.253 | 255.255.255.0 |
| S2 | VLAN 1 | 192.168.1.254 | 255.255.255.0 |
| PC1 | NIC | 192.168.1.1 | 255.255.255.0 |
| PC2 | NIC | 192.168.1.2 | 255.255.255.0 |

## Verification Commands
- show running-config
- show ip interface brief
- ping

## Skills Learned
- IPv4 addressing
- Switch management interfaces
- Network connectivity testing
- Basic troubleshooting

## Tool
Cisco Packet Tracer
