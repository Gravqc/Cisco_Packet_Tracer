# Network Topology Simulation Project

## 📖 Introduction
This project demonstrates a complex network topology using Cisco Packet Tracer. It showcases the configuration and interaction between various network devices, including routers, switches, servers, and end-user devices, across multiple subnets. The simulation includes the implementation of dynamic routing with OSPF, DHCP services for automatic IP assignments, and various network services such as DNS, NTP, and FTP.

## 🛠️ Installation
To view and interact with the network topology simulation, you will need:
- Cisco Packet Tracer installed on your computer.
- The `.pkt` file that contains the saved network topology.

**Setup:**
- Download and install Cisco Packet Tracer from [Cisco Networking Academy](https://www.netacad.com/courses/packet-tracer).
- Open the downloaded `.pkt` file with Cisco Packet Tracer to load the network topology.

## 👨‍🏫 Get Started
Once you have the topology loaded in Cisco Packet Tracer:
1. Start the simulation to see the network in action.
2. Interact with devices to see the configuration details.
3. Use the simulation mode to understand the packet flow across the network.

## 📘 Documentation
The project includes various configured network devices:
- **Routers**: Set up with OSPF for dynamic routing and DHCP for IP address assignment.
- **Switches**: Configured to facilitate device connections within LANs.
- **Servers**: Designated for DNS, NTP, and FTP services.
- **End-User Devices**: PCs and laptops representing clients in the network.

## 🌐 Network Topology
The network topology is structured as follows:
- **Core Layer**: Comprised of high-capacity routers (Router1 and Router3) using OSPF to ensure optimal routing.
- **Distribution Layer**: Includes Router0 for DHCP services, connecting to the core layer and aggregating the LANs formed by Switch0 to Switch3.
- **Access Layer**: Features switches connected to end devices like PCs and laptops, facilitating local area network access.
- **Wireless Network**: A wireless router (Wireless_Router0) is set up to provide wireless connectivity to mobile devices.
- **Network Services**: Servers are configured to provide DNS, NTP, and FTP services for network time synchronization, domain name resolution, and file transfer capabilities, respectively.
- **Public and Private Segments**: Designated areas for public addresses (198.10.10.x) and private network segments (195.12.10.x) to illustrate different access levels and security considerations.
- **Topology**:
  ![image](https://github.com/Gravqc/Cisco_Packet_Tracer/assets/90492971/4138fee1-c564-4ac3-96de-13e9110804c8)


## 🎥 Video Demo
Video demonstration of the network simulation can be found [here](https://drive.google.com/file/d/1yuzWS6S0Es4wJ8V7554UX2yjRrES-nMd/view?usp=sharing).
