# Network_Design_And_Implementation_Projects

## 1. Hotel Network Design and Implementation

## Project Overview
This project designs and implements the network infrastructure for Vic Modern Hotel, spanning three floors with multiple departments. The network uses VLANs for segmentation, OSPF for dynamic routing, and DHCP for automatic IP assignment. Each department is placed in a dedicated VLAN, and wireless networks are set up for mobile devices. Routers, switches, and security features like SSH and port security are configured to ensure secure, scalable, and efficient communication across the hotel.

## Key Features
- **Three Routers** connecting each floor using serial DCE cables.
- **VLANs** per department for network segmentation.
- **DHCP** for dynamic IP address allocation across devices.
- **OSPF** routing protocol to advertise and manage routes between floors.
- **Wi-Fi Networks** on each floor for laptops and phones.
- **Port Security** on IT department switch to allow only Test-PC on port fa0/2.
- **SSH** enabled for secure remote router access.

## Tools and Technologies
- **Cisco Packet Tracer**: Used for network design and simulation.
- **VLAN, DHCP, OSPF**: Network segmentation, dynamic IP assignment, and routing.
- **SSH**: For secure router login.
- **Port Security**: Limits unauthorized device access.

## Result
![Hotel Network Design and Implementation Result](https://github.com/YashM1234/Network_Design_And_Implementation_Projects/blob/main/Hotel%20Network%20Design%20and%20Implementation/Hotel%20Network%20Design%20and%20Implementation%20S0.png)


## 2. Campus University Network Design and Implementation

## Project Overview
This project designs the network infrastructure for Albion University, a large university with two campuses located 20 miles apart. The network supports four faculties (Health and Sciences, Business, Engineering/Computing, and Art/Design), with staff and students needing secure, segmented, and interconnected network access across both campuses. VLANs are used for network segmentation, RIPv2 for routing, and DHCP for dynamic IP allocation in the admin departments.

## Key Features
- **VLAN Configuration** for faculty and department segmentation.
- **RIPv2 Routing** between campuses and static routing for external servers.
- **DHCP Server** on routers for dynamic IP address allocation in Building A.
- **Inter-VLAN Routing** via router-on-a-stick for seamless communication.
- **Port Security** on switches to enhance network security.
- **SSH** for secure remote access to networking devices.

## Tools and Technologies
- **Cisco Packet Tracer**: For network simulation and design.
- **VLANs, DHCP, RIPv2**: Network segmentation, dynamic IPs, and routing protocol.
- **Inter-VLAN Routing**: Enables communication between different VLANs.
- **SSH**: Secures remote access for network management.
- **Port Security**: Secures switch ports from unauthorized access.

## Result
![Hotel Network Design and Implementation Result](https://github.com/YashM1234/Network_Design_And_Implementation_Projects/blob/main/Campus%20University%20Network%20Design%20and%20Implementation/Campus%20University%20Network%20Design%20and%20Implementation%20S0.png
)

## 3. Banking and Insurance Company Network Design and Implementation

## Project Overview
This project designs the network infrastructure for Radeon Company Ltd.’s new branch in Nairobi, Kenya. The network supports multiple departments across four floors, with secure, scalable connectivity for both wired and wireless users. VLANs are configured for network segmentation, OSPF for routing, and DHCP for dynamic IP address allocation from dedicated servers located in the server room.

## Key Features
1. **Hierarchical Network Design** with core, distribution, and access layers, providing redundancy.
2. **VLAN Configuration** for each department, ensuring network segmentation.
3. **OSPF Routing** to connect different floors and advertise routes between routers.
4. **DHCP Servers** in the server room, dynamically assigning IPs to devices across all floors.
5. **SSH Configuration** for secure remote login on all routers.
6. **Port Security** using the sticky method to secure switch ports.
7. **Wireless Networks** for all departments, accommodating wired and wireless users.
8. **DNS, HTTP and Email Servers** configured in the server room for company operations.

## Tools and Technologies
- **Network Design Tools**: MS Visio for network topology modeling.
- **Simulation Software**: Cisco Packet Tracer for network design and implementation.
- **VLANs, OSPF, DHCP**: VLAN segmentation, routing protocol, and dynamic IP allocation.
- **Port Security**: Sticky command for securing ports with violation mode set to shutdown.
- **SSH**: Secure remote access to routers.

## Result
![Banking and Insurance Company Network Design and Implementation](https://github.com/YashM1234/Network_Design_And_Implementation_Projects/blob/main/Banking%20and%20Insurance%20Company%20Network%20Design%20and%20Implementation/Banking%20and%20Insurance%20Company%20Network%20Design%20and%20Implementation%20S0.png)

## 4. 
