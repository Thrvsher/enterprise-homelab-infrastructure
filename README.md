# Enterprise Home Lab Infrastructure

## Project Overview

This project documents the design, deployment, and administration of a virtualized home lab built to simulate a small business IT environment.

The goal is to develop hands-on experience in network administration, virtualization, cybersecurity, Windows Server, and Linux systems administration.

**Project Status:** In progress

## Hardware

| Component | Purpose |
|---|---|
| Dell OptiPlex 3050 SFF | Dedicated OPNsense firewall |
| Intel i350 dual-port NIC | WAN and LAN connectivity |
| TP-Link managed switch | VLANs and network connectivity |
| Ryzen 5 3600 PC, 16GB RAM | Proxmox virtualization host |
| WD Blue SN570 500GB SSD | Virtual machine storage |

## Technologies

- OPNsense — firewall, routing, DHCP, and network segmentation
- Proxmox VE — virtualization
- Windows Server — Active Directory, DNS, and Group Policy
- Ubuntu Server — Linux administration and services
- TP-Link managed switch — VLANs and network management

## Project Objectives

- Deploy a dedicated firewall using OPNsense.
- Configure segmented networks using VLANs.
- Install and manage Proxmox VE.
- Deploy Windows Server and Linux virtual machines.
- Create an Active Directory domain.
- Implement firewall policies and least-privilege access.
- Test connectivity, security, and recovery procedures.
- Document configurations and troubleshooting.

## Network Architecture

Network topology diagram coming soon.

## Implementation Progress

- [ ] Install and configure OPNsense
- [ ] Configure managed switch
- [ ] Create VLANs
- [ ] Install Proxmox VE
- [ ] Deploy Windows Server
- [ ] Configure Active Directory and DNS
- [ ] Deploy Ubuntu Server
- [ ] Test firewall rules and network isolation
- [ ] Configure backups and test recovery
- [ ] Complete project documentation

## Lessons Learned

This section will document technical challenges, troubleshooting steps, and improvements made throughout the project.

## Future Improvements

- Expand server RAM to 32GB
- Deploy a dedicated wireless access point
- Implement centralized monitoring
- Configure network-attached storage
- Explore infrastructure automation
