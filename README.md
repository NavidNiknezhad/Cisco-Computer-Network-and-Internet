# Cisco-Computer-Network-and-Internet

## Lab 1 – Configuring Basic Router Settings with IOS CLI
<img src="https://imgur.com/DzRcfKw.jpg">
<h3>Objectives</h3>
<h4> Part 1: Set Up the Topology and Initialize Devices</h4>
1. Cable equipment to match the network topology.
2. Initialize and restart the router and switch.
<h4> Part 2: Configure Devices and Verify Connectivity</h4>
1. Assign static IPv4 information to the PC interfaces.
2. Configure basic router settings.
3. Verify network connectivity.
4. Configure the router for SSH.
<h4> Part 3: Display Router Information</h4>
1. Retrieve hardware and software information from the router.
2. Interpret the output from the startup configuration.
3. Interpret the output from the routing table.
4. Verify the status of the interfaces.
<h4> Part 4: Configure IPv6 and Verify Connectivity</h4>

## Lab 2a – Configuring Basic Switch Settings
<img src="https://imgur.com/8SVEgxk.jpg">
<h3>Objectives</h3>
<h4> Part 1: Cable the Network and Verify the Default Switch Configuration</h4>
<h4> Part 2: Configure Basic Network Device Settings</h4>
• Configure basic switch settings.
• Configure the PC IP address.
<h4> Part 3: Verify and Test Network Connectivity</h4>
• Display device configuration.
• Test end-to-end connectivity with ping.
• Test remote management capabilities with Telnet.
• Save the switch running configuration file.
<h4> Part 4: Manage the MAC Address Table</h4>
• Record the MAC address of the host.
• Determine the MAC addresses that the switch has learned.
• List the show mac address-table command options.
• Set up a static MAC address.

## Lab 2b – Configuring Switch Security Features
<img src="https://imgur.com/AYi2O4a.jpg">
<h3>Objectives</h3>
<h4> Part 1: Set up the Topology and Initialize Devices</h4>
<h4> Part 2: Configure Basic Device Settings and Verify Connectivity</h4>
<h4> Part 3: Configure and Verify SSH Access on S1</h4>
• Configure SSH access.
• Modify SSH parameters.
• Verify the SSH configuration.
<h4> Part 4: Configure and Verify Security Features on S1</h4>
• Configure and verify general security features.
• Configure and verify port security

<h3>Background / Scenario</h3> 
It is quite common to lock down access and install strong security features on PCs and servers. It is important 
that your network infrastructure devices, such as switches and routers, are also configured with security 
features.
In this lab, you will follow some best practices for configuring security features on LAN switches. You will only 
allow SSH and secure HTTPS sessions. You will also configure and verify port security to lock out any device 
with a MAC address not recognized by the switch

<h3>Background / Scenario</h3> 
Cisco switches can be configured with a special IP address known as the switch virtual interface (SVI). The SVI, or management address, can be used for remote access to the switch to display or configure settings. If the VLAN 1 SVI is assigned an IP address, by default all ports in VLAN 1 have access to the SVI IP address. 
In this lab, I built a simple topology using Ethernet LAN cabling and access a Cisco switch using the console and remote access methods. You will examine default switch configurations before configuring basic switch settings. These basic switch settings include device name, interface description, local passwords,
message of the day (MOTD) banner, IP addressing, and static MAC address. We also demonstrate the Topology Lab 2a – Configuring Basic Switch Settings © 2016 Cisco and/or its affiliates. All rights reserved. Use of a management IP address for remote switch management. The topology consists of one switch and one host using only Ethernet and console ports.

## Lab 3 - Implement VLANs and Trunking
<img src="https://imgur.com/Qn1Y2ha.jpg">
<h3>Objectives</h3>
<h4> Part 1: Build the Network and Configure Basic Device Settings</h4>
<h4> Part 2: Create VLANs and Assign Switch Ports</h4>
<h4> Part 3: Configure an 802.1Q Trunk between the Switches</h4>

