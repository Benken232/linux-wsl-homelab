
---

## 2. `docs/02-users-permissions.md`

```markdown
# Users and Permissions

## Overview

Linux is a multi-user operating system.

Each user has a separate identity, home directory and set of permissions.

Users can also belong to groups. Groups make it possible to give several users access to the same files or directories without giving access to every user on the system.

In this lab I created multiple users and configured different permissions to practise Linux access control.

The exercises were performed mainly on `server01`.

## Creating Users

Three users were created:

```bash
sudo adduser alice
sudo adduser bob
sudo adduser charlie

```

## What I Learned
This exercise demonstrated how Linux controls access using a combination of users, groups, ownership and permission bits.

I also learned that a permission problem cannot be diagnosed by looking at only one setting.
When troubleshooting access problems, I should check:

- Which user is trying to access the file?
- Who owns the file or directory?
- Which group owns it?
- Which groups does the user belong to?
- What permissions are configured?

The exercise also showed why groups are useful for shared resources. Instead of giving permissions individually to every user, access can be controlled through group membership.