# Home Lab Documentation

## Overview
This repository documents my home lab, which I use to learn and practice: 
- Linux system administration
- Virtualization with Proxmox
- Networking and segmentation
- Logging and security monitoring
- Self-hosted services

## Hardware
- 3x HP Mini PCs
    - Intel Core i5-9500T (Coffee Lake, 6 core, 6 thread, 35w TDP)
    - 32GB DDR4 RAM
- 1GbE networking and 2.5GbE networking for Ceph
- UPS with NUT for graceful shutdowns

## Virtualizaiton Platform
- Proxmox VE cluster (3 nodes)
- Local storage + Ceph clustered storage + NAS backup for VM disks using Proxmox Backup Server

## Services
- Jellyfin (media server)
- Minecraft server
- Opensearch (centralized logging/SIEM)
- Cloudflare Tunnel (secure remote access)

## Security focus
- Centralized logging via Opensearch
- Separation of services using VMs and LXCs
- TLS and secure remote access via Cloudflare

## Goals
- Demonstrate practical sysadmin and cybersecurity skills
- Create a shareable portfolio for SOC/IT roles
