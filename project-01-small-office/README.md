# Project 01 — Small Office Network

## Scenario
A small company with 10 employees needs a reliable internal network with basic connectivity.

---

## Problem
- Flat network (no segmentation)
- No security measures
- High broadcast traffic

---
## Objective
- Build a structured network
- Configure IP addressing
- Enable communication between devices

---
## Topology
![Topology](./images/topology.png)

# Objectives
- Design a basic network topology
- Assign IP addresses manually
- Configure default gateways
- Enable communication between devices
- Apply basic security configurations

---

## Security
- Configured console password on the switch to prevent unauthorized access  
- Disabled unused switch ports to reduce security risks  
- Applied basic device hardening practices  

---

## Testing

### Connectivity Tests
- Verified communication between PCs using `ping`  
- Tested connectivity between PCs and the router (default gateway)  

### Commands Used
```bash
ping 192.168.1.1
ping 192.168.1.10
arp -a


