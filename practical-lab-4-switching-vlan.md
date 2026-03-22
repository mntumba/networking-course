# VLAN Configuration Exercises

## Exercise 1: Configuring VLAN on Switch
1. Access the switch's command line interface (CLI).  
2. Enter global configuration mode:  
   ```
   Switch# configure terminal
   ```
3. Create VLAN 10 and name it 'Sales':  
   ```
   Switch(config)# vlan 10
   Switch(config-vlan)# name Sales
   ```
4. Assign ports 1-5 to VLAN 10:
   ```
   Switch(config)# interface range fa0/1 - 5
   Switch(config-if-range)# switchport mode access
   Switch(config-if-range)# switchport access vlan 10
   ```
5. Verify VLAN assignments:
   ```
   Switch# show vlan brief
   ```

## Exercise 2: Inter-VLAN Routing
1. Enable IP routing on the router:  
   ```
   Router# configure terminal
   Router(config)# ip routing
   ```
2. Configure subinterfaces for each VLAN:
   ```
   Router(config)# interface gig0/0.10
   Router(config-subif)# encapsulation dot1Q 10
   Router(config-subif)# ip address 192.168.10.1 255.255.255.0
   Router(config)# interface gig0/0.20
   Router(config-subif)# encapsulation dot1Q 20
   Router(config-subif)# ip address 192.168.20.1 255.255.255.0
   ```
3. Verify inter-VLAN connectivity:
   ```
   Router# ping 192.168.10.1
   Router# ping 192.168.20.1
   ```

## Exercise 3: VLAN Trunking
1. Configure trunking on switch port:
   ```
   Switch(config)# interface fa0/24
   Switch(config-if)# switchport mode trunk
   Switch(config-if)# switchport trunk allowed vlan 10,20
   ```
2. Verify trunking configuration:
   ```
   Switch# show interfaces trunk
   ```
3. Test VLAN communication through trunk:
   ```
   Switch# ping 192.168.10.1  # From a device in VLAN 10
   Switch# ping 192.168.20.1  # From a device in VLAN 20
   ```

# Conclusion
These exercises cover the basic configuration of VLANs, inter-VLAN routing, and trunking which are essential for managing network segmentation and improving traffic flow in a switched environment.
