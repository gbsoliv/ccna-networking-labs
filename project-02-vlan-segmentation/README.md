# Project 02 — VLAN Segmentation

## Scenario
The company has grown and now includes multiple departments:

- Finance
- Human Resources (HR)
- IT

---

## Problem
- All devices are in the same network  
- No traffic isolation between departments  
- Increased security risks  
- Excessive broadcast traffic  

---

## Objective
- Create VLANs for each department  
- Assign switch ports to the correct VLANs  
- Configure trunk links between switches  
- Ensure proper logical segmentation   
- Improve security and organization  
- Reduce unnecessary broadcast traffic  

---

## Topology
Topology: STAR 

![star-topology (1)](https://github.com/user-attachments/assets/2bef1ac6-7d91-4512-9e93-e47d9d8df722)



---

## VLAN Ports Plan

- VLAN 10: Fa0/1 > 0/10 
- VLAN 20: F0/10 > 0/20 
- VLAN 30: F0/20 > 0/24 

---

## Security
- Network segmentation between departments  
- Restricted access between VLANs  
- Improved control over broadcast domains  

---

## Testing

### Connectivity Tests
- Verify communication between devices within the same VLAN  
- Verify isolation between different VLANs  

### Commands Used
```bash
show vlan brief
show interfaces trunk
