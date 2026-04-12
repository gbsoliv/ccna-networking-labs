# Project 03 — Inter-VLAN Routing (Router-on-a-Stick)

## Overview
This project implements inter-VLAN routing using a router (Router-on-a-Stick) in Cisco Packet Tracer.

VLANs:
- VLAN 10 — Finance
- VLAN 20 — HR
- VLAN 30 — IT

---

## Objective
- Enable communication between VLANs
- Maintain Layer 2 segmentation
- Implement Layer 3 routing via router

---

## Topology
- Extended Star
- 1 Router, 2 Switches, 6 PCs

<img width="259" height="272" alt="extended-star-topology" src="https://github.com/user-attachments/assets/43dcb983-627f-440c-908c-e9c33be68370" />
<img width="1167" height="672" alt="Inter-VLAN Routing" src="https://github.com/user-attachments/assets/4429aa45-94e6-4ca4-a623-e03f9da30ef7" />

---

## Key Configuration

### Router (subinterfaces)
```bash
interface g0/0.10
 encapsulation dot1Q 10
 ip address 192.168.10.1 255.255.255.0

interface g0/0.20
 encapsulation dot1Q 20
 ip address 192.168.20.1 255.255.255.0

interface g0/0.30
 encapsulation dot1Q 30
 ip address 192.168.30.1 255.255.255.0

```
---

## Troubleshooting

Issue: VLAN 30 could not reach other networks
Fix: VLAN 30 missing on one switch
