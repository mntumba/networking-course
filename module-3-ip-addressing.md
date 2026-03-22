# IP Addressing

## Introduction
IP addressing is a vital aspect of networking, serving as a unique identifier for devices in a network. This document explores the fundamentals of IP addressing, focusing on both IPv4 and IPv6, subnetting techniques, CIDR notation and includes practical examples and calculations.

## IPv4 Addressing
### Definition
IPv4 (Internet Protocol version 4) is the most widely used version of the Internet Protocol. It utilizes a 32-bit addressing scheme allowing for approximately 4.3 billion unique addresses.
### Structure
An IPv4 address consists of four octets separated by periods. For example: `192.168.1.1`. Each octet can range from 0 to 255.

### Address Classes
- **Class A:** 1.0.0.0 to 126.0.0.0
- **Class B:** 128.0.0.0 to 191.255.0.0
- **Class C:** 192.0.0.0 to 223.255.255.0
- **Class D:** 224.0.0.0 to 239.255.255.255 (Multicast)
- **Class E:** 240.0.0.0 to 255.255.255.255 (Experimental)

## IPv6 Addressing
### Definition
IPv6 (Internet Protocol version 6) is designed to replace IPv4 and supports a much larger address space using 128-bit addressing.
### Structure
An IPv6 address is represented as eight groups of four hexadecimal digits, separated by colons. For example: `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.
### Address Types
- **Unicast:** A single sender and receiver.
- **Multicast:** A single sender and multiple receivers.
- **Anycast:** A single sender and the nearest receiver.

## Subnetting Techniques
Subnetting involves dividing a network into smaller, more manageable sub-networks.
### Purpose
- Efficient use of IP addresses.
- Improved network performance and security.

### Subnet Mask
A subnet mask determines which part of the IP address is the network and which part is the host. For example, in the address `192.168.1.1` with a subnet mask of `255.255.255.0`, `192.168.1` represents the network, and `.1` represents the host.

## CIDR Notation
CIDR (Classless Inter-Domain Routing) notation expresses IP addresses and their associated routing prefix.
### Format
It is represented as an IP address followed by a slash and the number of bits. For example: `192.168.1.0/24` indicates that the first 24 bits are the network portion.

## Practical Examples
### Example 1: Calculate Subnets
Assuming a network with the address `192.168.1.0` and a subnet mask of `255.255.255.0`, you can create 256 possible addresses (from 192.168.1.0 to 192.168.1.255).

### Example 2: CIDR Calculation
To find out how many hosts can be supported with `192.168.1.0/24`, you can calculate the number of hosts as `2^(32-24) - 2 = 256 - 2 = 254` usable addresses.

## Conclusion
Understanding IP addressing is critical for effective network management. IPv4 and IPv6 encompass the entire spectrum of addressing necessary for today's complex networks, while techniques like subnetting and CIDR allow for optimized use of these resources.

