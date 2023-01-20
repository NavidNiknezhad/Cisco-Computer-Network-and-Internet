# Cisco-Computer-Network-and-Internet

## Lab 1 – Configuring Basic Router Settings with IOS CLI



### Objectives
#### Part 1: Set Up the Topology and Initialize Devices
1. Cable equipment to match the network topology.
2. Initialize and restart the router and switch.
#### Part 2: Configure Devices and Verify Connectivity
1. Assign static IPv4 information to the PC interfaces.
2. Configure basic router settings.
3. Verify network connectivity.
4. Configure the router for SSH.
#### Part 3: Display Router Information
1. Retrieve hardware and software information from the router.
2. Interpret the output from the startup configuration.
3. Interpret the output from the routing table.
4. Verify the status of the interfaces.
#### Part 4: Configure IPv6 and Verify Connectivity

## Lab 2a – Configuring Basic Switch Settings

### Objectives
#### Part 1: Cable the Network and Verify the Default Switch Configuration
#### Part 2: Configure Basic Network Device Settings
• Configure basic switch settings.
• Configure the PC IP address.
#### Part 3: Verify and Test Network Connectivity
• Display device configuration.
• Test end-to-end connectivity with ping.
• Test remote management capabilities with Telnet.
• Save the switch running configuration file.
#### Part 4: Manage the MAC Address Table
• Record the MAC address of the host.
• Determine the MAC addresses that the switch has learned.
• List the show mac address-table command options.
• Set up a static MAC address.

### Background / Scenario
Cisco switches can be configured with a special IP address known as the switch virtual interface (SVI). The SVI, or management address, can be used for remote access to the switch to display or configure settings. If the VLAN 1 SVI is assigned an IP address, by default all ports in VLAN 1 have access to the SVI IP address. 
In this lab, I built a simple topology using Ethernet LAN cabling and access a Cisco switch using the console and remote access methods. You will examine default switch configurations before configuring basic switch settings. These basic switch settings include device name, interface description, local passwords,
message of the day (MOTD) banner, IP addressing, and static MAC address. You will also demonstrate the Topology Lab 2a – Configuring Basic Switch Settings © 2016 Cisco and/or its affiliates. All rights reserved. Use of a management IP address for remote switch management. The topology consists of one switch and one host using only Ethernet and console ports.

## Lab 3 - Implement VLANs and Trunking

