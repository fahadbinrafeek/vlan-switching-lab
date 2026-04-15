# vlan-switching-lab
VLAN configuration lab in Cisco Packet Tracer demonstrating network segmentation using switches.

# VLAN Configuration Lab

## Overview
This lab demonstrates the configuration of VLANs (Virtual Local Area Networks) in Cisco Packet Tracer.

## Objectives
- Create and configure VLANs on switches
- Assign switch ports to different VLANs
- Configure trunk links between switches
- Enable communication between VLANs (inter-VLAN routing)

## Topology
- Multiple switches connected via trunk links
- PCs assigned to different VLANs

## Configuration Highlights
- VLAN creation using `vlan` command
- Port assignment using `switchport access vlan`
- Trunk configuration using `switchport mode trunk`
- 802.1Q encapsulation

## Verification Commands
- show vlan brief
- show interfaces trunk
- show running-config

## Testing
- Devices in same VLAN can communicate
- Devices in different VLAN require routing
