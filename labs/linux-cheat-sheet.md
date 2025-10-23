---
layout: single
title: "Linux Command Reference"
collection: labs
---

# Linux Cheat Sheet

This page lists the core Linux commands practiced during my Security+ Home Lab training (Episode 17).  
These commands help with network troubleshooting, system monitoring, and log analysis — critical skills for SOC analysts.

---

## **System Information**
| Command | Description |
|----------|--------------|
| `hostname` | Show system hostname |
| `hostnamectl` | Display or set system hostname |
| `lsb_release -a` | Show distribution details |
| `uname -a` | Display kernel and system information |
| `uptime` | Show system uptime |

---

## **Network and Connectivity**
| Command | Description |
|----------|--------------|
| `ping` | Test network connectivity |
| `traceroute` | Display packet route to destination |
| `netstat -antup` | Show active connections and listening ports |
| `ss -tulnp` | Modern alternative to netstat |
| `ifconfig` | Display network interfaces |
| `ip addr` | Show IP configuration |
| `nslookup` | Query DNS records |
| `dig` | Perform advanced DNS queries |

---

## **File and Directory Management**
| Command | Description |
|----------|--------------|
| `ls -l` | List files with details |
| `mkdir` | Create directories |
| `cd` | Change directory |
| `cp` | Copy files or directories |
| `mv` | Move or rename files |
| `rm -r` | Remove files or directories |
| `touch` | Create empty files |
| `tree` | Display directory structure |

---

## **Process and Resource Monitoring**
| Command | Description |
|----------|--------------|
| `top` | Monitor system processes |
| `htop` | Interactive process viewer |
| `free -h` | Display memory usage |
| `ps aux` | Show running processes |
| `df -h` | Show disk usage |

---

## **Package Management (Debian/Ubuntu)**
| Command | Description |
|----------|--------------|
| `apt update` | Refresh package lists |
| `apt upgrade` | Upgrade installed packages |
| `apt install <pkg>` | Install a package |
| `apt remove <pkg>` | Uninstall a package |

---

## **Archiving and Compression**
| Command | Description |
|----------|--------------|
| `tar -cvf` | Create a tar archive |
| `tar -xvf` | Extract a tar archive |
| `gzip <file>` | Compress files |
| `gunzip <file>` | Decompress files |

---

## **Useful Keyboard Shortcuts**
| Shortcut | Action |
|-----------|--------|
| `Ctrl + A` | Move to start of line |
| `Ctrl + E` | Move to end of line |
| `Ctrl + K` | Delete to end of line |
| `Ctrl + U` | Delete from start of line |
| `Ctrl + C` | Stop a command |
| `Ctrl + Z` | Suspend current process |

---

## **Why This Matters**
Linux is the backbone of most SOC environments.  
Knowing how to move quickly and accurately in a Linux terminal improves your investigation speed and response quality.  

---

## **Next Step**
Next in my Security+ Home Lab series:  
**Incident Response tools and hands-on investigation workflows.**
