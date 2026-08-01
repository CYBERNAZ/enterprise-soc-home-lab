# Zeek Network Security Monitor

## Overview

Zeek is deployed to monitor network traffic and generate detailed security logs for analysis and threat hunting.

---

## Installation

Installed Zeek from source.

Verified installation.

```bash
zeek --version
```

Configured monitoring interface.

Modified:

node.cfg

Configured interface:

enp6s18

---

## Deployment

Executed:

```bash
zeekctl deploy
```

Verified successful startup.

---

## Log Collection

Generated logs:

- conn.log
- dns.log
- http.log
- ssl.log
- notice.log
- weird.log

Verified logs inside:

/usr/local/zeek/spool/zeek

---

## Skills Demonstrated

- Network Monitoring
- Linux Administration
- Log Analysis
- Network Visibility

---

## Lessons Learned

- Zeek configuration
- Interface selection
- Log verification
- Troubleshooting deployments

---

## Screenshots

Add:

- zeek --version
- zeekctl deploy
- Log directory
