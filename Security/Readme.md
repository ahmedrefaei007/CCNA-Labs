# Security Labs  

This folder contains labs related to security configurations in Cisco networks.  

## 1. ACL Lab  

**Objective:**  
Apply different ACL rules on multiple networks to control access to a server.  

**Scenario:**  
- The lab consists of **two networks**, each with two hosts connected to a server.  

### Network 1  
- **Host 1:** Completely denied (no traffic allowed to the server).  
- **Host 2:** Denied HTTP (web) access, but ICMP (ping) is allowed.  

### Network 2  
- **Host 1:** Denied ICMP (ping), but allowed HTTP (web).  
- **Host 2:** Denied HTTP (web), but allowed ICMP (ping).  

**Notes:**  
- This lab demonstrates how ACLs can selectively block or allow traffic per host and per protocol.  
- Configurations are saved in the devices and can be verified using `show run`.  
