# Home Lab Project Status - Thor's YouTube Portfolio Series

**Last Updated:** June 13, 2026

## Hardware Overview

### Proxmox Host Server (HP Z640)
- **CPU**: Dual Intel Xeon E5-2643 v3 @ 3.40GHz
- **RAM**: 64GB DDR4 ECC
- **Storage**:
  - 120GB HDD/SSD - OS (Proxmox) installed
  - 1TB HDD - Storage / Data
- **GPUs**:
  - Quadro K2200 - For host video output
  - RTX 4060 - For GPU passthrough to VMs (primarily Kali for Hashcat)
- **PSU**: 950W
- **Hypervisor**: Proxmox VE 9.2.3 (installed and running)

### Client Desktop PC
- **CPU**: AMD Ryzen 7 5700X
- **RAM**: 32GB DDR4 3600MHz CL18
- **PSU**: 850W Corsair Modular
- **GPU**: Radeon RX 9070 XT (corrected)
- **OS**: Ubuntu 26.04 LTS

## YouTube Series Progress

### Completed Episodes
- **Episode 1**: Proxmox Installation on HP Z640 - Uploaded
- **Episode 2**: Jellyfin Media Server + Introduction to Containers (LXC) - Uploaded

### Planned Episodes & Roadmap
- **Episode 3**: GPU Passthrough (RTX 4060 to Kali Linux VM for Hashcat acceleration)
- **Episode 4**: OPNsense Virtual Machine Install and Setup (Firewall/Router)
- **Episode 5**: Kali Linux VM Setup (full configuration)
- **Episode 6**: WireGuard VPN in OPNsense + Remote Desktop Access to Kali from Desktop PC

## Project Goals
- Build a robust homelab environment documented in video episodes
- Demonstrate Proxmox skills, GPU passthrough, secure networking (OPNsense + WireGuard), and pentesting tools (Kali + Hashcat)
- Portfolio content for YouTube showcasing practical sysadmin / homelab / security skills

## Next Steps for Episode 3
- Detailed GPU passthrough guide needed (IOMMU, VFIO, VM config, NVIDIA drivers in guest)

**Notes**: 
- All episodes recorded with focus on educational value for viewers building similar setups.
- Desktop GPU correction: RX 9070 XT (not 7900 XT).
