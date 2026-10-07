
# Lab Setup

## Overview

This home lab was created to practise basic Linux administration, SSH, networking, DNS, firewall configuration and troubleshooting.

The environment runs on Windows using WSL 2 and Ubuntu.

The lab contains three separate Ubuntu distributions:

- `client`
- `server01`
- `server02`

The `client` system is used as the administrative workstation.

`server01` and `server02` are used as Linux servers that can be accessed remotely from the client using SSH.

Although the three Ubuntu distributions are separate Linux environments, WSL 2 does not behave exactly like three independent virtual machines. The distributions share parts of the WSL networking environment. Because of this, different SSH ports are used for the two servers.

The lab architecture is:

Windows
 - WSL 2
    - client
        -  Administrative workstation
    - server01
        -  SSH port 2221
    - Server02
        - SSH port 2222

## Purpose of the Lab
The purpose of this environment is to practise Linux administration in a controlled environment where configuration changes and troubleshooting exercises can be performed safely.

The lab is used to practise:
- Linux users and groups
- File and directory permissions
- Linux command-line administration
- Service management
- SSH
- SSH key authentication
- Networking
- DNS
- Firewall configuration
- Troubleshooting
- Git and GitHub

The main goal is not only to learn individual commands, but also to understand what each component does and how to troubleshoot problems systematically.