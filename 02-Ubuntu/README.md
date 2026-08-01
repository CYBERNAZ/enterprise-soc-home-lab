# Ubuntu Server 24.04

## Overview

Ubuntu Server serves as the primary Linux administration host within the Enterprise SOC Home Lab. It is responsible for hosting Zeek Network Security Monitor and supporting network monitoring and security analysis.

---

# Objectives

- Deploy Ubuntu Server
- Configure networking
- Install development tools
- Compile Zeek from source
- Verify packet monitoring

---

# Installation

- Installed Ubuntu Server 24.04 LTS
- Updated system packages
- Configured administrative user
- Verified network connectivity

---

# System Update

```bash
sudo apt update
sudo apt upgrade -y
```

---

# Installed Packages

```bash
sudo apt install -y \
cmake \
make \
gcc \
g++ \
flex \
bison \
libpcap-dev \
libssl-dev \
python3 \
python3-pip \
swig \
zlib1g-dev
```

---

# Zeek Installation

Zeek was compiled from source and installed successfully.

Installation Path

```
/usr/local/zeek
```

Version

```bash
zeek --version
```

Result

```
Zeek version 9.x
```

---

# Configuration

Zeek interface configured

```
eth0
```

Configuration file

```
/usr/local/zeek/etc/node.cfg
```

Deployment

```bash
sudo /usr/local/zeek/bin/zeekctl deploy
```

---

# Troubleshooting

### PATH issue

Problem

```
zeek: command not found
```

Resolution

Added Zeek to PATH

```bash
export PATH=$PATH:/usr/local/zeek/bin
```

Updated

```
~/.bashrc
```

Reloaded

```bash
source ~/.bashrc
```

---

### Zeek Deployment

Verified deployment

```bash
sudo /usr/local/zeek/bin/zeekctl deploy
```

Verified logs

```bash
ls /usr/local/zeek/spool/zeek
```

---

# Skills Demonstrated

- Linux Administration
- Source Compilation
- Package Management
- Network Monitoring
- Zeek Deployment
- Troubleshooting

---

# Status

| Component | Status |
|-----------|--------|
| Ubuntu Installed | ✅ |
| Packages Updated | ✅ |
| Zeek Installed | ✅ |
| Zeek Configured | ✅ |
| Zeek Running | ✅ |
