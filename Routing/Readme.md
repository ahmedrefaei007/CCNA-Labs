# Routing Labs  

This folder contains three labs demonstrating different routing protocols and redistribution.  

## Labs Overview  

### 1. EIGRP Lab  
- Configure and verify EIGRP across multiple routers.  
- Ensure end-to-end connectivity between hosts.  
- **Verification:**  
  - `show ip route` → check EIGRP-learned routes  
  - `ping`, `traceroute` → test reachability  

---

### 2. OSPF Lab  
- Configure OSPF with multiple routers.  
- Build neighbor adjacencies and share routes between areas.  
- **Verification:**  
  - `show ip ospf neighbor` → check adjacency  
  - `show ip route` → confirm OSPF-learned routes  

---

### 3. Redistribution Lab  
- Demonstrates route redistribution across multiple routing protocols.  
- Protocols included in this lab:  
  - **EIGRP**  
  - **OSPF**  
  - **RIP v2**  
  - **Static Routes**  
  - **Default Routes**  
- Core router redistributes routes between all domains to achieve full connectivity.  
- **Verification:**  
  - `show ip protocols` → confirm redistribution  
  - `show ip route` → validate injected routes  
  - `ping`, `traceroute` → test end-to-end communication  

---