<h3>Background / Scenario</h3> 
Modern switches use virtual local-area networks (VLANs) to improve network performance by separating 
large Layer 2 broadcast domains into smaller ones. VLANs address scalability, security, and network 
management. In general, VLANs make it easier to design a network to support the goals of an organization. 
Communication between VLANs requires a device operating at Layer 3 of the OSI model. 
VLAN trunks are used to span VLANs across multiple devices. Trunks allow the traffic from multiple VLANs to 
travel over a single link, while keeping the VLAN identification and segmentation intact.
In this lab, we create VLANs on both switches in the topology, assign VLANs to switch access ports, 
verify that VLANs are working as expected and create VLAN trunks between the two switches.

## Lab 4 - Implement Inter-VLAN Routing
<img src="https://imgur.com/XvjfE10.jpg">
<h3>Objectives</h3>
<h4> Part 1: Build the Network and Configure Basic Device Settings</h4>
<h4> Part 2: Create VLANs and Assign Switch Ports</h4>
<h4> Part 3: Configure an 802.1Q Trunk between the Switches</h4>
<h4> Part 4: Configure Inter-VLAN Routing on the Router</h4>
<h4> Part 5: Verify Inter-VLAN Routing is working</h4>

<h3>Background / Scenario</h3> 
Modern switches use virtual local-area networks (VLANs) to improve network performance by separating 
large Layer 2 broadcast domains into smaller ones. VLANs can also be used as a security measure by 
separating sensitive data traffic from the rest of the network. In general, VLANs make it easier to design a 
network to support the goals of an organization. Communication between VLANs requires a device operating 
at Layer 3 of the OSI model. Adding an inter-VLAN router allows the organization to segregate and separate 
broadcast domains while simultaneously allowing them to communicate with each other.
VLAN trunks are used to span VLANs across multiple devices. Trunks allow the traffic from multiple VLANs to 
travel over a single link, while keeping the VLAN identification and segmentation intact. A particular kind of 
inter-VLAN routing, called “Router-on-a-Stick”, uses a trunk from the router to the switch to enable all VLANs 
to pass to the router.
In this lab, we create VLANs on both switches in the topology, assign VLANs to switch access ports, 
verify that VLANs are working as expected, create VLAN trunks between the two switches and between S1 
and R1, and configure Inter-VLAN routing on R1 to allow hosts in different VLANs to communicate, regardless 
of which subnet the host resides.

## Lab 5 -Implement EtherChannel
<img src="https://imgur.com/v1Ebz9P.jpg">
<h3>Objectives</h3>
<h4> Part 1: Build the Network and Configure Basic Device Settings</h4>
<h4> Part 2: Create VLANs and Assign Switch Ports</h4>
<h4> Part 3: Configure 802.1Q Trunks between the Switches</h4>
<h4> Part 4: Implement and Verify an EtherChannel between the switches</h4>

<h3>Background / Scenario</h3> 
Link aggregation allows the creation of logical links that are comprised of two or more physical links. This 
provides increased throughput beyond using only one physical link. Link aggregation also provides redundancy if one of the links fails.
In this lab, we configure EtherChannel, a form of link aggregation used in switched networks. We configure EtherChannel using Link Aggregation Control Protocol (LACP).

<h5> Note: LACP is a link aggregation protocol that is defined by IEEE 802.3ad, and it is not associated with any specific vendor.
LACP allows Cisco switches to manage Ethernet channels between switches that conform to the 802.3ad 
protocol. We can configure up to 16 ports to form a channel. Eight of the ports are in active mode and the 
other eight are in standby mode. When any of the active ports fail, a standby port becomes active. Standby 
mode works only for LACP, not for PAgP.</h5>

## Lab 8 Packet Tracer - Switch Security Configuration
<img src="https://imgur.com/MnhMiTe.jpg">
<h3>Objectives</h3> 
<h4> Part 1: Create a Secure Trunk </h4>
<h4> Part 2: Secure Unused Switchports </h4>
<h4> Part 3: Implement Port Security </h4>
<h4> Part 4: Enable DHCP Snooping </h4>
<h4> Part 5: Configure Rapid PVST PortFast and BPDU Guard </h4>

<h3>Background / Scenario</h3> 
You are enhancing security on two access switches in a partially configured network. You will implement the 
range of security measures that were covered in this module according to the requirements below. Note that 
routing has been configured on this network, so connectivity between hosts on different VLANs should 
function when completed. 
