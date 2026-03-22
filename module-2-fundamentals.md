# Networking Fundamentals

## OSI Model
The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and implement network communications. It consists of 7 layers:

1. **Physical Layer**  
   - **Function**: Transmits raw bit streams over a physical medium.  
   - **Examples**: Cables, switches.

2. **Data Link Layer**  
   - **Function**: Provides node-to-node data transfer and handles error correction from the physical layer.  
   - **Examples**: Switches, bridges.

3. **Network Layer**  
   - **Function**: Determines how data is sent from the source to the destination. It deals with routing of the data.  
   - **Examples**: Routers.

4. **Transport Layer**  
   - **Function**: Ensures complete data transfer. It provides error checking and guarantees delivery of data.  
   - **Examples**: TCP, UDP.

5. **Session Layer**  
   - **Function**: Manages sessions between applications. It establishes, maintains, and terminates connections.  
   - **Examples**: APIs, sockets.

6. **Presentation Layer**  
   - **Function**: Translates data between the application layer and the network. It can include encryption and compression.  
   - **Examples**: SSL, TLS.

7. **Application Layer**  
   - **Function**: Closest to the end user. It provides network services to end-user applications.  
   - **Examples**: HTTP, FTP, SMTP.

## TCP/IP Model
The TCP/IP model, also known as the Internet Protocol Suite, is a set of protocols used for communication over the internet. It consists of 4 layers:

1. **Link Layer**  
   - Responsible for the physical transmission of data over a medium.

2. **Internet Layer**  
   - Handles the routing of data packets across multiple networks.  
   - Example: IP protocol.

3. **Transport Layer**  
   - Provides end-to-end communication services for applications.  
   - Examples: TCP, UDP.

4. **Application Layer**  
   - Interfaces directly with end-user applications and provides network services.  
   - Examples: HTTP, FTP.

## Networking Devices
1. **Routers**:  
   - Connect different networks and route packets of data from one to another.
2. **Switches**:  
   - Connect devices within a single network and use MAC addresses to forward data to the correct device.
3. **Hubs**:  
   - Basic networking devices that connect multiple Ethernet devices, making them act as a single network segment.  
4. **Modems**:  
   - Modulate and demodulate signals for data transmission over phone lines or cable systems.

## ASCII Diagrams
```
  Layer 7    Application Layer
  Layer 6    Presentation Layer
  Layer 5    Session Layer
  Layer 4    Transport Layer
  Layer 3    Network Layer
  Layer 2    Data Link Layer
  Layer 1    Physical Layer
```

This document serves as an overview of networking fundamentals, providing a foundational understanding of the various models and devices essential for networking.