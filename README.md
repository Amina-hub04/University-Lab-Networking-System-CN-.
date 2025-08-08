# University-Lab-Networking-System-CN-.
This project involves the design, configuration, and testing of a university lab network to enable efficient communication, resource sharing, and centralized management. It integrates servers, routers, and Layer 3 switches to provide services like DHCP, DNS, HTTP, and inter-VLAN routing for seamless operation.
Key Components & Configurations
1. Server Configuration
Servers were set up to provide essential network services:
a) DHCP (Dynamic Host Configuration Protocol)
Automatically assigns IP addresses to devices within the network.
Eliminates the need for manual configuration of each device.
Ensures dynamic allocation, which improves scalability and manageability — especially in a lab where devices connect/disconnect frequently.
b) DNS (Domain Name System)
Translates human-readable domain names (e.g., labserver.edu) into IP addresses.
Makes it easier for users to access resources without memorizing numerical addresses.
Enhances usability and efficiency in accessing lab resources.
c) HTTP Server
Hosts web pages accessible within the university network.
Demonstrated deployment changes by adding/modifying web files and testing updates before and after deployment.
Useful for internal portals, e-learning systems, or project hosting.
2. Router Configuration
Three routers were configured to ensure reliable data routing and network segmentation:
Router 1 → Main routing hub, managing primary network segmentation and traffic control.
Router 2 → Connected for redundancy and backup routing, ensuring continuous operation if Router 1 fails.
Router 3 → Handles specific network areas or VLANs to optimize traffic flow and reduce congestion.
Configuration ensured optimized path selection, load balancing, and failover capabilities.


