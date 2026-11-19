
Task 04 — VLANs and Access Ports

Objective

To understand VLANs, broadcast domains, and access port configuration using Cisco Packet Tracer

VLAN Configuration Plan

VLAN ID

VLAN Name

Purpose

10

Staff

Staff Department

20

Finance

Finance Department

30

Guest

Guest Network

Tasks Performed

Studied broadcast domains and the limitations of flat networks

Created VLAN 10 (Staff)

Created VLAN 20 (Finance)

Created VLAN 30 (Guest)

Assigned switch access ports to the appropriate VLANs

Connected PCs to their assigned VLANs

Tested connectivity between hosts in different VLANs

Verified VLAN configuration and MAC address learning

Important Cisco IOS Commands

vlan 10
 name Staff
vlan 20
 name Finance
vlan 30
 name Guest

show vlan brief
show mac address-table

Verification

Used show vlan brief to verify VLANs and assigned ports

Used show mac address-table to inspect learned MAC addresses

Performed ping tests between hosts in different VLANs

Verified that inter-VLAN communication was blocked without Layer 3 routing

Learning Outcomes

Understood how VLANs divide a switch network into separate broadcast domains

Learned how to create and name VLANs

Practiced assigning access ports

Understood MAC address table entries

Learned how VLAN isolation works

Practical Evidence

Screenshots, Packet Tracer topology, configuration files, and ping test results are included in this folder
