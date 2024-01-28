# NSE8PracticewithAnsible
This github repo is to record my learning of diffirent topics relating to Fortinet products covered in NSE8 exam. Using ansible and automation to help better understand the topics as well as replicated using automation tools.

# Vxlan Topic
Virtual Extensible LAN (VXLAN) is a network virtualization technology used in large cloud computing deployments. It encapsulates layer 2 Ethernet frames within layer 3 IP packets using the UDP transport protocol on port 4789. VXLAN endpoints that terminate VXLAN tunnels can be virtual or physical switch ports, and are known as VXLAN tunnel endpoints (VTEPs).

Sample VXLAN packet
![[Pasted image 20240106082358.png]]
A VXLAN packet encapsulation occurs by first inserting a VXLAN header in front of the original layer 2 frame. This VXLAN header uses 3 B for the VNID that is used to identify the VXLAN segment, meaning that there are 16,777,215 different possible VNIDs. This allows for more unique LAN segments than possible VLANs. The original frame and the VXLAN header are then encapsulated into the UDP payload. The outer IP header allows it to be routed and transported over a layer 3 network, thus providing a layer 2 overlay scheme over a layer 3 network.

## Vxlan Labs

[vxlan-ipsec-over-virtuawire-pair](https://github.com/MikeWissa/NSE8PracticewithAnsible/tree/main/labs-vxlan/vxlan-ipsec-vwirepair-lab)

[vxlan point to point](https://github.com/MikeWissa/NSE8PracticewithAnsible/tree/main/labs-vxlan/vxlan-point-to-point)

[vxlan-vwire-pair](https://github.com/MikeWissa/NSE8PracticewithAnsible/tree/main/labs-vxlan/vxlan-vwire-pair)

