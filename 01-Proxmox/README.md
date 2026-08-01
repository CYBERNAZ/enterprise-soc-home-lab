# 01 - Proxmox VE

## Overview

This section documents the installation and configuration of Proxmox VE used as the virtualization platform for my Enterprise SOC Home Lab.
# Proxmox VE Installation

## Overview

This document describes the installation and configuration of the Proxmox Virtual Environment (VE) used as the virtualization platform for my Enterprise SOC Home Lab.

---

## Hardware

| Component | Specification |
|-----------|---------------|
| Host | Bosgame P3 Plus Mini PC |
| CPU | Intel Processor |
| RAM | 32 GB |
| Storage | 1 TB NVMe SSD |
| Hypervisor | Proxmox VE 9.x |

---

## Objectives

- Build an enterprise-style SOC lab
- Run multiple virtual machines
- Simulate attacker and victim environments
- Deploy SIEM and network monitoring tools
- Perform attack simulations and incident investigations

---

## Virtual Machines

| VM | Purpose |
|----|----------|
| Ubuntu Server | Zeek & management |
| Windows Server 2022 | Active Directory Domain Controller |
| Windows 10 | Domain client |
| Kali Linux | Attacker machine |
| Security Onion | Network monitoring |
| Wazuh | SIEM & Endpoint Detection |

---

## Network

The lab uses an isolated virtual network allowing communication between all virtual machines while remaining separated from the production home network.

---

## Status

✅ Proxmox Installed

✅ Networking Configured

✅ Virtual Machines Created

🚧 Documentation in Progress
