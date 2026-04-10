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

<img width="1912" height="1011" alt="01-topology" src="https://github.com/user-attachments/assets/95f3aa13-dfbc-4550-b504-79fb0e2b3a12" />

---

## Security
- Rename devices
- Add descriptions to ports
- Configured secret password on the switch and router to prevent unauthorized access
- Configured Password Encryption on the router
- Disabled unused switch ports to reduce security risks  
  

---

## Testing

### Connectivity Tests
- Verified communication between PCs using `ping`  
- Tested connectivity between PCs and the router (default gateway)  

<img width="802" height="961" alt="01-testing" src="https://github.com/user-attachments/assets/c6821f36-ed12-4dad-9515-5b2ff6135566" />

### Commands Used
```bash
ping 192.168.1.1
ping 192.168.1.10
arp -a





