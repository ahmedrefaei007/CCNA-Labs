# Routing Lab with Redistribution, OSPF, and EIGRP

This lab demonstrates a multi-protocol routing environment where different routing protocols are interconnected through redistribution.  

## Key Features:
- **Static & Default Routes**: Basic connectivity setup.  
- **RIP**: Configured on one part of the network.  
- **OSPF**: Configured on another segment with multiple areas.  
- **EIGRP**: Running on a separate part of the topology.  
- **Redistribution**: All routing protocols are redistributed into each other through the core router, enabling full connectivity across the network.  

## Testing
- Use `ping` to verify end-to-end reachability across all subnets.  
- Use `show ip route` on each router to confirm redistributed routes.  

---
This lab is designed to simulate real-world scenarios where multiple routing protocols must coexist and share routes.
