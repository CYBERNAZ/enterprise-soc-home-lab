# Proxmox Virtual Environment (VE)

## Overview

Proxmox VE is the virtualization platform powering my Enterprise SOC Home Lab. It provides centralized management of virtual machines used to simulate a realistic enterprise network for security monitoring, threat detection, and incident response.

---

# Objectives

- Build an enterprise SOC lab
- Host multiple Windows and Linux virtual machines
- Simulate attacker and victim environments
- Deploy enterprise security tools
- Practice Blue Team investigations

---

# Hardware

| Component | Specification |
|-----------|---------------|
| Host | Bosgame P3 Plus Mini PC |
| RAM | 32 GB DDR5 |
| Storage | 1 TB NVMe SSD |
| Hypervisor | Proxmox VE 9.x |

---

# Virtual Machines

| VM | Purpose |
|----|----------|
| Ubuntu Server | Zeek Network Security Monitor |
| Windows Server 2022 | Active Directory Domain Controller |
| Windows 10 | Enterprise Client |
| Kali Linux | Attacker Machine |
| Security Onion | Network Monitoring Platform |

---

# Virtual Network

The virtual machines communicate over an isolated lab network to safely simulate enterprise attack scenarios while remaining separated from the production home network.

---

# Skills Demonstrated

- Virtualization
- Hypervisor Administration
- Enterprise Networking
- Resource Management
- VM Provisioning

---

# Current Status

| Component | Status |
|-----------|--------|
| Proxmox Installed | ✅ |
| Virtual Networking | ✅ |
| Ubuntu VM | ✅ |
| Windows Server 2022 | ✅ |
| Windows 10 | ✅ |
| Kali Linux | ✅ |
| Security Onion | ✅ |

---

# Screenshots

Screenshots documenting the installation and configuration process are available in the `15-Screenshots` directory.

---

# Lessons Learned

- Proper VM resource allocation improves performance.
- Network planning simplifies security tool deployment.
- Proxmox snapshots provide quick recovery during testing.
