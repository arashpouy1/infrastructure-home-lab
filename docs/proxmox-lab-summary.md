# Proxmox Virtualisation Lab – Summary

## Objective

To build a hands-on virtualisation lab environment using Proxmox and apply networking and systems administration concepts from coursework.

---

## Setup

* Installed Proxmox VE on dedicated hardware
* Configured management interface and network access
* Created multiple virtual machines (Windows Server and Ubuntu)

---

## Networking Configuration

* Configured multiple virtual bridges (vmbr0, vmbr1, vmbr2)
* Implemented:

  * External network (internet access)
  * Internal isolated network
* Tested connectivity between VMs and host network

---

## Challenges & Troubleshooting

### 1. VM Connectivity Issues

* Issue: VMs could not communicate across networks
* Resolution:

  * Verified NIC assignments
  * Checked firewall settings
  * Adjusted bridge configurations

### 2. Interface Mapping (Linux)

* Issue: Network interfaces not matching expected configuration
* Resolution:

  * Reviewed netplan configuration
  * Matched Proxmox NICs with Linux interfaces (ens18, ens19)

---

## Key Learnings

* Practical understanding of virtual networking
* Importance of correct interface mapping
* Troubleshooting methodology in layered systems
* Differences between isolated and bridged networking

---

## Next Steps

* Implement VLAN segmentation
* Explore high availability configurations
* Add monitoring and automation tools
