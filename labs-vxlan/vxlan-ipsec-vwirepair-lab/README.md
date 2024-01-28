# Vxlan over IPSec configuration example
![image](https://github.com/MikeWissa/NSE8PracticewithAnsible/assets/6186228/84596be4-b7e0-46d0-a5c0-b0c8c8c9593f)

# Running the lab
ansible-playbook -i hosts tasks.yml

# VXLAN over IPSec tunnel with virtual wire pair

VXLAN can be used to encapsulate VLAN traffic over a Layer 3 network. Using IPsec VPN tunnels to secure a connection between two sites, VXLAN can encapsulate VLAN traffic over the VPN tunnel to extend the VLANs between the two sites.

In this example, a site-to-site VPN tunnel is formed between two FortiGates. A VXLAN is configured over the IPsec interface. Hosts connected to port 4 are able to communicate directly to each other as if they are on the same network.
