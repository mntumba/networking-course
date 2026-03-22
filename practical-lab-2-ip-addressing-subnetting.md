# Practical Lab 2: IP Addressing and Subnetting

## Overview
This practical lab focuses on exercises related to IP addressing and subnetting. Students will learn how to effectively design IP addresses, perform subnetting calculations, configure devices, and test and verify their configurations.

## Learning Objectives
- Understand the principles of IP addressing
- Perform subnetting calculations
- Configure devices with accurate IP settings
- Test and verify network configuration

## Subnetting Calculations
1. **Determine the network address**
   - Calculate the network address based on the given IP address and subnet mask.
   - Example: For IP 192.168.1.10 with subnet mask 255.255.255.0, the network address is 192.168.1.0.

2. **Subnet Mask Calculation**
   - Convert between CIDR and decimal format.
   - Example: /24 is equivalent to 255.255.255.0.

3. **Number of Hosts Calculation**
   - Calculate the number of usable hosts in a subnet.
   - Formula: Usable Hosts = 2^(32 - subnet_bits) - 2

## Device Configuration
- Configure devices with the assigned IP addresses.
- Example device configuration steps:
  - Access the CLI of the device.
  - Enter the configuration mode.
  - Assign IP address and subnet mask.
  - Save the configuration.

## Testing and Verification
- Ping tests to check connectivity:
  - Use the `ping` command to verify the connection between devices.
  - Check for successful responses.

- Verify IP configurations:
  - Use commands like `ipconfig` or `ifconfig` to view assigned IP details.

## Exercises for Students
1. Given a set of IP addresses, perform the necessary subnetting calculations and provide the subnet masks.
2. Configure a device with a specific IP address and subnet.
3. Conduct ping tests and report on connectivity between at least three devices.
4. Document your findings and any issues encountered during the lab.

---
End of Lab 2
