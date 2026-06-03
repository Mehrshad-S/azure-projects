# Azure Internal Load Balancer & Private DNS Website Deployment

This project focused on building a private, highly available web architecture in Microsoft Azure.

The goal was to place multiple IIS web servers behind an internal load balancer, use Private DNS for internal name resolution, and keep access private through Azure networking and Bastion instead of exposing public IP addresses.

## Project Date

Jul 2025 – Aug 2025

## What I Implemented

* Built a high-availability internal web architecture using two IIS servers.
* Placed the web servers behind an Azure Internal Load Balancer.
* Configured backend pools, health probes, and HTTP load balancing rules.
* Used Azure Private DNS for internal-only access through a fully qualified domain name.
* Configured secure private connectivity across peered virtual networks.
* Used Azure Bastion for browser-based VM access without public IP exposure.
* Tested traffic distribution by accessing the website from a client VM.
* Verified fault tolerance by confirming backend server responses through the load balancer.

## Technologies Used

* Azure Virtual Machines
* IIS Web Server
* Azure Internal Load Balancer
* Backend Pools
* Health Probes
* Private DNS Zone
* Virtual Network Peering
* Azure Bastion
* Network Security Groups

## Demo and Topology

* **Demo:** [here](https://onedrive.live.com/?photosData=%2Fshare%2F3AA4229D1E8931C9%21s6bcbf508f943455a89565ccd357106f2%3Fithint%3Dvideo%26migratedtospo%3Dtrue&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy8zYWE0MjI5ZDFlODkzMWM5L0lRQUk5Y3RyUV9sYVJZbFdYTTAxY1FieUFjLUJCdzM0LTVobDF1UWJkeWU5NERr&view=8)
* **Topology:** [here](./topology.png)

## Skills Demonstrated

* Internal load balancing
* Private Azure networking
* DNS-based internal access
* High availability design
* Secure VM administration with Bastion
* Backend health monitoring
* Web server deployment and testing

## What I Learned

This project helped me understand how private Azure web architectures can be designed without exposing services directly to the internet. I practiced using internal load balancing, Private DNS, VNet peering, and Bastion to create a secure and highly available environment for internal web access.
