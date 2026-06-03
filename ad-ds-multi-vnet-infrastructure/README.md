# Azure Active Directory & Multi-VNet Infrastructure Deployment

This project focused on building a multi-network Azure infrastructure with Active Directory Domain Services, domain-joined virtual machines, internal DNS resolution, and secure VM access through Azure Bastion.

The goal was to design an Azure environment with multiple virtual networks, connect them using VNet peering, deploy a Windows Server domain controller, and validate domain authentication and internal web access across the environment.

## Project Date

Jun 2025 – Jul 2025

## What I Implemented

- Designed and deployed a multi-network Azure architecture with three virtual networks.
- Configured subnet segmentation to separate different parts of the environment.
- Configured Virtual Network Peering to allow secure communication between isolated networks.
- Deployed a Windows Server Domain Controller using Active Directory Domain Services.
- Created domain users and admin roles.
- Joined multiple virtual machines, including a web server and client VM, to the domain.
- Implemented Azure Bastion for secure browser-based access without exposing public IPs.
- Configured an IIS web server for internal access.
- Verified internal DNS resolution using FQDN across the network.
- Validated end-to-end connectivity by accessing the web server from a client VM within the domain.

## Technologies Used

- Azure Virtual Networks
- Subnets
- Virtual Network Peering
- Windows Server
- Active Directory Domain Services
- Domain Controller
- Domain-Joined Virtual Machines
- Azure Bastion
- IIS Web Server
- DNS / FQDN resolution

## Demo and Topology

* **Demo:** [here](https://onedrive.live.com/?photosData=%2Fshare%2F3AA4229D1E8931C9%21sc455c6c4ed0c449e99d6862e4afcdf6b%3Fithint%3Dvideo%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy8zYWE0MjI5ZDFlODkzMWM5L0lRREV4bFhFRE8yZVJKbldoaTVLX045ckFWSVd4NjFqMEF0XzNnRVNYYjVYdTNN&view=8)
* **Topology:** [here](./topology.png)

## Skills Demonstrated

- Azure infrastructure design
- Multi-VNet networking
- Active Directory deployment
- Domain authentication
- DNS troubleshooting
- Secure VM administration
- Internal web server deployment
- Network connectivity validation

## What I Learned

This project helped me understand how traditional Windows Server and Active Directory environments can be deployed inside Azure. I practiced designing multiple virtual networks, connecting them through VNet peering, configuring domain services, joining machines to a domain, and validating DNS and internal connectivity across the environment.
