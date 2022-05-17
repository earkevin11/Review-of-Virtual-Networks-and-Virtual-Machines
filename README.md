# Review-of-Virtual-Networks-and-Virtual-Machines


# What are Virtual Networks?
- VNets are automatically created when VMs are created.
- VNets are a home for the VMs.
- This is an isolated network hosted in the Azure Cloud Infrastructure
- VNets have an address space and VMs get an IP address within the address space.


# What is the purpose of Subnets?
- Subnets are just segments or a segregation of the IP address space of the virutal network.
- A Vnet can have multiple subnets.
- It's just a subset of the VNet. 

# What is a Network Interface?
- Each VM gets NIC.
- Communication to the VM happens over the NIC.

# What is a Private IP Address?
- Each NIC gets an Private IP.
- Each private IP is taken from the range of the assigned subnet.
- Each VM can also have a public IP address, which allows traffic from the VM to flow via the internet. 

# Network Security Groups (Similar to Firewall)
- Restricts inbound and outbound traffic via Network Security Rules
- NSGs can be assigned on the NIC or the subnet itself.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/168878861-2efd1f48-2751-48e2-a02f-259455832403.png" height="85%" width="85%" alt="review of vnets and VMs"/>

<p/>




