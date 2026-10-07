# Linux WSL Home Lab

A small Linux administration and troubleshooting lab built with
Ubuntu and WSL 2.

## Architecture

- client — administrative workstation
- server01 — primary Linux server, SSH port 2221
- server02 — secondary Linux server, SSH port 2222

## Topics practised

- Linux user administration
- Users and groups
- File and directory permissions
- Basic command-line administration
- SSH
- SSH key authentication
- Linux services with systemd
- TCP/IP troubleshooting
- DNS
- UFW firewall
- Git
- Troubleshooting methodology

## Troubleshooting exercises

1. File permission denied
2. SSH service stopped
3. Incorrect SSH port
4. Incorrect DNS configuration
5. SSH key permission problem

## WSL networking limitation

The WSL 2 distributions used in this lab share the WSL networking
environment, so separate SSH ports were used for each SSH server.