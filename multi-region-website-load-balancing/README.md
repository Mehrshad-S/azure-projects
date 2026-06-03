# Azure Multi-Region Website Deployment with Load Balancing

This project focused on deploying a website across multiple Azure regions to improve availability, performance, and traffic distribution.

The goal was to host web servers in two different Azure regions, configure load balancing within each region, and use global traffic routing to direct users to the closest available region.

## Project Date

Oct 2025 – Oct 2025

## What I Implemented

- Deployed a website across two Azure regions for improved availability.
- Set up two web servers per region.
- Configured round-robin load balancing within each region.
- Configured global traffic routing to direct users to the closest region.
- Created a Windows 10 client VM to test access using FQDN.
- Verified load balancing by refreshing the website and confirming backend server changes.

## Technologies Used

- Azure Virtual Machines
- Azure Virtual Networks
- Azure Load Balancer
- Azure Traffic Manager
- IIS Web Server
- DNS / FQDN testing
- Windows 10 Client VM
- High Availability design

## Demo and Topology

* **Demo:** https://onedrive.live.com/?qt=allmyphotos&photosData=%2Fshare%2F3AA4229D1E8931C9%21sd1a7d91e0a9d482b8a3d9b29e0eba2d8%3Fithint%3Dvideo%26migratedtospo%3Dtrue&cid=3AA4229D1E8931C9&id=3AA4229D1E8931C9%21sd1a7d91e0a9d482b8a3d9b29e0eba2d8&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3YvYy8zYWE0MjI5ZDFlODkzMWM5L0lRQWUyYWZSblFvclNJbzlteW5nNjZMWUFZV29mcFJVekRJWWJKdW5jcUtXM1RB&v=photos 
* **Topology:** [here](./topology.png)

## Skills Demonstrated

- Multi-region cloud deployment
- High availability architecture
- Regional load balancing
- Global traffic routing
- DNS-based testing
- Azure networking
- Infrastructure validation

## What I Learned

This project helped me understand how Azure can be used to improve website availability by spreading resources across multiple regions. I practiced configuring regional load balancing, global traffic routing, and testing access through FQDN to confirm that users can be directed to the correct backend environment.
