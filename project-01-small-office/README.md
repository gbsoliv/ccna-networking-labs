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
- Design a basic network topology
- Assign IP addresses manually
- Enable communication between devices
- Configure default gateways

---
## Topology: STAR

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/b0aacc23-3b5c-4b50-a5ca-875e99b96d0b" />


---

## Security
- Rename devices
- Configured console password on the switch to prevent unauthorized access
- Disabled unused switch ports to reduce security risks  
- Configured Secret Password on the router
- Configured Password Encryption on the router 

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


