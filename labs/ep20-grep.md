---
layout: single
title: "Episode 20: grep Command"
collection: labs
---

## Objective
Learn how to search and filter log data efficiently using the `grep` command, a critical tool for Linux-based security operations.

---

## Commands Practiced
| Command | Description |
|----------|-------------|
| `grep "error" /var/log/syslog` | Search for “error” in system log |
| `grep -i "fail" /var/log/auth.log` | Case-insensitive search for “fail” |
| `grep -r "ssh" /var/log/` | Recursive search in directories |
| `grep -A 3 -B 3 "error" logfile` | Show 3 lines before and after a match |
| `grep -E "[0-9]+\.[0-9]+\.[0-9]+\.[0-9]+" logfile` | Match IP addresses using regex |
| `ps aux | grep ssh` | Filter running processes for SSH |

---

## Key Takeaways
- `grep` enables rapid log searching across files and directories.  
- Regular expressions (`-E`) make pattern searches powerful for IPs and timestamps.  
- Combining `grep` with other commands using pipes improves investigation speed.  
- Recursive searches help analysts quickly find indicators across system logs.  

---

## SOC Application
In a SOC, `grep` is often used to:
- Find signs of brute-force logins in `/var/log/auth.log`.  
- Filter error events in application logs.  
- Extract network connections or process names from large text files.  

---

## Next Step
Proceed to **Episode 21: logger**, focusing on generating and managing system log entries.
