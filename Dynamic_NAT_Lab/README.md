# Dynamic NAT Lab

## Description
This lab demonstrates the configuration and implementation of Dynamic Network Address Translation (Dynamic NAT) using Cisco Packet Tracer.

Dynamic NAT allows internal private IP addresses to be translated into public IP addresses dynamically from a predefined NAT pool.

## Objectives
- Configure a Dynamic NAT pool.
- Define an ACL to identify internal network traffic.
- Configure inside and outside interfaces.
- Verify NAT translations.
- Test connectivity between internal and external networks.

## Tools
- Cisco Packet Tracer
- Cisco IOS CLI

## Files
- `Dynamic_NAT.pkt` – Packet Tracer lab file.
- `Topology.png` – Network topology diagram.

## Verification Commands
```bash
show ip nat translations
show ip nat statistics
show access-lists
```

