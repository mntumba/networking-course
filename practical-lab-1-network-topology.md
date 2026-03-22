# Practical Lab 1: Network Topology Setup

## Objectives
- Understand different types of network topologies.
- Setup a network topology using simulation tools.

## Types of Network Topologies
1. **Star Topology**: All devices are connected to a central hub.  
   - **Pros**: Easy to manage and expand.  
   - **Cons**: If the hub fails, the whole network goes down.

2. **Bus Topology**: All devices share a single communication line.  
   - **Pros**: Cost-effective and easy to implement.
   - **Cons**: Performance degrades with more devices; if the main cable fails, the network is disrupted.

3. **Ring Topology**: Each device is connected to two other devices, forming a circular pathway.  
   - **Pros**: Data packets travel at great speeds; easier to manage as there are no collisions.
   - **Cons**: If one device fails, the entire network fails unless a dual-ring is used.

4. **Mesh Topology**: Devices are interconnected, allowing for multiple pathways for data.  
   - **Pros**: High redundancy and reliability.
   - **Cons**: Expensive because of the numerous cables and connections needed.

## Lab Setup Instructions
1. **Tools Required**:
   - Packet Tracer / GNS3 / Any other network simulation tool.

2. **Step 1**: Open your simulation tool and create a new project.
3. **Step 2**: Select the desired topology (star, bus, etc.) and begin placing devices on the canvas. Ensure each device is properly configured.
4. **Step 3**: Connect devices according to the chosen topology using appropriate cables (copper or fiber).
5. **Step 4**: Assign IP addresses to each device to enable communication.
6. **Step 5**: Test the network connectivity using ping command and troubleshoot any issues that arise.

## Conclusion
In this lab, you were expected to configure a network topology using simulation tools. Analyze how the topology impacts the performance and management of the network.

## References
- [Cisco Networking Academy](https://www.netacad.com)
- [Network Topologies Overview](https://www.networkworld.com)

---