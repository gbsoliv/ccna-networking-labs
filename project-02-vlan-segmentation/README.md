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


<img width="1847" height="1010" alt="vlan-segmentation-topology" src="https://github.com/user-attachments/assets/1551b06c-37e7-452f-96f5-91180b8b21cd" />


---

## VLAN Ports Plan

- VLAN 10 Fincance: Fa0/1 > 0/9 
- VLAN 20 HR: F0/10 > 0/19 
- VLAN 30 IT: F0/20 > 0/24 

---

## Security
- Network segmentation between departments  
- Restricted access between VLANs  
- Improved control over broadcast domains
- Enable Secret: Cisco
- Shutdown unused interfaces

---

## Testing

### Connectivity Tests
- Verify communication between devices within the same VLAN  
- Verify isolation between different VLANs  

### Commands Used
```bash
show vlan brief
show interfaces trunk
