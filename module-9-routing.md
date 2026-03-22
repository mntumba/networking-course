# Module 9: Routing

## Overview
Routing is the process of selecting paths in a network along which to send network traffic. This document provides comprehensive details about routing, including the differences between static and dynamic routing, and an overview of routing protocols such as RIP, OSPF, and BGP, as well as explanations of routing tables and ASCII diagrams.

## Static Routing
Static routing is a type of routing that is manually configured. It involves setting up routes by adding them to the routing table. Static routes do not change unless manually edited, making them reliable for small networks but lacking scalability.

### Advantages of Static Routing
- Simplicity and ease of configuration for small networks.
- Predictable—routes do not change.

### Disadvantages of Static Routing
- Requires manual updates when network topology changes.
- Not scalable for large, dynamic networks.

## Dynamic Routing
Dynamic routing involves the use of protocols to automatically update routing tables based on changes in the network. Routers communicate with each other to exchange information about network status and topology changes.

### Advantages of Dynamic Routing
- Adaptability to changes in the network topology.
- Scalable for large networks, as it requires minimal manual intervention.

### Disadvantages of Dynamic Routing
- More complex than static routing.
- Requires more overhead due to communication between routers.

## Routing Protocols
Routing protocols are standardized methods that routers use to communicate routing information. Some common routing protocols include:

### 1. RIP (Routing Information Protocol)
- A distance-vector routing protocol.
- Uses hop count as a metric for path selection.
- Limited to 15 hops, making it suitable for smaller networks.
- Less frequently used in modern networks due to scalability issues.

### 2. OSPF (Open Shortest Path First)
- A link-state routing protocol.
- Sends updates only when there is a change, conserving bandwidth.
- Supports VLSM (Variable Length Subnet Masking).
- Scalable and suitable for larger enterprise networks.

### 3. BGP (Border Gateway Protocol)
- The protocol used to route traffic across the Internet (between autonomous systems).
- Uses a path vector mechanism and maintains the path information that gets updated dynamically.
- Highly scalable and suitable for large networks.

## Routing Tables
Routing tables are data structures maintained by routers that contain information about the routes available to various network destinations. Each entry typically includes:
- **Destination Address**: The address of the destination network.
- **Next Hop**: The next router to which traffic should be sent.
- **Metric**: A value used to determine the best route to a destination.

## ASCII Diagrams
Below are ASCII diagrams representing routing concepts.

### Example of Static Routing
```
[Router A] ----- [Router B]
```

### Example of Dynamic Routing with OSPF
```
          +---------+
          |  OSPF   |
          +---------+
            /       \
     [Router A]    [Router B]
```

### Example of BGP
```
[AS1]---\
         [Router A]--[BGP]--[Router B]---[AS2]
[AS3]---/
```

## Conclusion
Understanding routing and its protocols is essential for managing and administering networks. This file provides a foundational overview, but further study and hands-on practice are recommended to master networking concepts and techniques.