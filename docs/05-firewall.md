
---

## 5. `docs/05-firewall.md`

```markdown
# Firewall Configuration

## Overview

A firewall controls which network traffic is allowed or blocked.

In this lab I used UFW to practise basic Linux firewall administration.

UFW stands for:

```text
Uncomplicated Firewall
```

## What I Learned
This exercise showed that a successful network connection depends on more than just the firewall.
For a service such as SSH to work:
- The SSH service must be running.
- The SSH service must listen on the expected port.
- The firewall must allow the port.
- The client must connect to the correct port.
- Authentication must succeed.

I also learned that firewall troubleshooting should be systematic.
Instead of immediately disabling the firewall, I should inspect the service, listening ports and firewall rules to determine where the failure occurs.