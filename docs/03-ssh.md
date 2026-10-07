
---

## 3. `docs/03-ssh.md`

```markdown
# SSH

## Overview

SSH stands for Secure Shell.

It is a protocol used to securely connect to and administer remote systems through a command-line interface.

In this lab, the `client` system is used as an administrative workstation and connects remotely to `server01` and `server02`.

The SSH layout is:

```text
client
 - SSH port 2221 ──> server01
 - SSH port 2222 ──> server02
````

## What I Learned

This exercise demonstrated that a successful SSH connection depends on several components working together.

The client must use:
- The correct destination address
- The correct port
- A valid username
- A valid authentication method

The server must have:
- A running SSH service
- A valid SSH configuration
- A listening TCP port
- Correct authentication settings
- Correct file permissions

SSH also demonstrated the difference between a Linux system being online and a specific service being available.
A server can be running normally while the SSH service itself is stopped.