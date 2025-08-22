# VoIP & QoS Lab

## Overview
Lab focused on implementing **VoIP** services with **Quality of Service (QoS)** to ensure voice traffic is prioritized.  
All devices are connected via a single router and switch topology.  

### Lab Includes:
- 6 IP Phones paired with 6 PCs.
- Intra-site calling between phones.
- QoS policies applied to prioritize VoIP traffic.

## Topology
- **Router:** Cisco 2811 (gateway and telephony service).  
- **Switch:** Layer 2 switch connecting all endpoints.  
- **Endpoints:** 6 IP Phones + 6 PCs.  

## Key Configurations
- DHCP and telephony service for IP Phones.  
- Dial plan for internal calls.  
- QoS implemented using:
  - Class maps for VoIP traffic.  
  - Policy maps to ensure priority for voice packets.  
  - Service-policy applied to router interface.  

## Testing
- Check phone registration with `show ephone registered`.  
- Place calls between phones and confirm audio.  
- Verify QoS with `show policy-map interface`.  

## Notes
Configs are saved on the lab devices. Use `show running-config` to view them directly.
