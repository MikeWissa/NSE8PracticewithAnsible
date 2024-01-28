# this script setup both branch1 and branch2 firewalls to establish a vxlan extension
![image](https://github.com/MikeWissa/NSE8PracticewithAnsible/assets/6186228/6c4b7119-5ad1-4bf9-be87-c5e990d07111)

# To modify the script
* modify hosts file to add information relation to your hosts
* add a yml file for each of your routers under host_vars

# To run the script
ansible-playbook -i hosts tasks.yaml
