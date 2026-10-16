# Enterprise Campus Network Security Lab

## Project Overview

This project demonstrates the design, configuration, and
troubleshooting of an enterprise campus network using EVE-NG.

The lab focuses on redundant switching, VLAN segmentation,
gateway redundancy, dynamic routing, and perimeter firewall
security.

## Objectives

- Design a hierarchical campus network.
- Configure VLANs and trunk links.
- Implement EtherChannel using LACP where appropriate.
- Configure HSRP for default gateway redundancy.
- Implement OSPF for dynamic routing where required.
- Integrate a Palo Alto firewall.
- Configure and validate security policies and NAT.
- Perform network troubleshooting and failover testing.
- Document configurations and verification results.

## Technologies

- EVE-NG
- Cisco IOS / IOS XE
- VLANs and 802.1Q trunks
- EtherChannel / LACP
- HSRP
- OSPF
- Palo Alto PAN-OS
- NAT and security policies
- Windows endpoints and virtual PCs

## Network Architecture

The topology includes:

- Two core switches
- Two distribution switches
- Two access switches
- One Palo Alto firewall
- Windows endpoints and virtual PCs
- A Windows Server endpoint

See `diagrams/network-topology.png` for the network topology.

## Project Structure

- `diagrams/` - Network and security diagrams
- `documentation/` - Network design and planning
- `configurations/` - Device configurations
- `screenshots/` - Verification evidence
- `troubleshooting/` - Issues and resolutions
- `eve-ng/` - Lab setup and import instructions

## Validation

Configuration and verification results will be documented
as each feature is implemented and tested.

## Learning Outcomes

This project is intended to demonstrate practical skills in
enterprise networking, network security, troubleshooting,
and technical documentation.

## Disclaimer

This is a personal learning lab built in a virtual environment.
Configurations must be reviewed and adapted before use in
a production network.
