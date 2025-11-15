---
layout: single
title: "Episode 21: Logger Command"
collection: labs
---

## Objective
Learn to generate and write custom log entries using the `logger` command, useful for testing log pipelines and SIEM alerts.

---

## Commands Practiced
| Command | Description |
|----------|-------------|
| `logger "Test message"` | Write a simple log entry |
| `logger -t security_test "Unauthorized access attempt"` | Add a tag to the message |
| `logger -p auth.warning "Failed SSH login detected"` | Use priority and facility flags |
| `grep "security_test" /var/log/syslog` | Verify tag in system logs |
| `tail -f /var/log/syslog` | View log events in real time |

---

## Key Takeaways
- `logger` is a safe way to generate log events for testing and validation.  
- Tags and priority flags help simulate different log types.  
- `logger` becomes powerful when combined with grep, tail, and SIEM alerts.  

---

## SOC Application
Analysts use `logger` to:
- Test alert rules in Splunk, Wazuh, or Elastic.
- Validate log forwarding.
- Simulate detection events in a lab for training or automation.

---

## Next Step
Move to **Episode 22: chmod**, focusing on file permissions and access control.
